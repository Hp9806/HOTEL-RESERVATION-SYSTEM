# HOTEL-RESERVATION-SYSTEM

# ABSTRACT
This project aims at creating on Hotel Reservation System which can be used by Admin and
Customers. There are a lot of hotel that still use a conventional methods for their reservation
system especially, which can be spent a lot of time for customer to make a reservation room.
So, with that problem, we plan to make a reservation system for hotel using the HTML,CSS,
PHP. The guests can visit the site and register themselves with the required information that
is expected by the system.The system shall take the start and end dates from the user and
check for availability of rooms. It shall check for the number of guests and reserve the rooms
for the user. This application shall enable the user to check for information regarding the
hotel and reserve rooms. Depending on the availability of the rooms the user can book the
room. The user also has an option to update the reservation details. The user can view the
room rates. Also, gallery provides pictures of different type of accommodations. This would
ease the customer to book rooms. He can check for different amenities provided by the
hotel.The user can also know more about the hotel and its address. The Interface is simple
which uses latest web technologies
## PROGRAM
## HOME PAGE:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hotel Reservation</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Tivoli Hotel</h1>
    <nav>
      <a href="#">Home</a> |
      <a href="#">About Us</a> |
      <a href="#">Contact Us</a> |
      <a href="#">Gallery</a> |
      <a href="#">Dine and Lounge</a> |
      <a href="#">Make a Reservation</a>
    </nav>
  </header>
  <main>
    <h2>Make a Reservation</h2>
    <form action="#">
      <div class="form-group">
        <label for="room-type">Room Type:</label>
        <select name="room-type">
          <option value="standard">Standard Room</option>
          <option value="deluxe">Deluxe Room</option>
          <option value="suite">Suite</option>
        </select>
      </div>
      <div class="form-group">
        <label for="check-in">Check-In Date:</label>
        <input type="date" name="check-in">
      </div>
      <div class="form-group">
        <label for="check-out">Check-Out Date:</label>
        <input type="date" name="check-out">
      </div>
      <div class="form-group">
        <label for="first-name">First Name:</label>
        <input type="text" name="first-name">
      </div>
      <div class="form-group">
        <label for="last-name">Last Name:</label>
        <input type="text" name="last-name">
      </div>
      <div class="form-group">
        <label for="email">Email Address:</label>
        <input type="email" name="email">
      </div>
      <div class="form-group">
        <label for="phone-number">Phone Number:</label>
        <input type="tel" name="phone-number">
      </div>
      <div class="form-group">
        <button type="submit">Make Reservation</button>
      </div>
    </form>
  </main>
  <footer>
    <p>Copyright &copy; 2023 Tivoli Hotel</p>
  </footer>
</body>
</html>

~~~
### OUTPUT:
<img width="462" alt="image" src="https://github.com/Hp9806/HOTEL-RESERVATION-SYSTEM/assets/94154621/ae93b869-58ba-4025-9caf-f7b28710f61a">
### RESULT:
Thus we have developed a HOTEL RESERVATION SYSTEM.
