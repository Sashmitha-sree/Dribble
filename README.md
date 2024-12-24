# Project Responsive Web Design using Bootstrap
## Date:24-12-2024

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
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f4edff;
        }
        .hero-section {
            background-color: #25044f;
            color: rgb(12, 1, 48);
            padding: 80px 0;
        }
        .section-title {
            font-size: 2.5rem;
            margin-bottom: 30px;
        }
        .feature-card {
            background: rgb(238, 226, 255);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .footer {
            background-color: #2d3436;
            color: white;
            padding: 20px 0;
        }
        .footer a {
            color: #dfe6e9;
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Dribbble Clone</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Featured</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Discover</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Sign Up</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<section class="hero-section text-center">
    <div class="container ">
        <h1 style="color: #dfe6e9;" class="display-4">Showcase Your Creative Work</h1>
        <p  style="color: #dfe6e9;" class="lead">Join a community of designers and developers to showcase your projects, get feedback, and collaborate.</p>
        <a href="#" class="btn btn-light btn-lg">Get Started</a>
    </div>
</section>

<section class="container my-5">
    <h2 class="section-title text-center">Featured Work</h2>
    <div class="row">
        <div class="col-md-4 mb-4">
            <div class="feature-card">
                <img src="c:\Users\Sashmitha sree\Pictures\Saved Pictures\New folder\2.jpg" class="img-fluid rounded" alt="Featured Work">
                <h4 class="mt-3">Alice</h4>
                <p>Simple but elegant social media power point template</p>
            </div>
        </div>
        <div class="col-md-4 mb-4">
            <div class="feature-card">
                <img src="c:\Users\Sashmitha sree\Pictures\Saved Pictures\New folder\3.png" class="img-fluid rounded" alt="Featured Work">
                <h4 class="mt-3">Roslan</h4>
                <p>Black and White Template</p>
            </div>
        </div>
        <div class="col-md-4 mb-4">
            <div class="feature-card">
                <img src="c:\Users\Sashmitha sree\Pictures\Saved Pictures\New folder\4.png" class="img-fluid rounded" alt="Featured Work">
                <h4 class="mt-3">Allison</h4>
                <p>Promote your social media smartly</p>
            </div>
        </div>
        <div class="col-md-4 mb-4">
            <div class="feature-card">
                <img src="c:\Users\Sashmitha sree\Pictures\Saved Pictures\New folder\5.png" class="img-fluid rounded" alt="Featured Work">
                <h4 class="mt-3">Nova</h4>
                <p>Simple elegant template mobile app template</p>
            </div>
        </div>
        <div class="col-md-4 mb-4">
            <div class="feature-card">
                <img src="c:\Users\Sashmitha sree\Pictures\Saved Pictures\New folder\6.png" class="img-fluid rounded" alt="Featured Work">
                <h4 class="mt-3">alex reo</h4>
                <p>Instagram puzzle design</p>
            </div>
        </div>
        <div class="col-md-4 mb-4">
            <div class="feature-card">
                <img src="c:\Users\Sashmitha sree\Pictures\Saved Pictures\New folder\8.png" class="img-fluid rounded" alt="Featured Work">
                <h4 class="mt-3">Hannah silver</h4>
                <p>Simplify your finance and secure your future</p>
            </div>
        </div>
    </div>
</section>

<footer class="footer text-center">
    <div class="container">
        <p>Developed by K V Sashmitha sree</p>
        <p>&copy; 2024 Dribbble Clone. All rights reserved.</p>
        
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>

</body>
</html>

```

## OUTPUT:
![Screenshot (73)](https://github.com/user-attachments/assets/e53259e1-1f1e-4872-9b29-de81525a7e29)
![Screenshot (74)](https://github.com/user-attachments/assets/b463ea58-775c-4d5a-b63a-095d5c68464f)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
