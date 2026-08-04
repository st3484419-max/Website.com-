# Website.com-<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tiwari Restaurant</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f4f4;
    color:#333;
}

header{
    background:#8B0000;
    color:white;
    padding:20px;
    text-align:center;
}

nav{
    background:#111;
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
}

nav a{
    color:white;
    text-decoration:none;
    padding:15px 20px;
}

nav a:hover{
    background:#8B0000;
}

.hero{
    height:400px;
    background:url('https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?w=1200') center/cover;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    text-align:center;
}

.hero h1{
    font-size:50px;
    background:rgba(0,0,0,0.5);
    padding:15px;
    border-radius:10px;
}

section{
    padding:50px 20px;
    text-align:center;
}

.menu{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    margin-top:30px;
}

.card{
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.2);
}

.card h3{
    color:#8B0000;
}

.price{
    font-size:22px;
    color:green;
    margin-top:10px;
}

button{
    margin-top:15px;
    padding:10px 20px;
    background:#8B0000;
    color:white;
    border:none;
    border-radius:5px;
    cursor:pointer;
}

button:hover{
    background:#b30000;
}

.contact{
    background:#222;
    color:white;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:15px;
}
</style>

</head>
<body>

<header>
    <h1>Tiwari Restaurant</h1>
    <p>Fresh Food • Great Taste • Fast Service</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
    <h1>Welcome to Tiwari Restaurant</h1>
</div>

<section id="about">
    <h2>About Us</h2>
    <br>
    <p>
        We serve delicious Indian food prepared with fresh ingredients.
        Visit us with your family and friends for an unforgettable dining experience.
    </p>
</section>

<section id="menu">
    <h2>Our Menu</h2>

    <div class="menu">

        <div class="card">
            <h3>Paneer Butter Masala</h3>
            <p>Rich & Creamy Paneer Curry</p>
            <div class="price">₹220</div>
            <button>Order Now</button>
        </div>

        <div class="card">
            <h3>Veg Biryani</h3>
            <p>Spicy Dum Biryani</p>
            <div class="price">₹180</div>
            <button>Order Now</button>
        </div>

        <div class="card">
            <h3>Chicken Curry</h3>
            <p>Traditional Indian Style</p>
            <div class="price">₹280</div>
            <button>Order Now</button>
        </div>

        <div class="card">
            <h3>Butter Naan</h3>
            <p>Fresh Tandoor Bread</p>
            <div class="price">₹40</div>
            <button>Order Now</button>
        </div>

        <div class="card">
            <h3>Cold Drink</h3>
            <p>Chilled Soft Drinks</p>
            <div class="price">₹50</div>
            <button>Order Now</button>
        </div>

        <div class="card">
            <h3>Ice Cream</h3>
            <p>Vanilla, Chocolate & Mango</p>
            <div class="price">₹80</div>
            <button>Order Now</button>
        </div>

    </div>

</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <br>
    <p>📍 Manoharpur, Jharkhand</p>
    <p>📞 +91 9876543210</p>
    <p>📧 tiwarirestaurant@email.com</p>
    <br>
    <p>Open Daily: 9:00 AM – 10:00 PM</p>
</section>

<footer>
    © 2026 Tiwari Restaurant | All Rights Reserved
</footer>

</body>
</html>
