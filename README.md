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
- <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Airline Management System</title>
</head>
<body>
  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>Roman Numeral List</h2>
    <ol type="I">
      <li>Flight Schedule</li>
      <li>Booking</li>
      <li>Check-in</li>
      <li>Boarding</li>
      <li>Departure</li>
    </ol>
  </section>

  <!-- External Image from Pexels -->
  <section>
    <h2>Airline Image</h2>
    <img src="https://images.pexels.com/photos/358319/pexels-photo-358319.jpeg" alt="Airplane" width="500">
  </section>

  <!-- Table of Contacts -->
  <section>
    <h2>Contact List</h2>
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
          <td>Alice Johnson</td>
          <td>123 Sky Lane</td>
          <td>555-1234</td>
          <td>alice@example.com</td>
        </tr>
        <tr>
          <td>Bob Smith</td>
          <td>456 Cloud Ave</td>
          <td>555-5678</td>
          <td>bob@example.com</td>
        </tr>
        <tr>
          <td>Carol Lee</td>
          <td>789 Jet Way</td>
          <td>555-8765</td>
          <td>carol@example.com</td>
        </tr>
        <tr>
          <td>David Kim</td>
          <td>101 Fly St</td>
          <td>555-4321</td>
          <td>david@example.com</td>
        </tr>
        <tr>
          <td>Eva Brown</td>
          <td>202 Runway Blvd</td>
          <td>555-6789</td>
          <td>eva@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>Passenger Registration</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required><br><br>

      <label for="destination">Destination:</label>
      <select id="destination" name="destination" required>
        <option value="">--Select Destination--</option>
        <option value="nairobi">Nairobi</option>
        <option value="mombasa">Mombasa</option>
        <option value="kisumu">Kisumu</option>
      </select><br><br>

      <p>Gender:</p>
      <input type="radio" id="male" name="gender" value="male" required>
      <label for="male">Male</label><br>
      <input type="radio" id="female" name="gender" value="female">
      <label for="female">Female</label><br>

      <p>Preferences:</p>
      <input type="checkbox" id="window" name="preference" value="window">
      <label for="window">Window Seat</label><br>
      <input type="checkbox" id="meal" name="preference" value="meal">
      <label for="meal">Special Meal</label><br><br>

      <input type="submit" value="Register">
    </form>
  </section>
</body>
</html>


Happy Coding! 💻✨
