 HTML code for a simple website displaying a hotel menu.

</think>```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Menu - Grand Vista Hotel</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .menu-section {
            margin: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #333;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            padding: 10px 0;
            border-bottom: 1px solid #eee;
        }
        .price {
            float: right;
            font-weight: bold;
            color: #007bff;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Grand Vista Hotel Menu</h1>
        <p>Enjoy our exquisite dining options</p>
    </header>

    <section class="menu-section">
        <h2>Breakfast</h2>
        <ul>
            <li>Continental Breakfast <span class="price">$12.99</span></li>
            <li>American Pancakes <span class="price">$15.99</span></li>
            <li>Omelette with Vegetables <span class="price">$14.99</span></li>
            <li>Fresh Fruit Platter <span class="price">$10.99</span></li>
        </ul>
    </section>

    <section class="menu-section">
        <h2>Lunch</h2>
        <ul>
            <li>Grilled Chicken Salad <span class="price">$18.99</span></li>
            <li>Beef Burger <span class="price">$16.99</span></li>
            <li>Vegetarian Pasta <span class="price">$15.99</span></li>
            <li>Club Sandwich <span class="price">$14.99</span></li>
        </ul>
    </section>

    <section class="menu-section">
        <h2>Dinner</h2>
        <ul>
            <li>Steak with Mashed Potatoes <span class="price">$29.99</span></li>
            <li>Grilled Salmon <span class="price">$26.99</span></li>
            <li>Vegetable Stir-Fry <span class="price">$22.99</span></li>
            <li>Seafood Paella <span class="price">$32.99</span></li>
        </ul>
    </section>

    <section class="menu-section">
        <h2>Drinks</h2>
        <ul>
            <li>Coffee <span class="price">$3.99</span></li>
            <li>Tea <span class="price">$2.99</span></li>
            <li>Fresh Juice <span class="price">$5.99</span></li>
            <li>House Wine <span class="price">$8.99</span></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2023 Grand Vista Hotel. All rights reserved.</p>
    </footer>
</body>
</html>
```