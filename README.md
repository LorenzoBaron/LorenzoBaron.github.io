<html>
<head>
    <title>Nomad - Empowering Digital Nomads</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Nomad</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#services">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="py-5 text-center">
        <div class="container">
            <h1 class="display-4">Empowering Digital Nomads</h1>
            <p class="lead">Flexible coworking solutions for the modern workforce</p>
        </div>
    </header>

    <section id="about" class="py-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <h2>About Nomad</h2>
                    <p>Nomad is a global platform that empowers digital nomads, freelancers, remote workers, and entrepreneurs with affordable and flexible coworking solutions. We believe in fostering a vibrant community and promoting synergistic collaborations.</p>
                </div>
                <div class="col-lg-6">
                    <h2>Our Mission</h2>
                    <p>To empower digital nomads and freelancers with affordable and flexible coworking solutions, fostering a vibrant community and promoting synergistic collaborations.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">Our Services</h2>
            <div class="row">
                <div class="col-lg-4 mb-4">
                    <div class="card">
                        <img src="https://source.unsplash.com/featured/?coworking" class="card-img-top" alt="Coworking Space">
                        <div class="card-body">
                            <h5 class="card-title">Membership Plans</h5>
                            <p class="card-text">Tiered membership plans offering access to partnered coworking spaces, exclusive events, and community forums.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 mb-4">
                    <div class="card">
                        <img src="https://source.unsplash.com/featured/?city" class="card-img-top" alt="City Transition">
                        <div class="card-body">
                            <h5 class="card-title">City Transition Assistance</h5>
                            <p class="card-text">Assistance with logistics, accommodation, and local orientation to facilitate seamless transitions between cities.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 mb-4">
                    <div class="card">
                        <img src="https://source.unsplash.com/featured/?networking" class="card-img-top" alt="Community Building">
                        <div class="card-body">
                            <h5 class="card-title">Community Building</h5>
                            <p class="card-text">Regular networking events, workshops, and social gatherings to foster a sense of belonging and collaboration.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 mb-4">
                    <div class="card">
                        <img src="https://source.unsplash.com/featured/?collaboration" class="card-img-top" alt="Collaboration Platform">
                        <div class="card-body">
                            <h5 class="card-title">Collaboration Platform</h5>
                            <p class="card-text">An online platform for members to collaborate on projects, share opportunities, and seek advice from a supportive community.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <div class="row">
                <div class="col-lg-6">
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
                            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </form>
                </div>
                <div class="col-lg-6">
                    <div id="map"></div>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-4 bg-dark text-white text-center">
        <div class="container">
            <p>&copy; 2022 Nomad. All rights reserved.</p>
        </div>
    </footer>

    <script>
        function initMap() {
            // Google Maps API integration
            // Replace YOUR_API_KEY with the actual API key
            var map = new google.maps.Map(document.getElementById('map'), {
                center: { lat: 52.3702, lng: 4.8952 }, // Amsterdam coordinates
                zoom: 12
            });
        }
    </script>
    <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.min.js"></script>
</body>
</html>


