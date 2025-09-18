<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HTML5 Form Enhancements</title>
</head>
<body>

  <h2>Registration Form</h2>
  <form>
    <!-- Autofocus and placeholder -->
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name" autofocus required><br><br>

    <!-- Required email field -->
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="you@example.com" required><br><br>

    <!-- Pattern validation for phone number -->
    <label for="phone">Phone:</label>
    <input type="text" id="phone" name="phone" placeholder="10-digit number" pattern="\d{10}" required><br><br>

    <input type="submit" value="Submit">
  </form>

</body>
</html>
