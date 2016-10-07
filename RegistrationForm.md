# COSCProject1
Code for Project1 COSC231
<!doctype html>
<html>
	<head>
		<title>Team Rocket Registration</title>
		<link rel="stylesheet" href="style2.css">
		<script>
		function regComplete() {
			alert('Welcome to the club, ' + document.getElementById('fname').value + ". Your registration has been completed successfully!!" );
		}
		</script>
	</head>
	<body>
	<body>
	<div id="wrapper">
		<header id="main_header">
			<div id="header">Fanclub Registration Form</div>
			<div><img class="logo" src="http://people.emich.edu/abowma21/fall16-231/images/team_rocket_R.png" alt="Team Rocket Logo"></div>
		</header>
		<nav id="main_menu">
			<ul>
				<li><a href="http://people.emich.edu/abowma21/fall16-231/231/TRCHomepage.html">Home</a></li>
				<li><a href="http://people.emich.edu/abowma21/fall16-231/231/about-TR.html">About Local Team Rocket</a></li>
				<li>Rocket History</li>
				<li><a href="http://people.emich.edu/kbledsoe3/Projects/TRRegistration.htmlTeam" >Register for the Club</a></li>
				<li>Site Map</li>
			</ul>
		</nav>
		<section id="main_section">
			
		<form id = "textboxes">
				<h2>Submit the following information to become an official fanclub member.</h2><br/>
				<label>Username:   <input id = "username" type="textbox" name="username" /></label>
				<label>Password:   <input id = "password" type="password" name="password" /></label>
				<label>Email: <input id = "email" type = "textbox" name="email" /></label><br /><br /><br />
				<label>First Name: <input id = "fname" type = "textbox" name="fname" /></label>
				<label>Last Name:  <input id = "lname" type = "textbox" name="lname" /></label>
				<label>Title: <input id = "title" type = "textbox" name="title" /></label>
				<label>DOB: <input id = "dob" type = "date" name="dob" placeholder = "mm/dd/yyyy" /></label><br /><br /><br />
				
				<label>Credit Card #: <input id = "ccn" type = "textbox" name="ccn" placeholder = "xxxx xxxx xxxx xxxx" /></label>
				<label>CSV: <input id = "csv" type = "textbox" name = "csv" /><label>
				<label>Exp Date: <input id = "exp" type = "mm/yyyy" name="exp" placeholder = "mm/yyyy" /></label><br /><br />
		</form>
		<form id = "other">
		<label >Male: <input id="gender" type="radio" name="gender" value ="Male" /></label>
				<label>Female: <input id="gender" type="radio" name="gender" value ="Female" />
				<label>Transgender: <input id="gender" type="radio" name="gender" value ="Transgender" /></label></label><br /><br /><br />
				<img src = "http://cdn.bulbagarden.net/upload/thumb/3/39/Team_Rocket_BW_1.png/320px-Team_Rocket_BW_1.png" 
				alt = "Image of Jessie, James, and Meowth" /><br /><br />
				<label>Team Jessie <input type="checkbox" name="team[0]" value ="jessie" /></label>
				<label>Team James <input type="checkbox" name="team[1]" value ="james" /></label>
				<label>Team Meowth <input type="checkbox" name="team[2]" value ="meowth" /></label><br /><br />
				<button type="button" onclick="regComplete();">Register</button>
				<p>(Image Source <a href = "http://archives.bulbagarden.net/media/upload/3/39/Team_Rocket_BW_1.png" >
				Bulbagarden Archives)</p></a><br />
		</form>
		</section>
		<aside id="main_aside">
			<img class="I0" src="http://people.emich.edu/abowma21/fall16-231/images/Team-Rocket-Join.jpg" alt="Team Rocket Logo">
		</aside>
		<footer id="main_footer">
			Created for EMU COSC231 Project 1
		</footer>
	</div>	
	</body>
</html>
