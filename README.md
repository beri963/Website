# MasterPage.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="MasterPage.css">
    
<style>
* {
  box-sizing: border-box;
}

.menu {
  float: left;
  width: 20%;
  text-align: center;
}

.menu a {
  background-color: #e5e5e5;
  padding: 8px;
  margin-top: 7px;
  display: block;
  width: 100%;
  color: black;
}

.main {
  float: left;
  width: 60%;
  padding: 0 20px;
}

.search {
  background-color: #e5e5e5;
  float: left;
  width: 20%;
  padding: 15px;
  margin-top: 7px;
  text-align: center;
}

@media only screen and (max-width: 620px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width: 100%;
  }
}
</style>
</head>
<body style="font-family:Verdana;color:#aaaaaa;">

<div style="background-color:#e5e5e5;padding:15px;text-align:center;">
  <h1>My Pasifika Recipe</h1>
</div>

<div style="overflow:auto">
  <div class="menu">
    <a href="#">Home</a>
    <a href="#">Recipe</a>
    <a href="#">Review</a>
  </div>

  <div class="main">
    <h2>Grace Road Restaurant</h2>
    <p>Is devoted towards preserving the variety of cultural dishes from across the pacific region. This allows to showcase dishes from a variety of cuisines.</p>
  </div>

  <div class="right">
    <h2>Search</h2>
    <p>Most recent items</p>
  </div>
</div>

<div style="background-color:#e5e5e5;text-align:center;padding:10px;margin-top:7px;">© copyright mypasifikarecipe.com</div>

</body>
</html>
