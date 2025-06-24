<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aman Dhiman | Portfolio Gallery</title>
<link rel="stylesheet"
href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css
">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-
awesome/6.0.0/css/all.min.css">
<style>
body {
scroll-behavior: smooth;
font-family: 'Segoe UI', sans-serif;
background: linear-gradient(to right, #f8f9fa, #e0eafc);
color: #333;
}
.navbar {
background-color: #2c3e50;
}
.navbar-brand, .nav-link {
color: white !important;
}
.nav-link:hover {
color: #f39c12 !important;
}
section {
padding: 80px 0;
}
#about {
background-color: #ffffff;
text-align: center;
}
#projects {
background-color: #ffffff;
}
#contact {
background-color: #f0f4f8;
}
footer {
background-color: #212121;
color: white;
}
.btn-custom {
background-color: #007bff;
color: white;
border: none;
transition: background-color 0.3s;
}
.btn-custom:hover {
background-color: #0056b3;
}
.project-img {
height: 200px;
object-fit: cover;
}
.card {
box-shadow: 0 4px 20px rgba(0,0,0,0.1);
transition: transform 0.3s ease;
}
.card:hover {
transform: translateY(-10px);
}
.social-icons a {
color: white;
font-size: 20px;
margin: 0 10px;
transition: color 0.3s ease;
}
.social-icons a:hover {
color: #f39c12;
}
.profile-img {
width: 150px;
border-radius: 50%;
margin-bottom: 20px;
}
</style>
</head>
<body data-spy="scroll" data-target="#navbar" data-offset="70">
<nav class="navbar navbar-expand-lg navbar-dark fixed-top">
<a class="navbar-brand" href="#">Aman Dhiman</a>
<button class="navbar-toggler" type="button" data-toggle="collapse" data-
target="#navMenu">
<span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="navMenu">
<ul class="navbar-nav ml-auto">
<li class="nav-item"><a class="nav-link" href="#about">Portfolio</a></li>
<li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
<li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
</ul>
</div>
</nav>
<section id="about">
<div class="container">
<h2 class="mb-4">My Portfolio</h2>
<img src="https://source.unsplash.com/150x150/?developer,person"
alt="Profile" class="profile-img">
<h4 class="mt-3">Aman Dhiman — Front-End Web Developer</h4>
<p class="lead">Welcome to my interactive and motivational portfolio! Each
project here represents a step forward in my journey as a front-end developer,
using HTML, CSS, JavaScript, and Bootstrap. These works reflect a passion for
crafting responsive, user-friendly interfaces that engage and inspire users.</p>
<a href="#projects" class="btn btn-custom mt-3">Explore Projects</a>
<div class="social-icons mt-4">
<a href="https://www.linkedin.com" target="_blank"><i class="fab fa-
linkedin"></i></a>
<a href="https://github.com" target="_blank"><i class="fab fa-
github"></i></a>
<a href="https://instagram.com" target="_blank"><i class="fab fa-
instagram"></i></a>
<a href="https://twitter.com" target="_blank"><i class="fab fa-
twitter"></i></a>
</div>
</div>
</section>
<section id="projects">
<div class="container">
<h2 class="text-center mb-5">Project Gallery</h2>
<div class="row">
<!-- Example project card: repeat and customize for each project -->
<div class="col-md-4 mb-4">
<div class="card">
<img src="https://source.unsplash.com/800x600/?ecommerce"
class="card-img-top project-img" alt="Project 1">
<div class="card-body">
<h5 class="card-title">Project 1: E-Commerce Site</h5>
<p class="card-text">Fully responsive shopping site with product pages,
search filter, and interactive cart.</p>
<a href="projects/project1/index.html" class="btn btn-custom"
target="_blank">View Project</a>
</div>
</div>
</div>
<div class="col-md-4 mb-4">
<div class="card">
<img src="https://source.unsplash.com/800x600/?todo" class="card-img-top
project-img" alt="Project 2">
<div class="card-body">
<h5 class="card-title">Project 2: Task Tracker</h5>
<p class="card-text">A simple to-do list app using localStorage to manage your
daily productivity tasks.</p>
<a href="projects/project2/index.html" class="btn btn-custom"
target="_blank">View Project</a>
</div>
</div>
</div>
<div class="col-md-4 mb-4">
<div class="card">
<img src="https://source.unsplash.com/800x600/?portfolio" class="card-img-
top project-img" alt="Project 3">
<div class="card-body">
<h5 class="card-title">Project 3: Personal Portfolio</h5>
<p class="card-text">Responsive personal website highlighting skills, projects,
and contact information.</p>
<a href="projects/project3/index.html" class="btn btn-custom"
target="_blank">View Project</a>
</div>
</div>
</div>
<div class="col-md-4 mb-4">
<div class="card">
<img src="https://source.unsplash.com/800x600/?weather" class="card-img-
top project-img" alt="Project 4">
<div class="card-body">
<h5 class="card-title">Project 4: Weather App</h5>
<p class="card-text">Real-time weather application fetching data from
OpenWeatherMap API using JS.</p>
<a href="projects/project4/index.html" class="btn btn-custom"
target="_blank">View Project</a>
</div>
</div>
</div>
<div class="col-md-4 mb-4">
<div class="card">
<img src="https://source.unsplash.com/800x600/?blog" class="card-img-top
project-img" alt="Project 5">
<div class="card-body">
<h5 class="card-title">Project 5: Blog Site</h5>
<p class="card-text">A blog content management layout where users can view
and manage blog entries.</p>
<a href="projects/project5/index.html" class="btn btn-custom"
target="_blank">View Project</a>
</div>
</div>
</div>
</div>
</div>
</section>
<section id="contact">
<div class="container">
<h2 class="text-center mb-4">Contact Me</h2>
<form id="contactForm">
<div class="form-group">
<label for="name">Name</label>
<input type="text" class="form-control" id="name" required />
</div>
<div class="form-group">
<label for="email">Email</label>
<input type="email" class="form-control" id="email" required />
</div>
<div class="form-group">
<label for="message">Message</label>
<textarea class="form-control" id="message" rows="4"
required></textarea>
</div>
<button type="submit" class="btn btn-custom">Send Message</button>
<div id="formAlert" class="mt-3 text-success" style="display:
none;">Message sent successfully!</div>
</form>
</div>
</section>
<footer class="text-center py-4">
<p>Connect with me on:</p>
<div class="social-icons">
<a href="https://www.linkedin.com" target="_blank"><i class="fab fa-
linkedin"></i></a>
<a href="https://github.com" target="_blank"><i class="fab fa-
github"></i></a>
<a href="https://instagram.com" target="_blank"><i class="fab fa-
instagram"></i></a>
<a href="https://twitter.com" target="_blank"><i class="fab fa-
twitter"></i></a>
</div>
<p class="mb-0 mt-2">&copy; 2025 Aman Dhiman. All rights reserved.</p>
</footer>
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script
src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.
js"></script>
<script>
$('#contactForm').on('submit', function(e) {
e.preventDefault();
const name = $('#name').val();
const email = $('#email').val();
const message = $('#message').val();
if (name && email && message) {
$('#formAlert').fadeIn();
setTimeout(() => $('#formAlert').fadeOut(), 3000);
$('#contactForm')[0].reset();
}
});
</script>
</body>
</html>
OUTPUT PDF LINK
https://1drv.ms/b/c/97f67e659aaaf5bf/EX8ezIReBR9EksrDIyXTfucBlz-
G3pjgkwkJMA__jTOt9A?e=p9WENn
