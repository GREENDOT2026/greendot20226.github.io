<!DOCTYPE html>
<html>
<head>
<title>Green Dot Bank</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family: 'Segoe UI', sans-serif;
}

body{
  background:
  linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.8)),
  url('https://images.unsplash.com/photo-1556742049-908f0d0a1b0c');
  background-size:cover;
  background-position:center;
  height:100vh;
  color:white;
}

/* NAVIGATION */
header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:20px 60px;
}

.logo{
  font-size:24px;
  font-weight:700;
  color:#2ecc71;
}

nav a{
  color:white;
  text-decoration:none;
  margin-left:30px;
  font-weight:500;
  transition:0.3s;
}

nav a:hover{
  color:#2ecc71;
}

/* HERO */
.hero{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:80px 60px;
}

.hero-text{
  max-width:500px;
}

.hero-text h1{
  font-size:48px;
  margin-bottom:20px;
}

.hero-text p{
  color:#ccc;
  margin-bottom:30px;
}

.cta-btn{
  padding:14px 30px;
  background:#2ecc71;
  border:none;
  border-radius:30px;
  font-weight:bold;
  cursor:pointer;
  transition:0.3s;
}

.cta-btn:hover{
  background:#27ae60;
}

/* LOGIN CARD */
.login-box{
  background:rgba(255,255,255,0.08);
  padding:40px;
  border-radius:20px;
  backdrop-filter:blur(15px);
  width:320px;
  box-shadow:0 0 40px rgba(0,0,0,0.6);
}

.login-box h2{
  margin-bottom:25px;
  text-align:center;
}

.login-box input{
  width:100%;
  padding:12px;
  margin-bottom:15px;
  border:none;
  border-radius:10px;
}

.login-box button{
  width:100%;
  padding:12px;
  background:#2ecc71;
  border:none;
  border-radius:10px;
  font-weight:bold;
  cursor:pointer;
}

.login-box button:hover{
  background:#27ae60;
}

footer{
  text-align:center;
  padding:20px;
  font-size:14px;
  background:black;
  position:absolute;
  bottom:0;
  width:100%;
}

</style>
</head>

<body>

<header>
  <div class="logo">Green Dot Bank</div>
  <nav>
    <a href="#">Home</a>
    <a href="#">Services</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>
</header>

<section class="hero">
  <div class="hero-text">
    <h1>Banking Made Secure & Intelligent</h1>
    <p>Experience next-generation digital banking with military-grade encryption and seamless financial management.</p>
    <button class="cta-btn">Open Account</button>
  </div>

  <div class="login-box">
    <h2>Client Login</h2>
    <input type="text" placeholder="Username">
    <input type="password" placeholder="Password">
    <button>Secure Login</button>
  </div>
</section>

<footer>
  © 2026 Green Dot Bank. All Rights Reserved.
</footer>

</body>
</html>
