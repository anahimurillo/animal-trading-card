# animal-trading-card
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Animal Trading Cards</title>
</head>
<body>
	<div>
		<h3>Honey Badger</h3>
		<!-- your favorite animal's image goes here -->
		<img src="" alt="Honey Badger">
		<div>
			<!-- your favorite animal's interesting fact goes here -->
			<p>
				The teeth of a Honey Badger are strong enough to break the shell of a tortoise.
			</p>
			<ul>
				<!-- your favorite animal's list items go here -->
				<li><span>Scientific Name</span>: Mellivora capensis</li>
				<li><span>Diet</span>: Anything and everything including,
					but not limited to poisonous snakes, honeybee hives, isects and other animals.</li>
				<li><span>Traits</span>: Thick-skinned, strong teeth, long claws.</li>
				<li><span>Habitat</span>: Honey Badgers can be found in dry areas forest, and grasslands.</li>
			</ul>
			<!-- your favorite animal's description goes here -->
			<p>
				Honey Badgers are fearless solitary animals that have a high
				metabolism and that is why they practically eat all day long.
			</p>
		</div>
	</div>
</body>
</html>

body{
  margin: 10px;
  padding: 10px;
  min-width:300px;
}

img{
  max-width:100%;
  width: 100%;
  height:auto;
}

h3{
  margin-top:0;
}

ul{
  list-style-type: none;
  padding:0;
}

.intro{
  font-size: 1em;
  font-style: italic;
}

.animal-card{
  font-family: serif;
  font-size: .9em;
  margin: 0 auto;
  padding: 20px;
  outline 1px solid blue;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.4);
  max-width: 300px;
}

.facts-outlined{
  margin-top: 10px;
  outline: 1px solid blue;
  max-width: 300px;
  padding:14px;
}

.strong{
  font-weight: bold;
}

