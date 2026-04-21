<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3D Portfolio - John Doe</title>
    <meta name="description" content="Modern 3D Portfolio Website - Full Stack Developer">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- 3D Canvas Background -->
    <canvas id="bgCanvas"></canvas>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">
                <h2>J<span class="gradient-text">D</span></h2>
            </div>
            <ul class="nav-menu">
                <li><a href="#home" class="nav-link">Home</a></li>
                <li><a href="#about" class="nav-link">About</a></li>
                <li><a href="#projects" class="nav-link">Projects</a></li>
                <li><a href="#contact" class="nav-link">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </div>
    </nav>
  <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <div class="hero-text">
                <h1 class="hero-title">
                    Hi, I'm <span class="gradient-text">John Doe</span>
                </h1>
                <p class="hero-subtitle">Full Stack Developer crafting amazing digital experiences</p>
                <div class="hero-buttons">
                    <a href="#projects" class="btn btn-primary">View Projects</a>
                    <a href="#contact" class="btn btn-secondary">Contact Me</a>
                </div>
            </div>
            <div class="hero-3d">
                <div class="floating-card" data-tilt>
                    <div class="card-content">
                        <i class="fab fa-react"></i>
                        <h3>React</h3>
                    </div>
                </div>
                <div class="floating-card" data-tilt>
                    <div class="card-content">
                        <i class="fab fa-node-js"></i>
                        <h3>Node.js</h3>
                    </div>
                </div>
                <div class="floating-card" data-tilt>
                    <div class="card-content">
                        <i class="fas fa-database"></i>
                        <h3>MongoDB</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>
 <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <h3>Passionate Full Stack Developer</h3>
                    <p>I create stunning web applications with modern technologies. With 5+ years of experience, I specialize in building scalable, performant, and user-friendly applications.</p>
                    <div class="skills">
                        <div class="skill-item">
                            <span>JavaScript</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="95%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>React</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="90%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Node.js</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="about-image">
                    <div class="image-container">
                        <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400&h=400&fit=crop" alt="John Doe">
                    </div>
                </div>
            </div>
        </div>
    </section>
<!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2 class="section-title">Featured Projects</h2>
            <div class="projects-grid">
                <div class="project-card" data-tilt>
                    <div class="project-image">
                        <img src="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?w=400&h=250&fit=crop" alt="E-commerce">
                        <div class="project-overlay">
                            <h3>E-Commerce Platform</h3>
                            <p>Full stack e-commerce solution with payment integration</p>
                        </div>
                    </div>
                    <div class="project-info">
                        <h3>E-Commerce Platform</h3>
                        <p>React, Node.js, MongoDB, Stripe Payments</p>
                        <div class="project-links">
                            <a href="#" class="project-link"><i class="fab fa-github"></i></a>
                            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i></a>
                        </div>
                    </div>
                </div>
                <!-- Add more project cards -->
                <div class="project-card" data-tilt>
                    <div class="project-image">
                        <img src="https://images.unsplash.com/photo-1551650975-87deedd944c3?w=400&h=250&fit=crop" alt="Dashboard">
                        <div class="project-overlay">
                            <h3>Analytics Dashboard</h3>
                            <p>Real-time data visualization dashboard</p>
                        </div>
                    </div>
                    <div class="project-info">
                        <h3>Analytics Dashboard</h3>
                        <p>React, Chart.js, Express, Socket.io</p>
                        <div class="project-links">
                            <a href="#" class="project-link"><i class="fab fa-github"></i></a>
                            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i></a>
                        </div>
                    </div>
                </div>
                <div class="project-card" data-tilt>
                    <div class="project-image">
                        <img src="https://images.unsplash.com/photo-1517433456452-f9633a875f6f?w=400&h=250&fit=crop" alt="Chat App">
                        <div class="project-overlay">
                            <h3>Real-time Chat</h3>
                            <p>Modern chat application with real-time messaging</p>
                        </div>
                    </div>
                    <div class="project-info">
                        <h3>Real-time Chat App</h3>
                        <p>React, Socket.io, Node.js, MongoDB</p>
                        <div class="project-links">
                            <a href="#" class="project-link"><i class="fab fa-github"></i></a>
                            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
  <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <h3>Email</h3>
                        <p>john.doe@email.com</p>
                    </div>
                    <div class="contact-item">
                        <i class="fab fa-linkedin"></i>
                        <h3>LinkedIn</h3>
                        <p>/in/johndoe</p>
                    </div>
                    <div class="contact-item">
                        <i class="fab fa-github"></i>
                        <h3>GitHub</h3>
                        <p>github.com/johndoe</p>
                    </div>
                </div>
                <form class="contact-form">
                    <div class="form-group">
                        <input type="text" placeholder="Your Name" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Your Email" required>
                    </div>
                    <div class="form-group">
                        <textarea placeholder="Your Message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </div>
    </section>
 <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 John Doe. All rights reserved.</p>
        </div>
    </footer>

 <script src="https://cdnjs.cloudflare.com/ajax/libs/vanilla-tilt/1.7.0/vanilla-tilt.min.js"></script>
  <script src="script.js"></script>
</body>
</html>
