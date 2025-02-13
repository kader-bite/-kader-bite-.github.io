<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./assets/images/favicon-32x32.png">
  
  <title>Frontend Mentor | Recipe page</title>
<link rel="stylesheet" href="stylesheet.css">
  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
</head>
<body>
<div>
  <div class="container">
  <img src="assets/images/image-omelette.jpeg" >
  </div>
  <h1>Simple Omelette Recipe</h1>
  <p>An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs <br> cooked 
    to perfection, optionally filled with your choice of cheese, vegetables, or meats.
  </p>
  <div class="time">
    <h3>Preparation time</h3>
    <ul>
      <li class="fy"><span>Total:</span> Approximately 10 minutes</li>
      <br>
      <li class="fy"><span>Preparation:</span> 5 minutes </li>
      <br>
      <li class="fy"><span>Cooking:</span> 5 minutes</li>
    </ul>
  </div>
  <h2>  Ingredients</h2>
  <ul>
    <li class="fy">2-3 large eggs</li>
    <br>
    <li class="fy">Salt, to taste</li>
    <br>
    <li class="fy">Pepper, to taste</li>
    <br>
    <li class="fy">1 tablespoon of butter or oil</li>
    <br>
    <li class="fy">Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
    <hr>
    <h2>  Instructions</h2>
    <ol>
      <li class="fy"><span>Beat the eggs:</span> In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. 
        You can add a tablespoon of water or milk for a fluffier texture.
      </li>
      <br>
      <li class="fy"><span>Heat the pan:</span> Place a non-stick frying pan over medium heat and add butter or oil.</li>
      <br>
      <li class="fy"><span>Cook the omelette: </span>Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure 
        the eggs evenly coat the surface.
      </li>
      <br>
      <li class="fy"><span>Add fillings (optional):</span> When the eggs begin to set at the edges but are still slightly runny in the 
        middle, sprinkle your chosen fillings over one half of the omelette.
      </li>
      <br>
      <li class="fy"><span>Fold and serve:</span> As the omelette continues to cook, carefully lift one edge and fold it over the 
        fillings. Let it cook for another minute, then slide it onto a plate.
      </li>
      <br>
      <li class="fy"><span>Enjoy:</span> Serve hot, with additional salt and pepper if needed.</li>
    </ol>
    <hr>
    <h2>Nutrition</h2>
    <p>  The table below shows nutritional values per serving without the additional fillings.</p>
    <table>
      <tr>
        <th class="fy">Calories</th>
        <th class="tb">277cal</th>
      </tr>
      <tr>
        <th class="fy">Carbs</th>
        <th class="tb">0g</th>
      </tr>
      <tr>
        <th class="fy">Protein</th>
        <th class="tb">20g</th>
      </tr>
      <tr>
        <th class="fy">  Fat</th>
        <th class="tb">22g</th>
      </tr>
    </table>
</div>
</body>
</html>


@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&family=Young+Serif&display=swap');
body{
  background-color: hsl(330, 100%, 98%);
}
div{
  width: 75%;
  height: 100%;
  margin-top: 50px;
  margin: auto;
  background-color: white;
  border-radius: 16px;
}
.container{
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 50px;
}
.container img{
  width: 75%;
  height: 75%;
  object-fit: cover;
  border-radius: 16px;
  margin-top: 30px;
}
h1{
  font-family: 'young serif';
  font-weight: 400;
  color:hsl(24, 5%, 18%) ;
  margin-left: 30px;
}
h2{
  font-family: 'young serif';
  font-weight: 400;
  color:hsl(14, 45%, 36%) ;
  margin-left: 30px;
}
h3{
  font-family: 'outfit';
  font-weight: bold;
  color:hsl(332, 51%, 32%) ;
}
p{
  font-size: 16px;
  color: hsl(30, 10%, 34%);
  font-family:'outfit'; 
  margin-left: 30px;
}
.time{
  background-color:hsl(330, 100%, 98%) ;
}
ul li span{
  font-family: 'outfit';
  font-weight: bold;
  color: hsl(30, 10%, 34%) ;
}
table{
  width: 100%;
  border-collapse:collapse ;
  margin-top: 30px;
  margin-bottom: 60px;
  text-align: left;
}
th, td{
border-bottom: 1px solid hsl(30, 18%, 87%);
padding: 10px;
}
.tb{
font-family: 'outfit';
font-size: bold;
color: hsl(14, 45%, 36%);
}
.fy{
  font-size: 16px;
  color: hsl(30, 10%, 34%);
  font-family:'outfit';
}
hr{
  border: 1px solid hsl(30, 18%, 87%);
  margin-top: 20px;
  width: 90%;
}
@media screen and (max-width: 375){
 .container img{
   width: 100%;
   height: 100%;
 }}
