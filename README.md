<!DOCTYPE html>
<html>
<head>
<title>Green Dot Bank</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: linear-gradient(-45deg, #0f2027, #203a43, #2c5364, #0f3057);
    background-size: 400% 400%;
    animation: gradient 12s ease infinite;
    color: white;
}

@keyframes gradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

header {
    display: flex;
    justify-content: space-between;
    padding: 20px 60px;
    background: rgba(0,0,0,0.6);
    backdrop-filter: blur(10px);
    position: fixed;
    width: 100%;
}

.logo {
    font-size: 22px;
    font-weight: bold;
    color: #2ecc71;
}

nav a {
    margin-left: 25px;
    text-decoration: none;
    color: white;
    font-size: 15px;
}

nav a:hover {
    color: #2ecc71;
}

.hero {
    padding-top: 160px;
    text-align: center;
    padding-bottom: 120px;
}

.hero h1 {
    font-size: 50px;
}

.hero p {
    margin-top: 15px;
    color: #ccc;
}

.btn {
    margin-top: 30px;
    padding: 14px 30px;
    background: #2ecc71;
    border: none;
    border-radius: 30px;
    font-weight: bold;
    cursor: pointer;
}

.section {
    padding: 80px 20px;
    text-align: center;
    background: rgba(0,0,0,0.5);
}

.card-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.card {
    background: rgba(255,255,255,0.08);
    margin: 20px;
    padding: 30px;
    width: 260px;
    border-radius: 15px;
    backdrop-filter: blur(10px);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

footer {
    background: black;
    padding: 20px;
    text-align: center;
}
</style>
</head>

<body>

<header>
    <div class="logo">Green Dot Bank</div>
    <nav>
        <a href="#">Home</a>
        <a href="#services">Services</a>
        <a href="#">About</a>
        <a href="#">Login</a>
    </nav>
</header>

<section class="hero">
    <h1>Banking Made Simple & Secure</h1>
    <p>Modern digital banking built for individuals and businesses.</p>
    <button class="btn">Open an Account</button>
</section>

<section class="section" id="services">
    <h2>Our Services</h2>
    <div class="card-container">
        <div class="card">
            <h3>Online Banking</h3>
            <p>Manage your account anytime from anywhere.</p>
        </div>

        <div class="card">
            <h3>Secure Payments</h3>
            <p>Encrypted transactions with real-time alerts.</p>
        </div>

        <div class="card">
            <h3>Business Solutions</h3>
            <p>Smart financial tools for companies.</p>
        </div>
    </div>
</section>

<footer>
    © 2026 Green Dot Bank | All Rights Reserved
</footer>

</body>
</html>
