# Data-share-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DataSwap - Buy, Sell &amp; Share Unused Data Securely</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f5f5f5;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #007bff;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      margin-bottom: 1.5rem;
    }

    .cta button {
      background: #fff;
      color: #007bff;
      border: none;
      padding: 0.8rem 2rem;
      font-size: 1.1rem;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s ease;
    }

    .cta button:hover {
      background: #e0e0e0;
    }

    section {
      padding: 2rem 1rem;
      max-width: 1200px;
      margin: 0 auto;
    }

    section h2 {
      text-align: center;
      margin-bottom: 1.5rem;
      font-size: 2rem;
    }

    .how-it-works {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
    }

    .step {
      background: #fff;
      padding: 1.5rem;
      margin: 0.5rem;
      flex: 1 1 250px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }

    .step h3 {
      margin-bottom: 0.8rem;
      font-size: 1.5rem;
    }

    .signup-form {
      max-width: 400px;
      background: #fff;
      margin: 2rem auto;
      padding: 1.5rem;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .signup-form input[type="text"],
    .signup-form input[type="email"] {
      width: 100%;
      padding: 0.8rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 3px;
    }

    .signup-form button {
      width: 100%;
      padding: 0.8rem;
      background: #007bff;
      border: none;
      color: #fff;
      font-size: 1.1rem;
      cursor: pointer;
      border-radius: 3px;
      margin-top: 1rem;
      transition: background 0.3s ease;
    }

    .signup-form button:hover {
      background: #0056b3;
    }

    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }
      header p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>DataSwap</h1>
    <p>Buy, Sell &amp; Share Unused Data Securely!</p>
    <div class="cta">
      <button onclick="document.getElementById('signup').scrollIntoView({ behavior: 'smooth' });">
        Get Started
      </button>
    </div>
  </header>

  <section>
    <h2>How It Works</h2>
    <div class="how-it-works">
      <div class="step">
        <h3>Sell Your Data</h3>
        <p>List your unused mobile data and earn money effortlessly.</p>
      </div>
      <div class="step">
        <h3>Buy Cheap Data</h3>
        <p>Purchase discounted data from fellow users.</p>
      </div>
      <div class="step">
        <h3>Join a Subscription</h3>
        <p>Pool data plans with others and split the cost.</p>
      </div>
    </div>
  </section>

  <section id="signup">
    <h2>Early Access Signup</h2>
    <div class="signup-form">
      <form onsubmit="alert('Thank you for signing up!'); return false;">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="email" placeholder="Your Email" required />
        <button type="submit">Sign Up</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 DataSwap. All rights reserved.</p>
  </footer>
</body>
</html>
