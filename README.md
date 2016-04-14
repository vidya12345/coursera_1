# coursera_1
assignment 1
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="generator" content="CoffeeCup HTML Editor (www.coffeecup.com)">
    <meta name="dcterms.created" content="Wed, 13 Apr 2016 02:47:00 GMT">
    <meta name="description" content="">
    <meta name="keywords" content="">
    <title></title>
    
    <!--[if IE]>
    <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
	
	<style>
	/*a {font-size:16px;}
	a:hover{font-size:20px }*/
	.face, .general, .indicators, .contact_information {border-color:#4bf616; background-color:#FFFF00 !important;}
	.short{background-color:#a92d4d;
color:white }
.tall{background-color:#bc16f6;
color:white}
	</style>
  </head>
  <body>
  
<a><h2>Please Enter Your Details for Our Dating Website! </h2></a>
<br>
<br>

<fieldset class="face">
<legend><a>Your Face</a></legend>
<a>Your Image: </a> <input type="file" name="imagetoupload"/>
<br>
<a>Image Preview:<a/a>
<br>
</fieldset>
<br>
<br>

<fieldset class="general">
<legend>Your General Details</legend>
<label for="fullname">Name</label>
<input type="text" name="fullname" id="fullname" placeholder="Your full name"/>
<br>
<label for="gender">Gender:</label>
<input type="radio" name="choices" id="choices" value="Male"/>Male
<input type="radio" name="choices" id="choices" value="Female"/> Female
<br>
<label for="age">Age:</label>
<input type="text" name="age" id="age" placeholder="Enter age" required/>
<br>
<label for="birthday">Birthday:</label>
<input type="date" name="birthday" id="birthday" placeholder="Enter Birthday" />
<br>
<label for="color">Your favorite color:</label>
<input type="color" id="color" name="color" />
<br>
<label for="country">Which Country:</label>
<select name=country>
<option value="in"> India</option>
<option value="us"> United States</option>
<option value="cn"> China</option>
<option value="jp"> Japan</option>
</select>
</fieldset>
<br>
<br>

<fieldset class="indicators">
<legend>Your Indicators</legend>
<label for="height">Height:</label>
<mark class="short">Short</mark><input type="range" min="0" max="100" step="5" value="60" name="height" id="height" /><mark class="tall">Tall</mark>
<br>
<label for="salary">Salary:</label>
<mark class="short">Poor</mark><input type="range" min="0" max="100" step="5" value="50" name="salary" id="salary" /><mark class="tall">Rich</mark>
</fieldset>
<br>
<br>
<fieldset class="contact_information">
<legend>Your Contact Information</legend>
<label for="email">Email</label>
<input type="text" name="email" id="email" />
<br>
<label for="mobile">Mobile Number</label>
<input type="number" name="mobile" id="mobile" />
<br>
<label for="address">Address</label>
<input type="text" name="address" id="address" />
<br>
Method to contact you:
<input type="checkbox" name="method" value="Email" />Email
<input type="checkbox" name="method" value="Whatsapp" />Whatsapp
<input type="checkbox" name="method" value="In-app chat" />In-app chat
</fieldset>

  </body>
</html>
