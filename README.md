<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shushil Kirana Store</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f4f6f9;
}

header{
background:linear-gradient(135deg,#28a745,#1d7d34);
color:white;
text-align:center;
padding:80px 20px;
}

header h1{
font-size:3rem;
}

header p{
margin-top:10px;
font-size:1.2rem;
}

.btn{
display:inline-block;
margin-top:20px;
padding:12px 25px;
background:white;
color:#28a745;
text-decoration:none;
border-radius:30px;
font-weight:bold;
}

.section{
padding:50px 20px;
max-width:1200px;
margin:auto;
}

.section h2{
text-align:center;
margin-bottom:30px;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.card{
background:white;
padding:20px;
border-radius:15px;
box-shadow:0 4px 12px rgba(0,0,0,0.1);
text-align:center;
transition:0.3s;
}

.card:hover{
transform:translateY(-5px);
}

.card h3{
margin-bottom:10px;
}

.review{
background:white;
padding:20px;
border-radius:15px;
margin:10px 0;
box-shadow:0 2px 8px rgba(0,0,0,0.1);
}

footer{
background:#222;
color:white;
text-align:center;
padding:20px;
margin-top:30px;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}
</style>
</head>

<body>

<header>
<h1>🛒 Shushil Kirana Store</h1>
<p>Fresh Grocery Delivered To Your Door</p>
<a href="https://wa.me/918423723222" class="btn">Order on WhatsApp</a>
</header>

<section class="section">
<h2>📦 Our Products</h2>

<div class="products">

<div class="card">
<h3>🌾 Atta</h3>
<p>Premium Quality Wheat Flour</p>
</div>

<div class="card">
<h3>🍚 Chawal</h3>
<p>Best Quality Rice</p>
</div>

<div class="card">
<h3>🥣 Dal</h3>
<p>Fresh Pulses Available</p>
</div>

<div class="card">
<h3>🌶️ Masala</h3>
<p>All Spice Products</p>
</div>

<div class="card">
<h3>🧼 Sabun</h3>
<p>Daily Use Soaps</p>
</div>

<div class="card">
<h3>🛢️ Tel</h3>
<p>Cooking Oil Available</p>
</div>

<div class="card">
<h3>🍪 Biscuit</h3>
<p>All Popular Brands</p>
</div>

<div class="card">
<h3>🧺 Surf</h3>
<p>Detergent Powder & Liquid</p>
</div>

</div>
</section>

<section class="section">
<h2>🚚 Home Delivery</h2>
<div class="review">
<p>We can provide home delivery service in nearby areas.</p>
</div>
</section>

<section class="section">
<h2>⭐ Customer Reviews</h2>

<div class="review">
★★★★★ Good quality products and affordable prices.
</div>

<div class="review">
★★★★★ Fast service and friendly shopkeeper.
</div>

</section>

<footer>
<h3>📍 Sarai Shekh, Lucknow</h3>
<p>📞 8423723222</p>
<p>© 2026 Shushil Kirana Store</p>
</footer>

<a class="whatsapp" href="https://wa.me/918423723222">
WhatsApp
</a>

</body>
</html>
