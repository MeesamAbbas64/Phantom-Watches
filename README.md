# Phantom-Watches
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Phantom Watches</title>
  <link rel="stylesheet" href="../CSS/style.css">
  <link rel="stylesheet" href="../CSS/function.css">
  <link rel="stylesheet" href="../CSS/filter.css">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="../CSS/animation.css">
</head>
<body>
  <header>
  <div class="logocontainer">
    <h1 id="logo">phantom watches</h1>
   <div class="dropdown">
    <button onclick="myfunction()" class="dropdown-btn">&#9776;</button>
    <div id="option-dp" class="navigation">
      <a href="/index.html">Home</a>
      <a href="/reviews.html">Reviews</a>
      <a href="/Contact.html">Contact Us</a>
      <a href="/About.html">About</a>
    </div>
   </div>
  </div>
  <form class="search-bar">
    <input type="text" id="search-bar" placeholder="Search Here...">
    <button id="search-button"><i class="fa-solid fa-magnifying-glass"></i></button>
  </form>
  </header>
  <br> 
  <hr>
  </section>
  <section class="types">
    <div id="Filter">Filter By:</div>
     <span class="gender">
       <form action="/index.html" method="get">
        <div class="labels">Gender</div>
        <input type="radio" name="gender" class="style-type" id="men">
        <label for="men" class="filter-types">
         Men
        </label>
         <br>
         <input type="radio" name="gender" class="style-type" id="women">
        <label for="women" class="filter-types">
         Women
        </label>
       </form>
     </span>
     <hr>
     <span class="style">
       <form action="/action.php">
         <div class="labels">Collection</div>
         <input type="radio" name="style" class="style-type" id="casual">
         <label for="casual" class="filter-types">
           Casual
         </label>
         <br>
         <input type="radio" name="style" class="style-type" id="timeless-classics">
         <label for="timeless-classics" class="filter-types" >
           Timeless-Classics
         </label>
         <br>
         <input type="radio" name="style" class="style-type" id="prestigious">
         <label for="prestigious" class="filter-types">
           The Prestigious
         </label>
         <br>
         <input type="radio" name="style" class="style-type" id="vintage-collection">
         <label for="vintage-collection" class="filter-types">
           vintage-Collection
         </label>
         <br>
         <input type="radio" name="style" class="style-type" id="future-classic">
         <label for="future-classic" class="filter-types" >
           future-classics
         </label>
       </form>
     </span>
     <hr>
     <button  onclick="applyfunction()" id="filter-button">Apply</button>
   </section>
  <section class="section1">
    <div class="watches" data-gender="men" data-style="timeless-classics">
      <img src="/1_HTML/silver watch.webp" alt="Moonlight-Rock" class="img-watch">
      <p class="p-watch">A chained watch that has the shine of a moon. Silver color that enhances any dress.</p>
      <p class="oprice">PKR:- 6,999</p>
      <p class="rprice">PKR:- 5,499</p>
    </div>
    <div class="watches" data-gender="women" data-style="future-classics">
      <img src="/1_HTML/blue watch 2nd.jpg" alt="Electric-Dragon" class="img-watch">
      <p class="p-watch">An elegant timepiece that shows the beauty of its owner. People marvel at its beauty.</p>
      <p class="oprice">PKR:- 9,999</p>
      <p class="rprice">PKR:- 7,999</p>
    </div>
  </section>
  <br>
  <br>
  <div id="loader"></div>
  <script src="../JS/funtion.js"></script>
  <script src="https://kit.fontawesome.com/8e1296e27d.js" crossorigin="anonymous"></script>
</body>
</html>
