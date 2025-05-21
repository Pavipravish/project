# Project Responsive Web Design using Bootstrap
# Date:13/05/2025
# NAME: PRAVISH.J
# REF NO: 212224040249
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Music World</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Music World</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#features">Features</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#Playlist">Playlist</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-dark text-white text-center py-5">
        <div class="container">
            <h1 class="display-4">Welcome to Music World</h1>
            <p class="lead">A responsive home for music lovers,designed for all devices..</p>
            <a href="#features" class="btn btn-primary mt-3">Explore Now</a>
        </div>
    </header>
    <!-- Features Section -->
    <section id="features" class="py-5">
        <div class="container">
            <div class="row text-center">
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="latest.png" class="card-img-top" alt="Latest News">
                        <div class="card-body">
                            <h5 class="card-title">Latest News</h5>
                            <p class="card-text">Stay tuned to the beats that matter,anytime,anywhere.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="review.png" class="card-img-top" alt="Top Reviews">
                        <div class="card-body">
                            <h5 class="card-title">Top Reviews</h5>
                            <p class="card-text">Honest reviews,flawless design-music feedback on every screen</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="community.png" class="card-img-top" alt="Community">
                        <div class="card-body">
                            <h5 class="card-title">Community</h5>
                            <p class="card-text">Join the rhythm of a global music community,anytime,anywhere</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Games Section -->
    <section id="games" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">Top Albums</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="top album.png" class="card-img-top" alt="Game 1">
                        <div class="card-body">
                            <h5 class="card-title">English</h5>
                            <p class="card-text">Explore the soundtracks  of the year,optimized for every device.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="artists.png" class="card-img-top" alt="Game 2">
                        <div class="card-body">
                            <h5 class="card-title">Artists Spotlights</h5>
                            <p class="card-text">Celebrate the creators,beautifully highlighted for every music lovers.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="concert.png" class="card-img-top" alt="Game 3">
                        <div class="card-body">
                            <h5 class="card-title">Upcoming Events</h5>
                            <p class="card-text">Stay in tune with upcoming events,anytime,anywhere</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="4" placeholder="Write your message"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p class="mb-0">&copy; 2024 Music World. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:
![Screenshot (150)](https://github.com/user-attachments/assets/60f5095a-aade-4163-959e-54c8639eb673)
![Screenshot (148)](https://github.com/user-attachments/assets/463c16a8-d323-45c6-8c18-313c90e77024)
![Screenshot (149)](https://github.com/user-attachments/assets/fc8c61be-acd7-4c02-b613-7592e0753ef4)



# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
