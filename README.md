# Ex02 Commercial Website
## Date: 27-02-2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
### HTML:
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FlexBiz - Commercial Website</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <div class="logo">FlexBiz</div>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <h1>Grow Your Business With Us</h1>
    <p>We provide modern solutions for your commercial needs.</p>
    <button>Get Started</button>
</section>

<section class="services">
    <h2>Our Services</h2>
    <div class="service-container">
        <div class="service-box">
            <h3>Web Development</h3>
            <p>Professional and responsive websites for your business.</p>
        </div>
        <div class="service-box">
            <h3>Marketing</h3>
            <p>Digital marketing strategies that boost your brand.</p>
        </div>
        <div class="service-box">
            <h3>Consulting</h3>
            <p>Expert advice to improve efficiency and growth.</p>
        </div>
    </div>
</section>

<section class="about">
    <div class="about-text">
        <h2>About Us</h2>
        <p>We are a team of professionals dedicated to delivering high-quality commercial solutions for businesses of all sizes.</p>
    </div>
    <div class="about-img">
        <img src="https://via.placeholder.com/500x300" alt="About Image">
    </div>
</section>

<section class="contact">
    <h2>Contact Us</h2>
    <form>
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Your Email">
        <textarea rows="5" placeholder="Your Message"></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>© 2026 FlexBiz. All Rights Reserved.</p>
</footer>

</body>
</html>
```

### CSS:
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
}

header {
    background: #222;
    color: #fff;
    padding: 15px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: linear-gradient(to right, #4facfe, #00f2fe);
    color: #fff;
    height: 60vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
}

.hero h1 {
    font-size: 48px;
}

.hero button {
    margin-top: 20px;
    padding: 12px 25px;
    border: none;
    background: #fff;
    color: #333;
    cursor: pointer;
    font-size: 16px;
}

.services {
    padding: 50px;
    text-align: center;
}

.service-container {
    display: flex;
    justify-content: space-between;
    margin-top: 30px;
    flex-wrap: wrap;
}

.service-box {
    background: #f4f4f4;
    padding: 20px;
    width: 30%;
    border-radius: 8px;
}

.service-box h3 {
    margin-bottom: 15px;
}

.about {
    padding: 50px;
    background: #eee;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.about-text {
    width: 48%;
}

.about-img {
    width: 48%;
}

.about-img img {
    width: 100%;
    border-radius: 8px;
}

.contact {
    padding: 50px;
    text-align: center;
}

.contact form {
    max-width: 500px;
    margin: auto;
    display: flex;
    flex-direction: column;
}

.contact input,
.contact textarea {
    padding: 10px;
    margin: 10px 0;
}

.contact button {
    padding: 12px;
    border: none;
    background: #4facfe;
    color: #fff;
    cursor: pointer;
}

footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 15px;
}

@media(max-width: 768px) {
    .service-box {
        width: 100%;
        margin-bottom: 20px;
    }

    .about-text,
    .about-img {
        width: 100%;
        margin-bottom: 20px;
    }

    header {
        flex-direction: column;
    }

    nav ul {
        margin-top: 10px;
    }
}
```
## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8c332bb0-3bdb-41d1-a506-6181df20568e" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
