<!DOCTYPE html>
<html>
<head>
  <title>PanditFinder</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <header>
    <h1 style="font-size:50px;">Welcome to PanditFinder!</h1>
    <p style="font-size;20px:">Book a pandit online with PanditFinder! Browse and select from a list of experienced pandits, check availability and book for your desired date and time, and enjoy easy and secure payment options. With PanditFinder, you can rely on verified and trusted pandits for a hassle-free puja experience. </p>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">How It Works</a></li>
        <li><a href="#">FAQs</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </nav>
  </header>

 <main>
    <section>
      <h2>Find a Pandit</h2>
      <form>
        <label for="pujaType">Puja Type:</label>
        <select id="pujaType">
          <option value="ganeshPuja">Ganesh Puja</option>
          <option value="satyanarayanPuja">Satyanarayan Puja</option>
          <option value="durgaPuja">Durga Puja</option>
          <!-- Add more options as needed -->
        </select>

        <label for="language">Language:</label>
        <select id="language">
          <option value="hindi">Hindi</option>
          <option value="english">English</option>
          <option value="bengali">Bengali</option>
          <!-- Add more options as needed -->
        </select>

<label for="availability">Availability:</label>
        <input type="text" id="availability" placeholder="Enter availability">

        <button type="submit">Search</button>
      </form>
    </section>

    <section>
      <h2>Search Results</h2>
      <div class="pandit-profile">
        <h3>Pandit Name</h3>
        <p>Rating: 4.5</p>
        <p>Language: Hindi, English</p>
        <p>Availability: Monday to Friday</p>
        <button>Contact</button>
      </div>
      <!-- Add more pandit profiles dynamically -->
    </section>
  </main>

  <footer>
    <p>&copy; 2024
