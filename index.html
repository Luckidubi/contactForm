<?php
	
	$error = ""; $successMessage = "";
if (isset($_POST["submit"])) {
	
	if ($_POST["email"] && !filter_var($_POST["email"], FILTER_VALIDATE_EMAIL)) {
  $error .= "Invalid email format<br>"; 
}
	if(empty($_POST["email"])) {
		$error.= "Email address is required<br>";
	}

	if(empty($_POST["subject"])) {
		$error.= "Email subject is required<br>";
	}

	if(empty($_POST["message"])) {
		$error.= "Your message is required<br>";
	}

	if($error != ""){
		$error = "<div class='alert alert-danger alert-dismissible fade show' role='alert'><strong>There are some errors in the fields below:</strong><br><button type='button' class='close' data-dismiss='alert' aria-label='Close'><span aria-hidden='true'>&times;</span></button>".$error."</div>";
	} else {
		$emailTo = "admin@mydomain.com";
		$subject = $_POST["subject"];
		$message = $_POST["message"];
		$headers = "From: ".$_POST["email"];
		if(mail($emailTo, $subject, $message, $headers)){
			$successMessage = "<div class='alert alert-success alert-dismissible fade show' role='alert'><strong>There are some errors in the fields below:</strong><br><button type='button' class='close' data-dismiss='alert' aria-label='Close'><span aria-hidden='true'>&times;</span></button>Email Sent Successfully</div>";
		} else {
			$error = "<div class='alert alert-danger alert-dismissible fade show' role='alert'><strong>Email Not Sent</strong><br><button type='button' class='close' data-dismiss='alert' aria-label='Close'><span aria-hidden='true'>&times;</span></button></div>";
		}
	}
}

?>
<!DOCTYPE html>
<html>
	<head>
	    <title></title>

	    <meta charset="utf-8" />
	    <meta http-equiv="Content-type" content="text/html; charset=utf-8" />
	    <meta name="viewport" content="width=device-width, initial-scale=1" />
	    <link rel="stylesheet" type="text/css" href="include/bootstrap.min.css">
	      
	</head>

	<body>
		<div class="container">
			<div class="error"><?= $error?></div>
			<h1>Get in Touch</h1>
			<form method="POST">
			  <div class="form-group">
			    <label>Email address</label>
			    <input type="email" class="form-control" id="email" name="email" aria-describedby="emailHelp" placeholder="Enter email" value="<?= $_POST["email"]?>">
			    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
			  </div>

			  <div class="form-group">
			    <label>Subject</label>
			    <input type="text" class="form-control" name="subject" id="subject" aria-describedby="subjectHelp" placeholder="Enter Subject" value="<?= $_POST["subject"]?>">
			</div>
			  <div class="form-group">
			    <label>Tell Us What's On Your Mind</label>
			    <textarea class="form-control" name="message" id="message" rows="5"><?= $_POST["message"]?></textarea>
			  </div>
			  
			  <input type="submit" name="submit" value ="submit" class="btn btn-primary">
			</form>
		</div>
		

			<script src="include/jquery.min.js"></script>
			<script src="include/bootstrap.min.js"></script>

			<script>
				$("form").submit(function(){
					var error = "";
					if ($("#email").val() == ""){
						error += "Email is missing<br>";
					}
					if ($("#subject").val() == ""){
						error += "Email subject is missing<br>";
					}
					if ($("#message").val() == ""){
						error += "Enter a message you will send us<br>";
					}

					if(error != ""){

						$(".error").html("<div class='alert alert-danger alert-dismissible fade show' role='alert'><strong>There are some errors in the fields below:</strong><br><button type='button' class='close' data-dismiss='alert' aria-label='Close'><span aria-hidden='true'>&times;</span></button>" + error + "</div>");
						return false;
					} else{
						return true;
					}

				})
			</script>
	</body>
</html>