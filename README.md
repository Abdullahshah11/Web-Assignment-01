<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UET Mardan | Student Activities Portal</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
          rel="stylesheet">

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f8fc;
            color: #243247;
        }

        .navbar {
            background-color: #073b2b;
        }

        .navbar-brand, .nav-link {
            color: white !important;
        }

        .nav-link:hover {
            color: #f8d568 !important;
        }

        .hero {
            background: linear-gradient(135deg, #073b2b, #167653);
            color: white;
            padding: 75px 0;
        }

        .hero img {
            width: 100%;
            height: 300px;
            object-fit: cover;
            border-radius: 15px;
        }

        section {
            padding: 55px 0;
        }

        .section-title {
            color: #073b2b;
            font-weight: bold;
            margin-bottom: 25px;
        }

        .event-card {
            height: 100%;
            border: none;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 14px #00000012;
            transition: transform 0.2s;
        }

        .event-card:hover {
            transform: translateY(-5px);
        }

        .event-card img {
            height: 190px;
            width: 100%;
            object-fit: cover;
        }

        .btn-portal {
            background-color: #f8d568;
            color: #073b2b;
            font-weight: bold;
        }

        .btn-portal:hover {
            background-color: #edc344;
        }

        .about-box, .form-box {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 3px 12px #0000000d;
        }

        footer {
            background-color: #073b2b;
            color: white;
            padding: 25px 0;
        }

        .source-code {
            background-color: #17212b;
            color: #e5f1e9;
            padding: 20px;
            border-radius: 10px;
            overflow-x: auto;
            white-space: pre-wrap;
            overflow-wrap: anywhere;
            font-size: 13px;
        }

        html {
            scroll-behavior: smooth;
        }
    </style>
</head>

<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg sticky-top">
    <div class="container">
        <a class="navbar-brand fw-bold" href="#home">
            UET Mardan Portal
        </a>

        <button class="navbar-toggler bg-light" type="button"
                data-bs-toggle="collapse"
                data-bs-target="#mainNavbar"
                aria-controls="mainNavbar"
                aria-expanded="false"
                aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="mainNavbar">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                <li class="nav-item"><a class="nav-link" href="#events">Events</a></li>
                <li class="nav-item"><a class="nav-link" href="#schedule">Schedule</a></li>
                <li class="nav-item"><a class="nav-link" href="#registration">Registration</a></li>
                <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<header class="hero" id="home">
    <div class="container">
        <div class="row align-items-center g-4">
            <div class="col-lg-6">
                <h1 class="display-5 fw-bold">
                    Welcome to Student Activities Portal
                </h1>
                <p class="lead mt-3">
                    Discover university events, develop new skills,
                    meet other students and make your campus life memorable.
                </p>
                <a href="#events" class="btn btn-portal btn-lg mt-2">
                    Explore Events
                </a>
            </div>

            <div class="col-lg-6">
                <img
                    src="https://images.unsplash.com/photo-1523580494863-6f3031224c94?auto=format&fit=crop&w=1000&q=80"
                    alt="University students participating in campus activities">
            </div>
        </div>
    </div>
</header>

<!-- About Section -->
<section id="about">
    <div class="container">
        <h2 class="section-title text-center">About Our Portal</h2>

        <div class="about-box">
            <p>
                The UET Mardan Student Activities Portal is a sample
                website designed to help students discover academic,
                technical, cultural and sports activities.
            </p>
            <p class="mb-0">
                Students can explore upcoming events, check the schedule
                and complete the registration form using one simple page.
            </p>
        </div>
    </div>
</section>

<!-- Events Section -->
<section id="events" class="bg-light">
    <div class="container">
        <h2 class="section-title text-center">Upcoming Events</h2>
        <p class="text-center mb-4">
            Explore activities and choose your favourite event.
        </p>

        <div class="row g-4">

            <div class="col-12 col-sm-6 col-lg-3">
                <div class="card event-card">
                    <img
                        src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=600&q=80"
                        class="card-img-top"
                        alt="Students working with computers">
                    <div class="card-body">
                        <h5 class="card-title">Coding Competition</h5>
                        <p class="card-text">
                            Test your programming skills and solve
                            interesting coding problems.
                        </p>
                        <a href="#registration" class="btn btn-success">
                            Register
                        </a>
                    </div>
                </div>
            </div>

            <div class="col-12 col-sm-6 col-lg-3">
                <div class="card event-card">
                    <img
                        src="https://images.unsplash.com/photo-1540575467063-178a50c2df87?auto=format&fit=crop&w=600&q=80"
                        class="card-img-top"
                        alt="People attending a seminar">
                    <div class="card-body">
                        <h5 class="card-title">Tech Seminar</h5>
                        <p class="card-text">
                            Learn about modern technologies, AI
                            and future career opportunities.
                        </p>
                        <a href="#registration" class="btn btn-success">
                            Register
                        </a>
                    </div>
                </div>
            </div>

            <div class="col-12 col-sm-6 col-lg-3">
                <div class="card event-card">
                    <img
                        src="https://images.unsplash.com/photo-1528605248644-14dd04022da1?auto=format&fit=crop&w=600&q=80"
                        class="card-img-top"
                        alt="Students sharing a meal">
                    <div class="card-body">
                        <h5 class="card-title">Cultural Day</h5>
                        <p class="card-text">
                            Celebrate different traditions, cultures
                            and student creativity.
                        </p>
                        <a href="#registration" class="btn btn-success">
                            Register
                        </a>
                    </div>
                </div>
            </div>

            <div class="col-12 col-sm-6 col-lg-3">
                <div class="card event-card">
                    <img
                        src="https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=600&q=80"
                        class="card-img-top"
                        alt="Athletes running on a track">
                    <div class="card-body">
                        <h5 class="card-title">Sports Festival</h5>
                        <p class="card-text">
                            Participate in sports, show your talent
                            and promote teamwork.
                        </p>
                        <a href="#registration" class="btn btn-success">
                            Register
                        </a>
                    </div>
                </div>
            </div>

        </div>
    </div>
</section>

<!-- Event Schedule -->
<section id="schedule">
    <div class="container">
        <h2 class="section-title text-center">Event Schedule</h2>

        <div class="table-responsive">
            <table class="table table-bordered table-striped
                          table-hover text-center align-middle">
                <thead class="table-success">
                    <tr>
                        <th>Event Name</th>
                        <th>Date</th>
                        <th>Time</th>
                        <th>Venue</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Coding Competition</td>
                        <td>20 October 2026</td>
                        <td>10:00 AM</td>
                        <td>Computer Lab</td>
                    </tr>
                    <tr>
                        <td>Tech Seminar</td>
                        <td>22 October 2026</td>
                        <td>11:00 AM</td>
                        <td>Seminar Hall</td>
                    </tr>
                    <tr>
                        <td>Cultural Day</td>
                        <td>25 October 2026</td>
                        <td>09:00 AM</td>
                        <td>Main Auditorium</td>
                    </tr>
                    <tr>
                        <td>Sports Festival</td>
                        <td>28 October 2026</td>
                        <td>08:00 AM</td>
                        <td>Sports Ground</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <p class="text-muted small">
            Note: These dates and venues are sample data for the assignment.
        </p>
    </div>
</section>

<!-- Registration Form -->
<section id="registration" class="bg-light">
    <div class="container">
        <h2 class="section-title text-center">Student Registration</h2>

        <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="form-box">
                    <form action="#" method="get">

                        <div class="mb-3">
                            <label for="fullName" class="form-label">
                                Full Name
                            </label>
                            <input type="text" class="form-control"
                                   id="fullName" name="fullName"
                                   placeholder="Enter your full name"
                                   required>
                        </div>

                        <div class="mb-3">
                            <label for="email" class="form-label">
                                Email Address
                            </label>
                            <input type="email" class="form-control"
                                   id="email" name="email"
                                   placeholder="example@email.com"
                                   required>
                        </div>

                        <div class="mb-3">
                            <label for="department" class="form-label">
                                Department
                            </label>
                            <select class="form-select" id="department"
                                    name="department" required>
                                <option value="">Select Department</option>
                                <option>Computer Science</option>
                                <option>Electrical Engineering</option>
                                <option>Mechanical Engineering</option>
                                <option>Civil Engineering</option>
                                <option>Other</option>
                            </select>
                        </div>

                        <div class="mb-3">
                            <label for="event" class="form-label">
                                Select Event
                            </label>
                            <select class="form-select" id="event"
                                    name="event" required>
                                <option value="">Choose an Event</option>
                                <option>Coding Competition</option>
                                <option>Tech Seminar</option>
                                <option>Cultural Day</option>
                                <option>Sports Festival</option>
                            </select>
                        </div>

                        <fieldset class="mb-3">
                            <legend class="fs-6">Gender</legend>

                            <div class="form-check form-check-inline">
                                <input class="form-check-input"
                                       type="radio" name="gender"
                                       id="male" value="Male" required>
                                <label class="form-check-label"
                                       for="male">Male</label>
                            </div>

                            <div class="form-check form-check-inline">
                                <input class="form-check-input"
                                       type="radio" name="gender"
                                       id="female" value="Female">
                                <label class="form-check-label"
                                       for="female">Female</label>
                            </div>

                            <div class="form-check form-check-inline">
                                <input class="form-check-input"
                                       type="radio" name="gender"
                                       id="other" value="Other">
                                <label class="form-check-label"
                                       for="other">Other</label>
                            </div>
                        </fieldset>

                        <div class="mb-3">
                            <label for="message" class="form-label">
                                Message
                            </label>
                            <textarea class="form-control" id="message"
                                      name="message" rows="4"
                                      placeholder="Write your message here"></textarea>
                        </div>

                        <button type="submit" class="btn btn-success w-100">
                            Submit Registration
                        </button>

                    </form>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contact">
    <div class="container text-center">
        <h2 class="section-title">Contact Us</h2>
        <p>UET Mardan Student Activities Portal</p>
        <p>Department of Computer Science</p>
        <p>Email: studentportal@example.com</p>
    </div>
</section>

<!-- Footer -->
<footer class="text-center">
    <div class="container">
        <p class="mb-1">
            &copy; 2026 UET Mardan Student Activities Portal
        </p>
        <p class="mb-0">Designed for Web Design & Development Assignment 01</p>
    </div>
</footer>

<!-- Source Code Section -->
<section id="source-code">
    <div class="container">
        <h2 class="section-title text-center">Website Source Code</h2>
        <p>
            The main page uses the HTML structure and inline CSS shown
            in this file. The source-code display below is a guide;
            replace this text with the escaped source of the complete
            file before submitting your assignment.
        </p>
        <pre class="source-code"><code>&lt;!-- UET Mardan Student Activities Portal --&gt;
&lt;!-- Main sections: Navbar, Hero, About, Events,
     Schedule, Registration, Contact and Footer --&gt;
&lt;!-- See the complete index.html source above. --&gt;</code></pre>
    </div>
</section>

<!-- Bootstrap JS is needed for the mobile navbar toggle -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
