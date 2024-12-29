# Landing-page:
### HTML Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Landing Page</title>
</head>
<body>
    <header class="header">
        <h1>Welcome to Our Landing Page</h1>
        <p>Your journey starts here!</p>
        <a href="#" class="button">Get Started</a>
    </header>
    <main class="content">
        <section class="section">
            <h2>About Us</h2>
            <p>We are dedicated to providing the best service.</p>
        </section>
        <section class="section">
            <h2>Services</h2>
            <p>Explore our wide range of services tailored for you.</p>
        </section>
    </main>
    <footer class="footer">
        <p>&copy; 2024 Your Company. All rights reserved.</p>
    </footer>
</body>
</html>
```

### CSS Code (styles.css):

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f4f4;
}

.header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
}

.content {
    display: flex;
    justify-content: space-around;
    padding: 20px;
}

.section {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 20px;
    width: 45%;
}

.button {
    display: inline-block;
    background-color: #008CBA;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: relative;
    bottom: 0;
    width: 100%;
}
,,,
