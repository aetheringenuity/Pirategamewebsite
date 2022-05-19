# Pirategamewebsite
A project for my class where I am making a website for my Skulls and shackles game
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.parallax {
  background-image: url("https://media4.giphy.com/media/PR5vbMZ6zDaR9EugXY/giphy.gif?cid=ecf05e47s8h8pdkfq91l0fy34af6n89mk3zv3bwzmborzd9k&rid=giphy.gif&ct=g");
  min-height:1000px; 
  background-attachment: fixed;
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;
  border: 30px solid black
}
a {
    color: whitesmoke;
}
ul {
      padding: 10px;
      background: rgba(255, 235, 205, 0.438);
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
</style>
</head>
<body>

<div class="parallax"></div>

<div style="height:1000px;background-color:rgba(22, 48, 73, 0.932); text-align: center; font-size: larger; color:aliceblue; border: 30px solid black">
<h1>The Black Blade Pirates</h1>
<ul>
    <li><a href="#">The Crew Bios</a></li>
    <li><a href="#">The Siren's Song</a></li>
    <li><a href="#">The Players</a></li>
  </ul>

<h2>The Crew</h2>
<p>The crew of the Siren's Call, also known as the Black Blade Pirates, are led by six pirates who act as the leading officers of the ship. These six are Captain Maereck the Black Blade, 
    Shimmer of Oil Beneath the Water, Killick the Rogue Wizard, Leofwine Shadesbrother and his shadow snake, Granthem, Reika Seilman the Sea Touched, and Smoggy the Illbringer. The rest of 
    the crew consist of people they had been press ganged with and members of Scourge's crew he left for dead, that they saved, as well as any who wish to join them and, of course, the ship's cat.
</p>
<button>Join the Black Blades</button>
<h3>The Growing Legend</h3>
<p>Though our heros are still new to being and having their own crew, they have already come across and defeated many dangerous foes as well as willingly made much more dangerous ones. With 
    their infamy on the rise, will our heros become a power of good out on the seas or will they become the most cut throat evil to have ever passed over the oceans?
    </p>
    
   <iframe width="560" height="315" src="https://www.youtube.com/embed/tPLodwT58nE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</div>
<script>
    $("button").on("click", function() {
      alert("You have joined the Black Blade Pirate Crew!");
    });
  </script>
</body>
</html>
