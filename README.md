<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Green Trends Salon – Nallagandla</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: auto;
      padding: 20px;
      background: #f8f8f8;
    }
    h1, h2 {
      color: #2b8a3e;
    }
    ul {
      padding-left: 20px;
    }
    input, button {
      padding: 10px;
      width: 100%;
      margin-bottom: 10px;
    }
    img {
      width: 100%;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <h1>💇 Green Trends Salon – Nallagandla</h1>
  <img src="https://i.imgur.com/BqHcphC.jpg" alt="Salon Banner" />

  <h2>💥 Offers This Week</h2>
  <ul>
    <li>20% Off on Hair Spa</li>
    <li>Pedicure + Manicure at ₹899</li>
    <li>Haircut + Hair Wash at ₹499</li>
  </ul>

  <h2>🛎️ Our Services</h2>
  <ul>
    <li>Haircut & Styling</li>
    <li>Hair Spa & Coloring</li>
    <li>Facials & Clean-ups</li>
    <li>Bridal Makeup</li>
  </ul>

  <h2>📍 Location & Contact</h2>
  <p>Nallagandla, Hyderabad</p>
  <p>Phone: +91-XXXXXXXXXX</p>
  <p>Open: 10 AM – 8 PM, All Days</p>

  <h2>📋 Book an Appointment</h2>
  <form action="https://formsubmit.co/hasinimaganti27@gmail.com" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="text" name="service" placeholder="Service You Want" required>
    <input type="date" name="date" required>
    <input type="tel" name="phone" placeholder="+91-XXXXXXXXXX" required>
    <input type="hidden" name="_captcha" value="false">
    <button type="submit">Book Now</button>
  </form>

  <h2>💬 Chat With Our Bot</h2>
  <p>Ask about offers, services, or book appointments below.</p>

  <!-- Botpress V3 Webchat Embed -->
  <script src="https://cdn.botpress.cloud/webchat/v3/inject.js"></script>
  <script>
    window.addEventListener("DOMContentLoaded", function () {
      window.botpressWebChat.init({
        configUrl: "https://files.bpcontent.cloud/2025/06/16/09/20250616093105-BU0FR2ZA.json"
      });
    });
  </script>

</body>
</html>
