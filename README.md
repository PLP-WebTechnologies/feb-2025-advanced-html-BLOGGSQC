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


ANSWER

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements and Forms</title>
    <link rel="stylesheet" href="styles.css"> <!-- Optional: Link to an external CSS file -->
</head>
<body>
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>

    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
            <li>Fifth Item</li>
        </ol>
    </section>

    <section>
        <h2>External Image</h2>
        <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg" alt="Sample Image" width="600">
    </section>

    <section>
        <h2>Contact Table</h2>
        <table border="1">
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
                    <td>123 Main St, Cityville</td>
                    <td>(123) 456-7890</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St, Townsville</td>
                    <td>(234) 567-8901</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Emily Johnson</td>
                    <td>789 Oak St, Villageburg</td>
                    <td>(345) 678-9012</td>
                    <td>emily@example.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>321 Pine St, Hamlet</td>
                    <td>(456) 789-0123</td>
                    <td>michael@example.com</td>
                </tr>
                <tr>
                    <td>Sarah Davis</td>
                    <td>654 Maple St, Metrocity</td>
                    <td>(567) 890-1234</td>
                    <td>sarah@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>

            <label for="date">Date of Birth:</label>
            <input type="date" id="date" name="date" required>

            <label for="gender">Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label>

            <label for="interests">Interests:</label>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>

            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
                <option value="australia">Australia</option>
            </select>

            <button type="submit">Register</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Advanced HTML5 Elements and Forms</p>
    </footer>
</body>
</html>

