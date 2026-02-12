<!DOCTYPE html>
<html>
<head>
<title>Jazz Mart</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{
  margin:0;
  font-family:Arial;
  background:#f4f4f4;
}
header{
  background:#111;
  color:white;
  padding:20px;
  text-align:center;
  font-size:28px;
}
.container{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:20px;
  padding:20px;
}
.card{
  background:white;
  width:200px;
  padding:15px;
  border-radius:10px;
  box-shadow:0 4px 10px rgba(0,0,0,0.1);
  text-align:center;
}
.price{
  color:green;
  font-weight:bold;
}
button{
  background:#111;
  color:white;
  border:none;
  padding:8px;
  margin-top:8px;
  cursor:pointer;
  border-radius:5px;
}
button:hover{
  background:#333;
}
</style>
</head>

<body>

<header>🛒 Jazz Mart</header>

<div class="container">

<div class="card">
<h3>Milk</h3>
<p class="price">₹60</p>
<button>Add to Cart</button>
</div>

<div class="card">
<h3>Fish</h3>
<p class="price">₹400</p>
<button>Add to Cart</button>
</div>

<div class="card">
<h3>Notebook</h3>
<p class="price">₹50</p>
<button>Add to Cart</button>
</div>

<div class="card">
<h3>Pen</h3>
<p class="price">₹20</p>
<button>Add to Cart</button>
</div>

</div>

</body>
</html>
