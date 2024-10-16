<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
<style>
.login{
  border: 3px solid yellow;
  max-width: max-content;
  padding: 20px 30px;
  margin: 10px auto;
}
input[type=button], input[type=submit], input[type=reset]{
  display: block;
  background-color: blanchedalmond;
  margin: 10px auto;
  padding: 5px 15px;
}
</style>
</head>
<body>
<div class="login">
<form>
  <!-- Email input -->
  <label for="email">Enter your Email:</label>
  <input type="email" name="email" id="email" required />
  <br/>
  
  <!-- Password input -->
  <label for="password">Enter your Password:</label>
  <input type="password" name="password" id="password" required />
  <br/>
  
  <!-- Radio button -->
  <label>Choose your gender:</label>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label>
  <br/>
  
  <!-- Checkbox -->
  <input type="checkbox" id="terms" name="terms">
  <label for="terms">I agree to the terms and conditions</label>
  <br/>
  
  <!-- Dropdown list (Select) -->
  <label for="country">Select your country:</label>
  <select id="country" name="country">
    <option value="us">United States</option>
    <option value="ca">Canada</option>
    <option value="uk">United Kingdom</option>
  </select>
  <br/>
  
  <!-- Datalist (alternative for a dropdown) -->
  <label for="browser">Choose your browser:</label>
  <input list="browsers" id="browser" name="browser">
  <datalist id="browsers">
    <option value="Chrome">
    <option value="Firefox">
    <option value="Safari">
    <option value="Edge">
  </datalist>
  <br/>
  
  <!-- List Box -->
  <label for="colors">Select your favorite colors:</label>
  <select id="colors" name="colors" size="3" multiple>
    <option value="red">Red</option>
    <option value="green">Green</option>
    <option value="blue">Blue</option>
    <option value="yellow">Yellow</option>
  </select>
  <br/>
  
  <!-- Search field -->
  <label for="search">Search here:</label>
  <input type="search" id="search" name="search">
  <br/>
  
  <!-- URL input -->
  <label for="website">Your Website:</label>
  <input type="url" id="website" name="website">
  <br/>

  <!-- Buttons -->
  <input type="submit" value="Submit">
  <input type="reset" value="Reset">
  <input type="button" value="LOGIN">
</form>
</div>
</body>
</html>
# FORMMS
