<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>How to send data from an HTML form to email</title>

	<!-- custom css style link -->
	<link rel="stylesheet" href="style.css">
	<!-- font link -->
	<link href="https://googleapis.com/css?famali=Nunito" rel="stylesheet" type="text/css">
</head>

<body>

<!-- contacts section start -->

<section class="contacts">

	<h2 class="heading"><span>Contact</span>Us</h2>

	<div class="row"> 
		<div class="img">
		   <img src="1.png">	
		</div>

		<form action="https://api.web3forms.com/submit" method="POST">

			<input type="hidden" name="access_key" value="d3760a67-b5ff-4b41-a241-393dde56386b">
			
			<span>Your name</span>
			<input type="text" name="name" id="" class="box" required placeholder="Enter your name.." autocomplete="off">

			<span>Your email</span>
			<input type="email" name="email" id="" class="box" required placeholder="Enter your email.." autocomplete="off">

			<span>Your number</span>
			<input type="number" name="number" id="" class="box" required placeholder="Enter your number.." autocomplete="off">

			<span>Select cources</span>
			<select name="courses" id="" class="box" required>
				<option value="" disabled selected>Select cources</option>
				<option value="HTML">HTML</option>
				<option value="CSS">CSS</option>
				<option value="JavaScript">JavaScript</option>
				<option value="PHP">PHP</option>
				<option value="Python">Python</option>
			</select>

			<span>Select gender</span>
			<div class="gender">
				<input type="radio" name="gender" id="male" value="male">
				<label for="male">male</label>

				<input type="radio" name="gender" id="male" value="male">
				<label for="male">female</label>
			</div>

			<input type="submit" value="Send data" class="btn" name="send" style="height: 30px; width: 100px; border-radius: 7px;">
 
		</form>

	</div>

</section>

<!-- contacts section end -->

</body>
</html>