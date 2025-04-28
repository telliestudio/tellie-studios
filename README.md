<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tellie Studios</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <div class="logo-container">
      <img src="path/to/your/logo.png" alt="Tellie Studios Logo">
    </div>
    <div class="mission-statement">
      <h1>Our Mission</h1>
      <p>At Tellie Studios, our mission is to inspire creativity and foster a love for art through engaging workshops, high-quality art kits, and personalized teaching. We are dedicated to helping individuals discover their artistic potential and share their unique expressions with the world.</p>
      <a href="#products" class="btn">Explore Our Kits</a>
    </div>
  </main>

  <footer>
    <p>&copy; 2025 Tellie Studios. All rights reserved.</p>
  </footer>
</body>
</html>

body {
  font-family: 'Arial, sans-serif';
  color: #333;
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: column;
 : center;
  justify-content: center;
  height: 100vh;
}

header {
  width: 100%;
  background-color: #f8f8f8;
  padding: 10px 0;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  padding: 0;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
}

.logo-container {
  text-align: center;
  margin: 20px 0;
}

.logo-container img {
  max-width: 200px;
  height: auto;
}

.mission-statement {
  text-align: center;
  margin: 20px 0;
}

.mission-statement h1 {
  font-size: 2em;
  margin-bottom: 10px;
}

.mission-statement p {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.btn {
  background-color: #ff6347;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

footer {
  width: 100%;
  text-align: center;
  background-color: #f8f8f8;
  padding: 10px 0;
  position: absolute;
  bottom: 0;
}
