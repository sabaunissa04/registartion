# registartion
using html created registration form
<!DOCTYPE html>
<html>
<head>
  <title>Complete Registration Form</title>
</head>
<body>

  <h2>Registration Form</h2>

  <form action="/submit" method="post" enctype="multipart/form-data">
    
    <label for="firstname">First Name:</label><br>
    <input type="text" id="firstname" name="firstname" required><br><br>

    <label for="lastname">Last Name:</label><br>
    <input type="text" id="lastname" name="lastname" required><br><br>

    <label for="username">Username:</label><br>
    <input type="text" id="username" name="username" required><br><br>

    <label for="password">Password:</label><br>
    <input type="password" id="password" name="password" required><br><br>

    <label for="confirmpassword">Confirm Password:</label><br>
    <input type="password" id="confirmpassword" name="confirmpassword" required><br><br>

    <label for="mobile">Mobile Number:</label><br>
    <input type="tel" id="mobile" name="mobile" required><br><br>

    <label for="date">Date:</label><br>
    <input type="date" id="date" name="date" required><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label>Gender:</label><br>
    <input type="radio" id="male" name="gender" value="Male" required>
    <label for="male">Male</label><br>
    <input type="radio" id="female" name="gender" value="Female">
    <label for="female">Female</label><br>
    <input type="radio" id="other" name="gender" value="Other">
    <label for="other">Other</label><br><br>

    <label>Languages Known:</label><br>
    <input type="checkbox" id="english" name="language" value="English">
    <label for="english">English</label><br>
    <input type="checkbox" id="hindi" name="language" value="Hindi">
    <label for="hindi">Hindi</label><br>
    <input type="checkbox" id="telugu" name="language" value="Telugu">
    <label for="telugu">Telugu</label><br><br>

    <label for="city">City:</label><br>
    <input type="text" id="city" name="city" required><br><br>

    <label for="state">State:</label><br>
    <input type="text" id="state" name="state" required><br><br>

    <label for="country">Country:</label><br>
    <input type="text" id="country" name="country" required><br><br>

    <label for="file">Upload File:</label><br>
    <input type="file" id="file" name="file"><br><br>

    <label for="feedback">Feedback:</label><br>
    <textarea id="feedback" name="feedback" rows="4" cols="50"></textarea><br><br>

    <input type="submit" value="Register">

  </form>

</body>
</html>

