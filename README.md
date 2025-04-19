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
  <style>
    *{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    font-family: arial, Verdana, Geneva, Tahoma, sans-serif;
}
body{
    background-color: #F1EFEC;
}
.header{
    background-color: #030303;
    height: 175px;
    width: auto;
    display: block;
}
#logo{
    text-transform: capitalize;
    text-align: center;
    color: #ffffff; 
    font-size: 85px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS',sans-serif;
}
.dropdown-btn {
    position: relative;
    left: 15px;
    top: 4px;
    background-color: transparent;
    color: whitesmoke; 
    padding: 13px 13px 13px 13px;
    font-size: 30px;
    border-radius: 10px;
    font-weight: 600;
    border: none;
    cursor: pointer;
} 
.dropdown {
    position: relative;
    display: inline-block;
} 
.navigation {
    display: none;
    top: 0;
    position: absolute;
    top: 61px;
    background-color: #F9F9F9; 
    min-width: 160px;
    overflow: auto;
    box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
    z-index: 1;
}
.navigation a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}
.search-bar {
    display: flex;
    flex-direction: row;
    background-color: #ffffff; 
    border: 1.5px solid #ccc; 
    padding: 0 10px;
    border-radius: 18px;
    margin-top: 15px;
    width: 400px;
    height: 40px;
    overflow: hidden;
    position: sticky;
    left: 500px;
    top: 0;
    z-index: 100;
} 
#search-bar {
    flex-grow: 2;
    border: none; 
    background-color: #ffffff; 
    padding-left: 10px;
    outline: none;
    font-size: 14px;
} 
#search-button {
    background-color: #f2f2f2;  
    font-size: 18px;
    padding: 0 15px;
    border: none;
    border-left: 1px solid #ccc; 
    cursor: pointer;
}
.section1{
    background-color: #F1EFEC; 
    display: inline-block;
    position: relative;
    top: 20px;
    left: 30px;
}
.watches{
    width: 200px;
    display: inline-block;
    margin-left: 30px;
    margin-top: 34px;
    border: 2px solid #A8A8A8; 
    box-shadow: 5px 4px 2px rgba(168,168,168,0.6); 
}
.p-watch{
    height: 70px;
    line-height: 1.26em;
    text-transform: capitalize;
    font-family: Arial, Helvetica, sans-serif;
    overflow-y: scroll;
}
.img-watch{
    height: 140px;
    width: 100%;
}
.oprice{
    font-family: Roboto, 'Open Sans', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;
    font-size: 1.25em;
    font-weight: 600;
    text-decoration: underline rgb(10, 9, 10);
    text-underline-offset: -0.38em;
    text-decoration-skip-ink: none;
    text-decoration-thickness: 0.1em;
    color: rgba(39, 39, 39, 0.7); 
}
.rprice{
    font-family: Roboto, 'Open Sans', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;
    font-size: 1.25em;
    font-weight: 600;
}
  </style>
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
