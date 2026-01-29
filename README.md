<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Hana Ella</title>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Segoe UI", sans-serif;
}

body {
    background-color: #111;
    color: #eee;
}

/* ===== HEADER ===== */
header {
    background: url("vila8.jpg.jpeg") center/cover;
    height: 90vh;
    display: flex;
    align-items: center;
    padding: 50px;
}

.hero {
    max-width: 500px;
}

.hero h1 {
    font-size: 42px;
    margin-bottom: 15px;
}

.hero p {
    line-height: 1.6;
    margin-bottom: 20px;
}

.hero button {
    padding: 10px 20px;
    background: #c49b63;
    border: none;
    color: #000;
    cursor: pointer;
}

/* ===== BEST SELLER ===== */
.section {
    padding: 60px 10%;
    background: #eee;
    color: #111;
}

.section h2 {
    text-align: center;
    margin-bottom: 40px;
}

.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    padding: 15px;
    text-align: center;
}

.card img {
    width: 100%;
    height: 160px;
    object-fit: cover;
}

.card h3 {
    margin: 10px 0;
}

.card button {
    background: #c49b63;
    border: none;
    padding: 8px 15px;
    cursor: pointer;
}

/* ===== MENU ===== */
.menu {
    padding: 60px 10%;
}

.menu h2 {
    text-align: center;
    margin-bottom: 40px;
}

.menu-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.menu-item {
    display: flex;
    gap: 15px;
}

.menu-item img {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    object-fit: cover;
}

.price {
    color: #c49b63;
}

/* ===== FOOTER ===== */
footer {
    background: #000;
    text-align: center;
    padding: 20px;
}
</style>
</head>

<body>

<header>
    <div class="hero">
        <h1>Welcome to Simple Dessert</h1>
        <p>Nikmati Dessert terbaik dengan rasa premium dan suasana yang nyaman.</p>
        <button>Learn More</button>
    </div>
</header>

<section class="section">
    <h2>Best Seller & Promo</h2>
    <div class="cards">
        <div class="card">
            <img src="vila1.jpg.jpeg">
            <h3>Banana Roll Crispy</h3>
           
        </div>
        <div class="card">
            <img src="vila6.jpg.jpeg">
            <h3>Matcha latte</h3>
            
        </div>
        <div class="card">
            <img src="vila5.jpg.jpeg">
            <h3>Tiramisu Cake</h3>
            
            
        </div>
    </div>
</section>

<section class="menu">
    <h2>Delicious Menu</h2>
    <div class="menu-list">
        <div class="menu-item">
            <img src="vila4.jpg.jpeg">
            <div>
                <h4>Strowberry Marshmellow</h4>
                
            </div>
        </div>
        <div class="menu-item">
            <img src="vila2.jpg.jpeg">
            <div>
                <h4>Jus Buah Naga</h4>
                
            </div>
        </div>
        <div class="menu-item">
            <img src="vila7.jpg.jpeg">
            <div>
                
                <h4>Oreo Milkshake</h4>
            
            </div>
        </div>
    </div>
</section>
<br>
  <a class="btn-wa" 
     href="https://wa.me/082319353964" 
     target="_blank">
     📞 Hubungi via WhatsApp
  </a>
</section>

<footer>
    <p>©  Hana & Ella dessert</p>
</footer>

</body>
</html>
