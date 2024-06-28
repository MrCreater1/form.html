<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form1</title>
</head>
<body>
    <fieldset>
    <h2>Event Registration</h2>
     <label for="name">Name:</label>
     <input type="text" id="name">
     <br>
     <br>
     <label for="email">Email:</label>
     <input type="text" id="email">
     <br>
     <br>
     <label for="ph">Phone:</label>
     <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" required />
     <br>
     <br>
     <label for="">Ocuupation:</label>
     <select>
     <option value="other">Other</option>
     <option value="">other</option>
     </select>
     <br>
     <br>
     <label for="areaofinterest">Topics of Interest</label>
     <br>
    <input type="checkbox" id="checkboxes">
    <label for="checkboxes">HTML</label>
    <br>
    <input type="checkbox" id="checkboxes">
    <label for="checkboxes">CSS</label>
    <br>
    <input type="checkbox" id="checkboxes">
    <label for="checkboxes">JavaScipt</label>
    <br>
    <label for="comment:">Comments:</label>
    <br>
    <textarea name="textarea" id="textarea1" cols="50" rows="10"></textarea>
     <button>Register</button>

    </fieldset>
</body>
</html>
