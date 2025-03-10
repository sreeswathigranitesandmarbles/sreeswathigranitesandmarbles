* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

header {
  background-color: #333;
  color: #fff;
  padding: 10px 0;
}

header .logo h1 {
  text-align: center;
  font-size: 2rem;
}

nav ul {
  list-style-type: none;
  display: flex;
  justify-content: center;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  text-decoration: none;
  color: #fff;
  font-size: 1rem;
}

nav ul li a:hover {
  color: #f2a900;
}

section {
  padding: 20px;
  text-align: center;
}

#home {
  background: #f4f4f4;
  padding: 40px 20px;
}

.hero h2 {
  font-size: 2.5rem;
  color: #333;
}

.hero p {
  font-size: 1.2rem;
  color: #555;
}

.cta-button {
  background-color: #f2a900;
  padding: 10px 20px;
  text-decoration: none;
  color: #fff;
  font-size: 1.1rem;
  border-radius: 5px;
}

.cta-button:hover {
  background-color: #e07b00;
}

#products {
  background-color: #eaeaea;
}

.product-gallery {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.product-item img {
  width: 100px;
  height: 100px;
  object-fit: cover;
}

#services ul {
  list-style-type: none;
  padding: 0;
}

#services ul li {
  font-size: 1.2rem;
  margin: 10px 0;
}

form input, form textarea, form button {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
}

form button {
  background-color: #f2a900;
  color: #fff;
  border: none;
  cursor: pointer;
}

form button:hover {
  background-color: #e07b00;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
}
