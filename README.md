<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tax Collection Portal</title>
    <link rel="stylesheet" href="styles.css">
    
    <style>
      body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

nav li {
    margin-right: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background-image: linear-gradient(to bottom, #333, #555);
    color: #fff;
    padding: 5em;
    text-align: center;
}

.tax-form {
    padding: 2em;
    background-color: #f0f0f0;
    border: 1px solid #ddd;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin: 2em auto;
    width: 80%;
}

.label {
    display: block;
    margin-bottom: 10px;
}

input, select {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
}

button[type="submit"] {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button[type="submit"]:hover {
    background-color: #555;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
    clear: both;
}
      
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>Motorist Tax Collection Portal</h1>
            <p>Pay your taxes online</p>
            <button>Pay Now</button>
        </section>
        <section class="tax-form">
            <h2>Tax Payment Form</h2>
            <form>
                <label for="vehicle-type">Vehicle Type:</label>
                <select id="vehicle-type" name="vehicle-type">
                    <option value="car">Car</option>
                    <option value="truck">Truck</option>
                    <option value="motorcycle">Motorcycle</option>
                </select>
                <label for="license-number">License Number:</label>
                <input type="text" id="license-number" name="license-number">
                <label for="tax-amount">Tax Amount:</label>
                <input type="number" id="tax-amount" name="tax-amount">
                <button type="submit">Pay Tax</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Tax Collection Portal</p>
    </footer>
</body>
</html>
