# Online-Shopping-Cart
#### Basic idea and Key objective
* ##### Basic idea
	* Providing an **online shopping portal** that help people to purchase products online using their unique id and password which helps them access the website and purchase.
* ##### Key objective
	* This pandemic situation has made people sit in a room of four walls and just gaze at the walls of the room. So the main moto of this project is to overcome this situation with a pleasent website which offers people to see for different goods and get them delivered in days with contact less delivery option.
	* Also many people in this modern world are running busy. This user friendly website allows the user to purchase products by sitting comfortably in home.
	* Users are the backbone of this website. So this website have a separate pane for the users to mention their queries and complaints regarding the websites for the further improvements of the website.
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
		
