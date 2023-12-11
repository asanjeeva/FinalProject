# Code Sample


Here is how to create a simple form in HTML.

### HTML
```html
<!-- Creating a simple form -->
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- The title of the webpage that appears on the browser tab -->
    <title>Simple Form</title>
</head>
<body>
    <!-- Heading 1 element to display a main heading -->
    <h1>Contact Me</h1>

    <!-- Form element with input fields for name and email -->
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
