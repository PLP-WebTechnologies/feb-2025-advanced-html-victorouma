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
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Top 5 Programming Languages</h2>
    <ol type="I">
        <li>JavaScript</li>
        <li>Python</li>
        <li>Java</li>
        <li>C#</li>
        <li>PHP</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Nature Image</h2>
    <img src="https://images.pexels.com/photos/268533/pexels-photo-268533.jpeg" 
         alt="Beautiful nature scene" 
         width="500"
         title="Photo from Pexels">

    <!-- Contacts Table -->
    <h2>Contact List</h2>
    <table border="1" cellpadding="8">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Doe</td>
                <td>123 Main St, Anytown</td>
                <td>555-123-4567</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Ave, Somewhere</td>
                <td>555-987-6543</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Bob Johnson</td>
                <td>789 Pine Rd, Nowhere</td>
                <td>555-456-7890</td>
                <td>bob@example.com</td>
            </tr>
            <tr>
                <td>Alice Brown</td>
                <td>321 Elm Blvd, Anywhere</td>
                <td>555-789-0123</td>
                <td>alice@example.com</td>
            </tr>
            <tr>
                <td>Charlie Wilson</td>
                <td>654 Maple Ln, Everywhere</td>
                <td>555-234-5678</td>
                <td>charlie@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="/submit" method="post">
        <!-- Name Field -->
        <div>
            <label for="name">Full Name:</label><br>
            <input type="text" id="name" name="name" 
                   placeholder="Enter your full name" 
                   required minlength="3">
        </div><br>

        <!-- Email Field -->
        <div>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" 
                   placeholder="Enter your email" 
                   required>
        </div><br>

        <!-- Password Field -->
        <div>
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" 
                   placeholder="Create a password" 
                   required minlength="8">
        </div><br>

        <!-- Date Field -->
        <div>
            <label for="birthdate">Date of Birth:</label><br>
            <input type="date" id="birthdate" name="birthdate" 
                   required>
        </div><br>

        <!-- Dropdown Menu -->
        <div>
            <label for="country">Country:</label><br>
            <select id="country" name="country" required>
                <option value="" disabled selected>Select your country</option>
                <option value="us">United States</option>
                <option value="ca">Canada</option>
                <option value="uk">United Kingdom</option>
                <option value="au">Australia</option>
                <option value="other">Other</option>
            </select>
        </div><br>

        <!-- Radio Buttons -->
        <div>
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label><br>
            
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label>
        </div><br>

        <!-- Checkboxes -->
        <div>
            <label>Interests (select all that apply):</label><br>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label><br>
            
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br>
            
            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label><br>
            
            <input type="checkbox" id="travel" name="interests" value="travel">
            <label for="travel">Travel</label>
        </div><br>

        <!-- Terms and Conditions -->
        <div>
            <input type="checkbox" id="terms" name="terms" required>
            <label for="terms">I agree to the terms and conditions</label>
        </div><br>

        <!-- Submit Button -->
        <div>
            <input type="submit" value="Register">
        </div>
    </form>
</body>
</html>

Happy Coding! 💻✨
