# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
NAME:DHARSHINI.R
REF.NO:212224220023
```
pharmacy.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmacy Website</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom CSS can go here */
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">OurPharmacy</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="pharmacy.html">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="ABOUTP.html">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="service.html">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="CONTACTPHA.html">Contact</a>
      </li>
    </ul>
  </div>
</nav>

<!-- Main Content -->
<div class="container mt-4">
  <div class="row">
    <div class="col-md-8">
      <h2>Welcome to OurPharmacy</h2>
      <p>The best and the Most Efficient Pharmacy is Within your computer.</p>
    </div>
    <div class="col-md-4">
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">Opening Hours</h5>
          <p class="card-text">Monday - Friday: 9:00 AM - 6:00 PM</p>
          <p class="card-text">Saturday: 10:00 AM - 4:00 PM</p>
          <p class="card-text">Sunday: Closed</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="bg-dark text-white mt-5 py-4">
  <div class="container text-center">
    <p>&copy; 2024 Pharmacy. All rights reserved.</p><br>
    <p>Developed by DHARSHINI.R (212224220023)</p>
  </div>
</footer>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
```
ABOUTP.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us - OurPharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom CSS for Pharmacy Website */

    /* Navbar */
    .navbar {
      border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    }

    .navbar-brand {
      font-weight: bold;
    }

    /* Main Content */
    .container {
      padding-top: 20px;
    }

    /* Footer */
    footer {
      background-color: #343a40;
      color: #fff;
    }

    /* Responsive styles */
    @media (max-width: 768px) {
      .container {
        padding-top: 60px;
      }
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">OurPharmacy</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="pharmacy.html">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="ABOUTP.html">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="service.html">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="CONTACTPHA.html">Contact</a>
      </li>
    </ul>
  </div>
  <!-- Rest of the navbar code -->
</nav>

<!-- Main Content -->
<div class="container mt-4">
  <!-- About content -->
  <h2>About OurPharmacy</h2>
  <p>Welcome to OurPharmacy, your trusted neighborhood pharmacy dedicated to providing high-quality healthcare services and products. Our team of experienced pharmacists and staff are here to serve you with care and expertise.</p>
  <img src="C:\Users\91755\Pictures\phar.jpg" alt="Pharmacy Image" class="img-fluid mt-4" height="400" width="400">
</div>

<!-- Footer -->
<footer class="bg-dark text-white mt-5 py-4">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h5>Contact Us</h5>
        <p>Address: 123 Pharmacy Street, Cityville, State, ZIP</p>
        <p>Phone: 123-456-7890</p>
        <p>Email: info@ourpharmacy.com</p>
      </div>
      <div class="col-md-6">
        <h5>Follow Us</h5>
        <p>Stay connected with us on social media for updates and health tips.</p>
        <ul class="list-inline">
          <li class="list-inline-item"><a href="#"><img src="C:\Users\91755\Pictures\pharface.jpeg" alt="Facebook" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="C:\Users\91755\Pictures\twitter.png" alt="Twitter" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="C:\Users\91755\Pictures\pa.png" alt="Instagram" height="30" width="30"></a></li>
        </ul>
      </div>
    </div>
  </div>
</footer>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
```
service.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Services - OurPharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom CSS for Pharmacy Website */

    /* Navbar */
    .navbar {
      border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    }

    .navbar-brand {
      font-weight: bold;
    }

    /* Main Content */
    .container {
      padding-top: 20px;
    }

    /* Footer */
    footer {
      background-color: #343a40;
      color: #fff;
    }

    /* Responsive styles */
    @media (max-width: 768px) {
      .container {
        padding-top: 60px;
      }
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">OurPharmacy</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="pharmacy.html">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="ABOUTP.html">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="service.html">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="CONTACTPHA.html">Contact</a>
      </li>
    </ul>
  </div>
  <!-- Rest of the navbar code -->
</nav>

<!-- Main Content -->
<div class="container mt-4">
  <!-- Services content -->
  <h2>Our Services</h2>
  <p>At OurPharmacy, we offer a wide range of services to cater to your healthcare needs:</p>
  <ul>
    <li>Prescription filling and medication counseling</li>
    <li>Over-the-counter medications and health products</li>
    <li>Health screenings and vaccinations</li>
    <li>Medication therapy management</li>
    <li>Home delivery services</li>
    <li>Compounding services</li>
  </ul>
  <!-- Image related to pharmacy services -->
  <img src="C:\Users\91755\Pictures\DEL.jpg" alt="Pharmacy Services" class="img-fluid mt-4" height="250" width="250">
  <img src="C:\Users\91755\Pictures\MEDICATION.webp" alt="Pharmacy Services" class="img-fluid mt-4" height="250" width="250">
  <img src="C:\Users\91755\Pictures\MEDIC.jpg" alt="Pharmacy Services" class="img-fluid mt-4" height="300" width="250">
  <img src="C:\Users\91755\Pictures\Online.jpg" alt="Pharmacy Services" class="img-fluid mt-4" height="300" width="250">
</div>

<!-- Footer -->
<footer class="bg-dark text-white mt-5 py-4">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h5>Contact Us</h5>
        <p>Address: 123 Pharmacy Street, Cityville, State, ZIP</p>
        <p>Phone: 123-456-7890</p>
        <p>Email: info@ourpharmacy.com</p>
      </div>
      <div class="col-md-6">
        <h5>Follow Us</h5>
        <p>Stay connected with us on social media for updates and health tips.</p>
        <ul class="list-inline">
          <li class="list-inline-item"><a href="#"><img src="C:\Users\91755\Pictures\pharface.jpeg" alt="Facebook" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="C:\Users\91755\Pictures\twitter.png" alt="Twitter" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="C:\Users\91755\Pictures\pa.png" alt="Instagram" height="30" width="30"></a></li>
        </ul>
      </div>
    </div>
  </div>
</footer>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
```
CONTACTPH.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - OurPharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom CSS for Pharmacy Website */

    /* Navbar */
    .navbar {
      border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    }

    .navbar-brand {
      font-weight: bold;
    }

    /* Main Content */
    .container {
      padding-top: 20px;
    }

    /* Footer */
    footer {
      background-color: #343a40;
      color: #fff;
    }

    /* Responsive styles */
    @media (max-width: 768px) {
      .container {
        padding-top: 60px;
      }
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="pharmacy.html">OurPharmacy</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="ABOUTP.html">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="service.html">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="CONTACTPHA.html">Contact</a>
      </li>
    </ul>
  </div>
  <!-- Rest of the navbar code -->
</nav>

<!-- Main Content -->
<div class="container mt-4">
  <!-- Contact Form -->
  <h2>Contact Us</h2>
  <p>If you have any questions or inquiries, please feel free to contact us using the form below:</p>
  <form>
    <div class="form-group">
      <label for="name">Name:</label>
      <input type="text" class="form-control" id="name" placeholder="Enter your name">
    </div>
    <div class="form-group">
      <label for="email">Email:</label>
      <input type="email" class="form-control" id="email" placeholder="Enter your email">
    </div>
    <div class="form-group">
      <label for="message">Message:</label>
      <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
</div>

<!-- Footer -->
<footer class="bg-dark text-white mt-5 py-4">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h5>Contact Us</h5>
        <p>Address: 123 Pharmacy Street, Cityville, State, ZIP</p>
        <p>Phone: 123-456-7890</p>
        <p>Email: info@ourpharmacy.com</p>
      </div>
      <div class="col-md-6">
        <h5>Follow Us</h5>
        <p>Stay connected with us on social media for updates and health tips.</p>
        <ul class="list-inline">
          <li class="list-inline-item"><a href="#"><img src="C:\Users\91755\Pictures\pharface.jpeg" alt="Facebook" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="C:\Users\91755\Pictures\twitter.png" alt="Twitter" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="C:\Users\91755\Pictures\pa.png" alt="Instagram" height="30" width="30"></a></li>
        </ul>
      </div>
    </div>
  </div>
  <center>Developed By DHARSHINI.R (212224220023) </center>
</footer>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
```

## OUTPUT:
### pharmacy.html
![Screenshot 2024-12-26 191749](https://github.com/user-attachments/assets/f3494f8d-2b80-475e-84ae-86a83dbc3932)
### ABOUTP.html
![Screenshot 2024-05-11 185119](https://github.com/KSIHORE/Pharma/assets/151484879/51f3cb3f-62a3-4098-a6f1-d86d26c11ec1)
### service.html
![Screenshot 2024-05-11 185139](https://github.com/KSIHORE/Pharma/assets/151484879/774e3029-3da0-4021-8735-e443d697048b)
### contact.html
![Screenshot (48)](https://github.com/user-attachments/assets/c5f34555-554c-467d-be97-741f073e8da2)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
