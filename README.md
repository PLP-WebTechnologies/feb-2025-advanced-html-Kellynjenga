# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia Webpage</title>
</head>
<body>
    <ol type="I">
        <li>Power</li>
        <li>Learnig</li>
        <li>Project</li>
    </ol>
    <img src="https://images.pexels.com/photos/31181927/pexels-photo-31181927/free-photo-of-charming-rainy-tokyo-laneway-with-greenery.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load" alt="A road in tokyo">
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>Nairobi</td>
            <td>0765345231</td>
            <td>johndoe@gmail.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>Nakuru</td>
            <td>0789675453</td>
            <td>johnsmith@gmail.com</td>
        </tr>
        <tr>
            <td>Paul Maina</td>
            <td>Naivasha</td>
            <td>0798786453</td>
            <td>johnmaina@gmail.com</td>
        </tr>
        <tr>
            <td>Mary Lee</td>
            <td>Mombasa</td>
            <td>0765467098</td>
            <td>marylee@gmail.com</td>
        </tr>
        <tr>
            <td>Kelly Njenga</td>
            <td>Nairobi</td>
            <td>0709879412</td>
            <td>kellynjenga@gmail.com</td>
        </tr>

    </table>
    <h2>Register Here</h2>
    <form>
        <!-- Name Field -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>
        
        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>
        
        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter a secure password" minlength="6" required>
        <br><br>
        
        <!-- Date Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>
        
        <!-- Dropdown -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="kenya">Kenya</option>
            <option value="uganda">Uganda</option>
            <option value="tanzania">Tanzania</option>
        </select>
        <br><br>
        
        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other" required>
        <label for="other">Other</label>
        <br><br>
        
        <!-- Checkboxes -->
        <label>Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <input type="checkbox" id="tech" name="interests" value="tech">
        <label for="tech">Technology</label>
        <br><br>
        
        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>
    
</body>
</html>
