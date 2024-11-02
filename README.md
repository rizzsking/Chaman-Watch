/* Basic reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    color: #333;
    background-color: #f9f9f9;
}

/* Header */
header {
    background-color: #ffffff;
    padding: 10px 0;
    border-bottom: 1px solid #ddd;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 90%;
    margin: auto;
}

.logo {
    width: 150px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ff9900; /* Accent color on hover */
}

/* Hero Section */
.hero {
    background: url('images/hero.jpg') no-repeat center center/cover;
    color: #fff;
    padding: 100px 0;
    text-align: center;
}

.hero-content {
    max-width: 600px;
    margin: auto;
}

.hero h1 {
    font-size: 2.5em;
}

.hero .cta {
    margin-top: 20px;
    background-color: #ff9900; /* Accent color */
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

/* Product Section */
.products {
    padding: 50px 0;
    text-align: center;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    padding: 0 20px;
}

.product {
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    padding: 20px;
    transition: transform 0.3s;
}

.product img {
    max-width: 100%;
    border-radius: 5px;
}

.product h3 {
    margin: 10px 0;
}

/* Testimonials */
.testimonials {
    padding: 50px 0;
    text-align: center;
    background-color: #f1f1f1;
}

.testimonial {
    margin: 20px 0;
}

/* About Us */
.about {
    padding: 50px 20px;
    text-align: center;
}

/* Contact Section */
.contact {
    padding: 50px 20px;
    text-align: center;
}

.contact form {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
}

.contact input,
.contact textarea {
    width: 300px;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.contact button {
    background-color: #ff9900; /* Accent color */
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact button:hover {
    background-color: #cc7a00; /* Darker shade on hover */
}

/* Map Section */
.map {
    padding: 50px 20px;
    text-align: center;
}

.map iframe {
    width: 100%;
    height: 300px;
    border: none;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

footer ul {
    list-style: none;
    padding: 0;
}

footer ul li {
    display: inline;
    margin: 0 10px;
}

footer ul li a {
    color: #ff9900; /* Accent color */
    text-decoration: none;
}
