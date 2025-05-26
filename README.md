# Module-1-Bootstrap5
<!-- Exercise 1.1 -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bootstrap CDN Setup</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-center">Hello, Bootstrap 5!</h1>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

<!-- Exercise 1.2 -->
<!-- Create a new folder, add Bootstrap's CSS/JS, and link like this: -->
<link rel="stylesheet" href="css/bootstrap.min.css">
<script src="js/bootstrap.bundle.min.js"></script>

<!-- Exercise 2.1 and 2.2 -->
<!-- Include Bootstrap's bundle which contains Popper and Bootstrap JS -->
<script src="js/bootstrap.bundle.min.js"></script>

<!-- Exercise 3.1 and 3.2 -->
<div class="container">
  <div class="row">
    <div class="col-12 col-sm-6 col-lg-4">Column 1</div>
    <div class="col-12 col-sm-6 col-lg-4">Column 2</div>
    <div class="col-12 col-sm-6 col-lg-4">Column 3</div>
  </div>
</div>

<!-- Exercise 4.1 -->
<div class="container">
  <div class="row">
    <div class="col-md-3 bg-light">Sidebar</div>
    <div class="col-md-9">Main Content</div>
  </div>
</div>

<!-- Exercise 4.2 -->
<div class="row">
  <div class="col-sm-3">1</div>
  <div class="col-sm-3">2</div>
  <div class="col-sm-3">3</div>
  <div class="col-sm-3">4</div>
</div>

<!-- Exercise 5.1 -->
<div class="d-flex justify-content-center align-items-center" style="height: 100vh;">
  <p>Centered Content</p>
</div>

<!-- Exercise 5.2 -->
<div class="row">
  <div class="col-md-6 order-md-2">Second</div>
  <div class="col-md-6 order-md-1">First</div>
</div>

<!-- Exercise 6.1 (Flexbox Navbar) -->
<nav class="d-flex flex-column flex-md-row bg-dark p-3">
  <a href="#" class="text-white me-md-3">Home</a>
  <a href="#" class="text-white me-md-3">About</a>
</nav>

<!-- Exercise 6.2 -->
<div class="card d-flex flex-row justify-content-between align-items-center p-3">
  <div>Item 1</div>
  <div>Item 2</div>
</div>

<!-- Exercise 7.1 and 7.2 -->
<div class="container">
  <h1 class="display-1">Heading</h1>
  <p class="lead text-muted fw-bold">Lead paragraph</p>
  <p class="text-uppercase">Uppercase</p>
  <p class="text-lowercase">LOWERCASE</p>
  <p class="text-capitalize">capitalize this sentence</p>
</div>

<!-- Exercise 8.1 -->
<form>
  <div class="mb-3">
    <label for="name" class="form-label">Name</label>
    <input type="text" class="form-control" id="name">
  </div>
  <div class="form-check">
    <input class="form-check-input" type="checkbox" id="check">
    <label class="form-check-label" for="check">Remember me</label>
  </div>
</form>

<!-- Exercise 8.2 -->
<form>
  <div class="form-floating mb-3">
    <input type="email" class="form-control" id="email" placeholder="name@example.com">
    <label for="email">Email address</label>
  </div>
</form>

<!-- Exercise 9.1 -->
<button class="btn btn-primary">Primary</button>
<button class="btn btn-outline-secondary">Secondary</button>

<!-- Exercise 9.2 -->
<div class="btn-group" role="group">
  <input type="checkbox" class="btn-check" id="btncheck1">
  <label class="btn btn-outline-primary" for="btncheck1">Toggle</label>
</div>

<!-- Exercise 10.1 -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Logo</a>
  <div class="collapse navbar-collapse">
    <ul class="navbar-nav">
      <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
    </ul>
    <form class="d-flex ms-auto">
      <input class="form-control" type="search" placeholder="Search">
    </form>
  </div>
</nav>

<!-- Exercise 10.2 -->
<ul class="nav nav-tabs">
  <li class="nav-item">
    <a class="nav-link active" href="#">Tab 1</a>
  </li>
</ul>

<!-- Exercise 11.1 -->
<div class="card" style="width: 18rem;">
  <img src="profile.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Profile</h5>
  </div>
</div>

<!-- Exercise 11.2 -->
<div class="media d-flex">
  <img src="image.jpg" class="me-3" alt="..." style="width:64px;">
  <div class="media-body">
    <h5>Media Heading</h5>
    Content here...
  </div>
</div>

<!-- Exercise 12.1 and 12.2 -->
<div class="container mt-4 p-2">
  <div class="pricing m-3 p-3 bg-light">Basic Plan</div>
</div>

<!-- Exercise 13.1 and 13.2 -->
<div class="bg-primary text-white p-3">Dashboard</div>
<div class="bg-dark bg-gradient text-white p-3">Dark Section</div>

<!-- Exercise 14.1 and 14.2 -->
<div class="d-none d-md-block">Tablet and above only</div>
<div class="d-lg-flex">Large devices and above</div>

<!-- Exercise 15.1 and 15.2 -->
<img src="avatar.jpg" class="border border-primary border-3 rounded-circle">
<div class="card shadow shadow-lg rounded-pill">Card Content</div>

<!-- Exercise 16.1 and 16.2 -->
<footer class="position-fixed bottom-0 bg-dark text-white w-100 text-center p-2">Footer</footer>
<div class="position-relative">
  <img src="product.jpg" alt="Product">
  <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">New</span>
</div>

<!-- Exercise 17.1 and 17.2 -->
<footer>
  <i class="bi bi-facebook"></i>
  <i class="bi bi-twitter"></i>
</footer>
<button class="btn"><i class="bi bi-check"></i></button>

<!-- Exercise 18.1 -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
  Launch Modal
</button>
<div class="modal fade" id="exampleModal" tabindex="-1">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Modal title</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
      </div>
      <div class="modal-body">Modal body</div>
    </div>
  </div>
</div>

<!-- Exercise 18.2 -->
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne">
        Accordion Item
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show">
      <div class="accordion-body">Body Content</div>
    </div>
  </div>
</div>

<!-- Exercise 19.1 and 19.2 -->
<!-- Set up via npm and edit _variables.scss, e.g., -->
$primary: #ff6347;
$border-radius: 1rem;


