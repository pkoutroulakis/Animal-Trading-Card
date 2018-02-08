# Animal-Trading-Card
Grow with Google Lesson 08
<!DOCTYPE html>
<html>
<head>

    <meta charset="utf-8">
    <title>Animal Trading Cards</title>
    <link  type="text/css" rel="stylesheet" href="...fend-animal-trading-cards-master\styles.css" />
</head>
<body>
	<div id="card">
		<!-- your favorite animal's name goes here -->
		<h3>House-Elf</h3>
		<!-- your favorite animal's image goes here -->
		<img src="http://www.maskerix.com/wp-content/uploads/2017/04/diy-harry-potter-dobby-halloween-costume-idea-5.jpg" id="myimage" alt="Dobby smiles when he becomes a free elf">
         <div id="content">
			<!-- your favorite animal's interesting fact goes here -->
			<p class="facts">Dobby is a male house-elf who served the Malfoy family.</p>
			<ul class="list">
				<!-- your favorite animal's list items go here -->
				<li><span>Scientific Name</span>: House-Elf</li>
				<li><span>Average Length</span>: up to 36 inches tall</li>
				<li><span>Average Lifespan</span>: 200 years</li>
				<li><span>Habitat</span>: Highlands of Scotland</li>
			</ul>
			<!-- your favorite animal's description goes here -->
			<p class="description">House-Elves appear to have large heads, long noses and fingers, very short, 
                 with bulging, tennis ball eyes and bat-like ears. They have their 
                 own type of magic performed without a wand which includes the ability 
                 to apparate, disarm and make objects levitate. They are bound to serve
                 one owner unless freed by being given clothes by that owner.</p>
		</div>
	</div>
</body>
</html>

 body     {
               margin: auto;
               
               border-radius: 7px;
               background: #fff;
               width: 330px;
               
               border-style: solid;
               
              }
     #card    {
               padding-top: 4px;
               
               margin: auto;
               border-radius: 6px;
               background: #F0E68C;
               width: 310px;
               
              }
     h3      {
               
               
              
              font-size:30px;
              text-align: center;
              border-style: solid;
              }
     #myimage {
              width: 300px;
              height:335.141px 
              margin: auto;
              
              border-radius: 6px;
              background: #000;
              border-style: solid;
              }
     #content {
              margin: auto;
             padding-bottom: 2px;
             padding-top: 2px;
              border-radius: 7px;
              background: #F0E68C;
              width: 300px;
              
              text-align: left; 
              
              }
     .facts  {
             font-style: italic;
             
             }
     ul     {
              list-style: none;
             }
     span  {
            font-weight: bold;
            }
     .description {
             background: #FFD700;
             border-style: double;
             border-width: 1px;
             border-color: green;
             font-size:12px;
            }
   
