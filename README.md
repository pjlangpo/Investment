<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Investment Opportunities</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Investment Opportunities</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#types">Types of Investments</a></li>
                <li><a href="#benefits">Benefits</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="home">
            <h2>Welcome to Our Investment Platform</h2>
            <p>Explore various investment opportunities to grow your wealth. Our platform offers a wide range of investment options tailored to your needs.</p>
        </section>
        
        <section id="types">
            <h2>Types of Investments</h2>
            <ul>
                <li>Stocks</li>
                <li>Bonds</li>
                <li>Real Estate</li>
                <li>Mutual Funds</li>
                <li>Cryptocurrencies</li>
            </ul>
        </section>
        
        <section id="benefits">
            <h2>Benefits of Investing with Us</h2>
            <ul>
                <li>Diversified Portfolio</li>
                <li>Expert Advice</li>
                <li>High Returns</li>
                <li>Secure Platform</li>
            </ul>
        </section>
        
        <section id="contact">
            <h2>Contact Us</h2>
            <form action="submit_form.php" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2024 Investment Opportunities. All rights reserved.</p>
    </footer>
</body>
</html>
