<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Fashion Hub</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #5b5454;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }

        nav {
            background-color: #4caf50;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: rgb(92, 221, 199);
            text-decoration: turquoise;
            padding: 10px 20px;
            margin: 0 10px;
            border-radius: 4px;
            background-color: #45a049;
        }

        nav a:hover {
            background-color: #333;
            font-style: oblique;
        }

        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .product {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin: 10px;
            width: 300px;
            background-color: rgb(179, 184, 218);
            text-align: center;
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            margin-bottom: 10px;
        }

        
        button {
            border-radius:4px ;
            background-color: blueviolet;
        }
    </style>
</head>
<body>

    <header>
        <h1> Fashion Hub</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Dresses</a>
        <a href="#">Contact</a>
    </nav>

    <section id="products">
        <div class="product">
            <img src="dress1.jpg" alt="Dress 1">
            <h2>Beautiful Party Dress</h2>
            <p>Description of the dress. Party Wear</p>
            <p>Price: $4999.99</p>
            <button>Add to Cart</button>
        </div>

        <div class="product">
            <img src="dress2.jpg" alt="Dress 2">
            <h2>Elegant Summer Gown</h2>
            <p>Description of the dress.Casual Wear</p>
            <p>Price: $899.99</p>
            <button>Add to Cart</button>
        </div>
        

        <div class="product">
            <img src="dress3.jpg" alt="Dress 3">
            <h2>Elegant Occational Gown</h2>
            <p>Description of the dress.Occational Wear</p>
            <p>Price: $2999.99</p>
            <button>Add to Cart</button>
        </div>

        <div class="product">
            <img src="dress4.jpg" alt="Dress 4">
            <h2>Elegant Evening Gown</h2>
            <p>Description of the dress. Party Wear</p>
            <p>Price: $1999.99</p>
            <button>Add to Cart</button>
        </div>

        <div class="product">
            <img src="dress5.jpg" alt="Dress 5">
            <h2>Elegant Summer Top</h2>
            <p>Description of the dress. College Wear.</p>
            <p>Price: $999.99</p>
            <button>Add to Cart</button>
        </div>

    
    </section>

    

</body>
</html>


<!---
saranya348/saranya348 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
