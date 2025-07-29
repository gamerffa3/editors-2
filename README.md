<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Editor Services</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f8f8;
    }
    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .reviews {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    .review {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .review h3 {
      margin-top: 0;
      color: #333;
    }
    .contact {
      background: #e0e0e0;
      padding: 20px;
      border-radius: 10px;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Professional Editing Services</h1>
    <p>High-quality editing for all your needs</p>
  </header>

  <div class="section">
    <h2>Client Reviews</h2>
    <div class="reviews">
      <div class="review">
        <h3>Ali Khan</h3>
        <p>"Bahut hi behtareen service thi. Mere document bilkul professional bana diye."</p>
      </div>
      <div class="review">
        <h3>Sana Raza</h3>
        <p>"Editor ne meri CV ko perfect banaya. Fast aur reliable service!"</p>
      </div>
      <div class="review">
        <h3>Rehan Malik</h3>
        <p>"Editing quality top-notch thi. Highly recommended."</p>
      </div>
    </div>
  </div>

  <div class="section">
    <h2>Contact Us</h2>
    <div class="contact">
      <form>
        <label for="name">Name:</label><br />
        <input type="text" id="name" name="name" required /><br /><br />

        <label for="email">Email:</label><br />
        <input type="email" id="email" name="email" required /><br /><br />

        <label for="message">Message:</label><br />
        <textarea id="message" name="message" rows="4" required></textarea><br /><br />

        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 Editor Services. All rights reserved.</p>
  </footer>
</body>
</html>
