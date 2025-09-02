<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Embinnox Construction</title>
   <!-- Font Awesome -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
   <!-- Custom CSS -->
   <link rel="stylesheet" href="style.css">
</head>
<body>
   <!-- Header -->
   <header class="header">
      <a href="#" class="logo">Em<span>binnox</span></a>
      
      <nav class="navbar">
         <a href="#home" class="active">Home</a>
         <a href="#about">About</a>
         <a href="#services">Services</a>
         <a href="#projects">Projects</a>
         <a href="#pricing">Pricing</a>
         <a href="#contact">Contact</a>
      </nav>

      <div class="icons">
         <div id="menu-btn" class="fas fa-bars"></div>
      </div>
   </header>

   <!-- Home -->
   <section id="home" class="home">
      <div class="overlay"></div>
      <div class="content">
         <h1>We Build Your Future</h1>
         <p>From homes to skyscrapers, we provide quality construction services with trust and excellence.</p>
         <a href="#contact" class="btn">Get a Quote</a>
      </div>
   </section>

   <!-- About -->
   <section id="about" class="about">
      <h2 class="heading">About <span>Us</span></h2>
      <p>
         Embinnox is one of the leading construction companies with over 15 years of experience. 
         We specialize in modern architecture, commercial and residential projects, and renovations. 
         Our team is committed to delivering projects that stand the test of time.
      </p>
   </section>

   <!-- Services -->
   <section id="services" class="services">
      <h2 class="heading">Our <span>Services</span></h2>
      <div class="service-container">
         <div class="service-box">
            <i class="fas fa-building"></i>
            <h3>Construction</h3>
            <p>We construct modern buildings that combine durability and elegance.</p>
         </div>
         <div class="service-box">
            <i class="fas fa-paint-roller"></i>
            <h3>Renovation</h3>
            <p>Transform your old structures into new and stylish designs.</p>
         </div>
         <div class="service-box">
            <i class="fas fa-tools"></i>
            <h3>Maintenance</h3>
            <p>We provide regular and emergency maintenance for your projects.</p>
         </div>
      </div>
   </section>

   <!-- Projects -->
   <section id="projects" class="projects">
      <h2 class="heading">Our <span>Projects</span></h2>
      <div class="project-gallery">
         <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=800&q=80" alt="Skyscraper">
         <img src="https://images.unsplash.com/photo-1501594907352-04cda38ebc29?auto=format&fit=crop&w=800&q=80" alt="Modern House">
         <img src="https://images.unsplash.com/photo-1501183638710-841dd1904471?auto=format&fit=crop&w=800&q=80" alt="Office Building">
         <img src="https://images.unsplash.com/photo-1523413651479-597eb2da0ad6?auto=format&fit=crop&w=800&q=80" alt="Luxury Apartment">
      </div>
   </section>

   <!-- Pricing -->
   <section id="pricing" class="pricing">
      <h2 class="heading">Our <span>Pricing</span></h2>
      <div class="price-container">
         <div class="price-card">
            <h3>Basic Plan</h3>
            <p class="price">$500</p>
            <ul>
               <li>Consultation</li>
               <li>Small Construction</li>
               <li>Support</li>
            </ul>
            <a href="#contact" class="btn">Choose Plan</a>
         </div>
         <div class="price-card popular">
            <h3>Premium Plan</h3>
            <p class="price">$1500</p>
            <ul>
               <li>Full Project</li>
               <li>Custom Design</li>
               <li>24/7 Support</li>
            </ul>
            <a href="#contact" class="btn">Choose Plan</a>
         </div>
         <div class="price-card">
            <h3>Enterprise</h3>
            <p class="price">$5000</p>
            <ul>
               <li>Large Construction</li>
               <li>Architecture & Design</li>
               <li>Lifetime Support</li>
            </ul>
            <a href="#contact" class="btn">Choose Plan</a>
         </div>
      </div>
   </section>

   <!-- Contact -->
   <section id="contact" class="contact">
      <h2 class="heading">Contact <span>Us</span></h2>
      <form>
         <input type="text" placeholder="Your Name" required>
         <input type="email" placeholder="Your Email" required>
         <textarea placeholder="Your Message"></textarea>
         <button type="submit" class="btn">Send Message</button>
      </form>
   </section>

   <!-- Footer -->
   <footer>
      <p>© 2025 Embinnox Construction. All Rights Reserved.</p>
   </footer>

   <!-- JavaScript -->
   <script src="script.js"></script>
</body>
</html>
