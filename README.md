<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="google-site-verification" content="Hdc1Z5iRvX7ptFIC72na7HXMMzE_K5NzcweguzwYN8I" />
  <title>DANNY CARE</title>

  <!-- SEO Meta Tags -->
  <meta name="description" content="DANNY CARE - Delivery of medication, prescription, and medical assistance. Contact us at dannysmilo083@gmail.com or 079 127 0724." />
  <meta name="keywords" content="medical assistance, medication delivery, prescription, healthcare, DANNY CARE" />
  <meta name="author" content="Danny Smilo" />
  <meta property="og:title" content="DANNY CARE - Medical Services" />
  <meta property="og:description" content="Reliable delivery of medication, prescriptions, and medical assistance. Contact us today!" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://dannysmilo.github.io" />
  <!-- Optional: Add your logo image URL below or remove the line -->
  <!-- <meta property="og:image" content="https://yourdomain.com/path-to-logo.png" /> -->

  <!-- Google Fonts Open Sans -->
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet" />

  <style>
    /* Reset & base */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Open Sans', Arial, sans-serif;
      background: #f4f8ff;
      color: #333;
      line-height: 1.6;
    }
    a {
      color: inherit;
      text-decoration: none;
    }
    /* Navigation Bar */
    nav {
      background: #004aad;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav .logo {
      font-weight: 700;
      font-size: 1.5rem;
      letter-spacing: 2px;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 25px;
    }
    nav ul li a {
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav ul li a:hover {
      color: #a8cdf0;
    }
    .btn-group {
      display: flex;
      gap: 15px;
    }
    .btn {
      background: white;
      color: #004aad;
      border: none;
      padding: 10px 18px;
      font-weight: 600;
      border-radius: 4px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
      text-transform: uppercase;
      font-size: 0.9rem;
    }
    .btn:hover {
      background: #a8cdf0;
      color: white;
    }
    /* Header */
    header {
      background: #004aad;
      color: white;
      text-align: center;
      padding: 100px 20px 60px;
    }
    header h1 {
      font-size: 3rem;
      letter-spacing: 3px;
      margin-bottom: 15px;
    }
    header p {
      font-size: 1.3rem;
      font-weight: 400;
      max-width: 600px;
      margin: auto;
      line-height: 1.4;
    }
    /* Sections */
    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }
    h2 {
      color: #004aad;
      margin-bottom: 20px;
      font-weight: 700;
      font-size: 2rem;
      border-bottom: 3px solid #004aad;
      padding-bottom: 8px;
      max-width: 220px;
    }
    /* Services */
    .services {
      display: flex;
      gap: 25px;
      flex-wrap: wrap;
    }
    .service {
      background: white;
      flex: 1 1 300px;
      padding: 25px;
      border-radius: 8px;
      box-shadow: 0 5px 15px rgba(0, 74, 173, 0.1);
      transition: transform 0.3s ease;
    }
    .service:hover {
      transform: translateY(-7px);
    }
    .service h3 {
      color: #004aad;
      margin-bottom: 15px;
    }
    /* Contact */
    .contact {
      background: #e8f0ff;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      max-width: 500px;
      margin: 40px auto;
      text-align: center;
    }
    .contact a {
      color: #004aad;
      font-weight: 600;
    }
    /* Form Styling */
    form label {
      display: block;
      margin-bottom: 6px;
      font-weight: 600;
      color: #004aad;
      text-align: left;
    }
    form input[type="text"],
    form input[type="email"],
    form textarea {
      width: 100%;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
      margin-bottom: 15px;
      font-size: 1rem;
      font-family: 'Open Sans', Arial, sans-serif;
      resize: vertical;
    }
    form button {
      width: 100%;
      padding: 12px;
      background-color: #004aad;
      border: none;
      color: white;
      font-weight: 700;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
      text-transform: uppercase;
      transition: background-color 0.3s ease;
    }
    form button:hover {
      background-color: #0066ff;
    }
    /* Footer */
    footer {
      background: #004aad;
      color: white;
      text-align: center;
      padding: 20px 15px;
      font-size: 0.9rem;
      margin-top: 40px;
    }
    /* Responsive */
    @media (max-width: 768px) {
      .services {
        flex-direction: column;
      }
      nav ul {
        display: none;
      }
      nav {
        justify-content: space-between;
      }
    }
  </style>
</head>
<body>

  <nav>
    <div class="logo">DANNY CARE</div>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <div class="btn-group">
      <button class="btn" onclick="alert('Booking feature coming soon!')">Book Now</button>
      <a href="tel:+0791270724" class="btn">Call Now</a>
    </div>
  </nav>

  <header id="home">
    <h1>DANNY CARE</h1>
    <p>Quality medical support, delivered with care</p>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>Welcome to DANNY CARE! We provide essential medical services to support your health and well-being. Whether you need medicine delivered, prescriptions filled, or direct medical assistance, we're here to help — quickly, reliably, and with care.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service">
        <h3>Delivery of Medication</h3>
        <p>Fast and reliable delivery of your prescribed medicines right to your door.</p>
      </div>
      <div class="service">
        <h3>Prescription of Medicine</h3>
        <p>Consult with certified professionals for accurate and trusted prescriptions.</p>
      </div>
      <div class="service">
        <h3>Medical Assistance</h3>
        <p>Friendly and professional support for your medical needs, anytime you need it.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form action="https://formspree.io/f/your-form-id" method="POST">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required />
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="_replyto" required />
      
      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" required></textarea>
      
      <button type="submit" class="btn">Send Message</button>
    </form>
    <p>Email: <a href="mailto:dannysmilo083@gmail.com">dannysmilo083@gmail.com</a></p>
    <p>Phone: <a href="tel:+0791270724">079 127 0724</a></p>
  </section>

  <footer>
    &copy; 2025 DANNY CARE. All rights reserved.
  </footer>

</body>
</html>
