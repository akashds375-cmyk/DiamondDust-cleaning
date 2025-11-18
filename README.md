<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Diamond Dust Cleaning</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f5f7fa; }
    header { background: linear-gradient(135deg, #1e3a8a, #3b82f6); color: white; padding: 40px 20px; text-align: center; }
    nav { background: #0f172a; padding: 15px; text-align: center; }
    nav a { color: white; margin: 0 20px; text-decoration: none; font-weight: bold; font-size: 18px; }
    .hero {
      background: url('https://images.unsplash.com/photo-1581579185169-1f0995d1c3d4?auto=format&fit=crop&w=1500&q=80') center/cover no-repeat;
      color: white;
      padding: 150px 20px;
      text-align: center;
      text-shadow: 0 3px 10px rgba(0,0,0,0.5);
    }
    .hero h1 { font-size: 54px; margin: 0; }
    .hero p { font-size: 22px; margin-top: 15px; }

    .section { padding: 60px 20px; max-width: 1100px; margin: auto; }
    h2 { text-align: center; color: #1e3a8a; font-size: 32px; margin-bottom: 30px; }

    .services { display: flex; gap: 25px; flex-wrap: wrap; }
    .service-card {
      background: white;
      padding: 25px;
      border-radius: 12px;
      flex: 1 1 calc(33% - 25px);
      box-shadow: 0 4px 14px rgba(0,0,0,0.1);
      text-align: center;
    }
    .service-card h3 { margin-top: 0; color: #1e3a8a; }

    .pricing-table { width: 100%; border-collapse: collapse; background: white; box-shadow: 0 4px 14px rgba(0,0,0,0.1); }
    .pricing-table th {
      background: #1e3a8a;
      color: white;
      padding: 15px;
      border: 1px solid #ddd;
      font-size: 18px;
    }
    .pricing-table td {
      padding: 15px;
      border: 1px solid #ddd;
      background: #fafafa;
    }

    .contact-box {
      background: white;
      padding: 30px;
      border-radius: 12px;
      max-width: 600px;
      margin: auto;
      box-shadow: 0 4px 14px rgba(0,0,0,0.1);
    }
    .contact-box p { font-size: 18px; }
    .contact-box strong { color: #1e3a8a; }

    footer { background: #0f172a; color: white; padding: 25px; text-align: center; margin-top: 50px; }
  
    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes slideUp {
      from { transform: translateY(40px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    /* Apply animations */
    .hero {
      animation: fadeIn 1.5s ease-in-out;
    }
    .service-card {
      animation: slideUp 1s ease-in-out;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .service-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    }
    section.section {
      animation: fadeIn 1.2s ease-in-out;
    }

      .contact-form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .contact-form input,
    .contact-form select,
    .contact-form textarea {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 16px;
      background: #f9fafb;
      transition: border 0.3s ease;
    }
    .contact-form input:focus,
    .contact-form select:focus,
    .contact-form textarea:focus {
      border-color: #3b82f6;
      outline: none;
    }
    .contact-form textarea {
      min-height: 120px;
      resize: vertical;
    }
    .submit-btn {
      background: #1e3a8a;
      color: white;
      padding: 14px;
      font-size: 18px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease, transform 0.3s ease;
    }
    .submit-btn:hover {
      background: #3b82f6;
      transform: translateY(-2px);
    }

      .calendar-container iframe {
      animation: fadeIn 1.5s ease-in-out;
    }

  </style>
</head>

<body>
  <header>
    <img src="A_logo_for_&quot;Diamond_Dust_Cleaning&quot;_is_featured_in_.png" alt="Diamond Dust Cleaning Logo" style="width:160px;margin-bottom:20px;background:transparent;mix-blend-mode:normal;" />
    <h1>Diamond Dust Cleaning</h1>
    <p>Shining Spaces. Trusted Service.</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#pricing">Pricing</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    <h1>Your Space Deserves to Shine</h1>
    <p>Professional • Reliable • Affordable</p>
  </div>

  <section class="section" id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service-card">
        <h3>Residential Cleaning</h3>
        <p>Keep your home spotless with recurring or one-time cleanings.</p>
      </div>
      <div class="service-card">
        <h3>Deep Cleaning</h3>
        <p>Detailed top-to-bottom cleaning for a fresh and polished look.</p>
      </div>
      <div class="service-card">
        <h3>Move In / Move Out</h3>
        <p>Ensure your space is perfect when moving in or handing over keys.</p>
      </div>
      <div class="service-card">
        <h3>Commercial Cleaning</h3>
        <p>Professional cleaning for offices, retail spaces, and businesses.</p>
      </div>
      <div class="service-card">
        <h3>Post-Construction</h3>
        <p>Remove dust and debris after renovations or builds.</p>
      </div>
      <div class="service-card">
        <h3>Airbnb / Rental Cleaning</h3>
        <p>Fast, reliable turnover cleaning for rentals and short-stays.</p>
      </div>
    </div>
  </section>

  <section class="section" id="pricing">
    <h2>Pricing</h2>
    <table class="pricing-table">
      <tr>
        <th>Service</th>
        <th>Description</th>
        <th>Price</th>
      </tr>
      <tr>
        <td>Standard Home Cleaning</td>
        <td>General cleaning of living areas, bathrooms, and kitchen.</td>
        <td>$80 - $150</td>
      </tr>
      <tr>
        <td>Deep Cleaning</td>
        <td>Detailed cleaning including baseboards, appliances, and more.</td>
        <td>$150 - $300</td>
      </tr>
      <tr>
        <td>Move In / Move Out</td>
        <td>Full cleaning for empty homes or apartments.</td>
        <td>$200 - $400</td>
      </tr>
      <tr>
        <td>Commercial Cleaning</td>
        <td>Custom plans for offices and businesses.</td>
        <td>Custom Quote</td>
      </tr>
    </table>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <div class="contact-box">
      <p><strong>Phone:</strong> +1 437-228-4472</p>
      <p><strong>Email:</strong> sohalkhushdeep@gmail.com</p>
      <p>Reach out to us anytime for quotes, bookings, or questions. We're here to help!</p>
    </div>
  </section>

  <footer>
    <p>© 2025 Diamond Dust Cleaning. All Rights Reserved.</p>
  </footer>
  <a href="https://wa.me/14372284472" class="floating-btn">Book Now</a>

  <style>
    .floating-btn {
      position: fixed;
      bottom: 25px;
      right: 25px;
      background: #25D366;
      color: white;
      padding: 15px 25px;
      border-radius: 50px;
      font-size: 20px;
      text-decoration: none;
      box-shadow: 0 6px 15px rgba(0,0,0,0.2);
      animation: slideIn 0.8s ease-out, pulse 2s infinite ease-in-out;
      transition: transform 0.3s ease, box-shadow 0.3s ease, background 0.3s ease;
      z-index: 999;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.08); }
      100% { transform: scale(1); }
    }

    @keyframes slideIn {
      from { transform: translateX(80px); opacity: 0; }
      to { transform: translateX(0); opacity: 1; }
    }

    .floating-btn:hover {
      transform: scale(1.12);
      background: #128C7E;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }
    .floating-btn:hover {
      transform: scale(1.08);
      background: #1e3a8a;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }
  </style>


<!-- Booking Calendar Section Starts -->
<section id="booking" class="section">
  <h2 class="section-title">Book an Appointment</h2>
  <p class="section-text">Select a date and time that works best for you.</p>

  <div class="calendar-container" style="display:flex;justify-content:center;">
    <iframe src="https://calendly.com/diamonddustcleaning/book" width="100%" height="650" frameborder="0" style="max-width:900px;border-radius:12px;box-shadow:0 10px 30px rgba(0,0,0,0.15);"></iframe>
  </div>
</section>
<!-- Booking Calendar Section Ends -->



<!-- Success Popup -->
<div id="successPopup" style="
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%) scale(0.8);
  background: white;
  padding: 30px 40px;
  border-radius: 12px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.25);
  text-align: center;
  font-size: 20px;
  color: #1e3a8a;
  opacity: 0;
  pointer-events: none;
  transition: all 0.4s ease;
  z-index: 9999;
">
  <strong>Message Sent Successfully!</strong><br>
  We will get back to you shortly.
</div>

<script>
  const form = document.querySelector('.contact-form');
  const popup = document.getElementById('successPopup');

  form.addEventListener('submit', function(e) {
    e.preventDefault();
    popup.style.opacity = '1';
    popup.style.pointerEvents = 'auto';
    popup.style.transform = 'translate(-50%, -50%) scale(1)';

    setTimeout(() => {
      popup.style.opacity = '0';
      popup.style.pointerEvents = 'none';
      popup.style.transform = 'translate(-50%, -50%) scale(0.8)';
    }, 3000);

    form.reset();
  });
</script>

</body>
</html>
