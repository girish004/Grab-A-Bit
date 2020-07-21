# Shopping Cart
#### Basic idea and Key objective
* ##### Basic idea
	* To provide an **online shopping portal** to help people purchase products online using their unique ID and password which will helps them access the website and purchase the desired product.
* ##### Key objective
	* This pandemic has made everyone all around the world sit in a room with four walls, just gazing at the walls and everyone is itching to shop. So the main moto of this project is to create a website which offers people to purchase different items and get them delivered in days with no-contact delivery option.
	* Plus, many are running busy in today's modern world. This user friendly website allows the user to purchase products by sitting comfortably at home.
	* Users are the backbone of this website. To ensure their satisfaction the website provides a separate panel for the users to mention their queries and complaints regarding the websites for the further improvements of the website.
# Tools and Programming languges used
#### Front end
* #### *Hyper Text Mark-up Language(HTML)*
	* This front-end client side language has so many attributes that makes a website
	* This describes the structure of a Web page
	* It consists of a series of elements
	* It's elements tell the browser how to display the content
* #### *Cascading Style Sheets and Java Script(CSS AND JS)*
	* HTML supports CSS and Java Script which makes the page look beautiful and colorful.
	* CSS plays a major role in attracting the user of the website.
	* Java Script helps the eveloper in spliting the codes into modules and using the code elsewher in the website.
* #### *Hypertext Preprocessor(PHP)*
	* Php is the best server side language which always runs on the host server.
	* Php is Object oriented language and can be used along with html.
#### Back-end
* *Mysqli*
	* This helps us collect the information of the users their id and password and store them in one place
#### Gist of the possible codes that can be used
### Connecting the sql and Html page
	<?php
	$servername = "localhost";// local host along with port number
	$username = "username";// username of your mysqli
	$password = "password";// password for the user of mysqli

	// Create connection
	$conn = new mysqli($servername, $username, $password);//oject oriented declaration
	
	// Check connection
	if ($conn->connect_error) {// Boolean value
 	die("Connection failed: " . $conn->connect_error);
	}
	echo "Connected successfully";
	?>
Saving the above mentioned code in a php file can help us use the code whenever needed
### Main structure of the code for login page(Without any styles)
	<html>
		<body>
		<form>
			ID:<input type="text" name="id"><br>
			Password:<input type="password" name="password"><br>
			<input type="submit" name="login">
		</form>
		</body>
	</html>
### Sample code to store the data in sql
	$sql="insert into table_name values('name','password')
# Result 
This project will result in building a webiste which allows all kind of people to access it and shop online.
This website could benifit everyone in the globe to shop online and get the goods with no contact delivery during ths pandemic.
		
