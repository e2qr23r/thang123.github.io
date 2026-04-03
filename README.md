<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>SHOP ACC LIÊN QUÂN</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
    color: white;
}

/* Header */
.header {
    background: #000;
    padding: 20px;
    font-size: 28px;
    font-weight: bold;
    color: orange;
    box-shadow: 0 0 10px orange;
}

/* Container */
.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}

/* Card */
.card {
    background: #1e1e1e;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 0 15px rgba(255,165,0,0.3);
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 25px orange;
}

.card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}

.card-content {
    padding: 15px;
}

.price {
    color: orange;
    font-size: 20px;
    font-weight: bold;
}

/* Button */
button {
    width: 100%;
    padding: 10px;
    margin-top: 10px;
    background: orange;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    font-weight: bold;
}

button:hover {
    background: #ff9900;
}
</style>
</head>

<body>

<div class="header">🔥 SHOP ACC LIÊN QUÂN 🔥</div>

<div class="container">

<div class="card">
    <img src="https://via.placeholder.com/300x150">
    <div class="card-content">
        <h3>Acc #001</h3>
        <p>Rank: Cao Thủ</p>
        <p>Tướng: 50+</p>
        <div class="price">200K</div>
        <button onclick="contact()">Mua ngay</button>
    </div>
</div>

<div class="card">
    <img src="https://via.placeholder.com/300x150">
    <div class="card-content">
        <h3>Acc #002</h3>
        <p>Rank: Kim Cương</p>
        <p>Tướng: 30+</p>
        <div class="price">100K</div>
        <button onclick="contact()">Mua ngay</button>
    </div>
</div>

</div>

<script>
function contact() {
    window.open("https://zalo.me/0123456789");
}
</script>

</body>
</html>
