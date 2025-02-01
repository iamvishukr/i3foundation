Thanks for downloading this template!

Template Name: Multi
Template URL: https://bootstrapmade.com/multi-responsive-bootstrap-template/
Author: BootstrapMade.com
License: https://bootstrapmade.com/license/




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Everest Summit 2.0: Beyond the Mountains</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<style>
  /* General Styles */
body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  padding: 0;
  color: #333;
  background-color: #f9f9f9;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px 0;
}

h1, h2, h3 {
  margin: 0;
  font-weight: 600;
}

p {
  line-height: 1.6;
}

a {
  text-decoration: none;
  color: inherit;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background-color: #ff6f61;
  color: #fff;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.btn:hover {
  background-color: #ff4a3d;
}

/* Hero Section */
.hero {
  height: 80vh;
  background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://via.placeholder.com/1920x1080') no-repeat center center/cover;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
}

.hero-content h1 {
  font-size: 4rem;
  margin-bottom: 10px;
}

.hero-content p {
  font-size: 1.5rem;
  margin-bottom: 20px;
}

/* Highlights Section */
.highlights {
  padding: 60px 0;
  background-color: #fff;
  text-align: center;
}

.highlight-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.highlight-card {
  background-color: #f4f4f4;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.highlight-card:hover {
  transform: translateY(-10px);
}

.highlight-card .icon {
  font-size: 2rem;
  color: #ff6f61;
  margin-bottom: 15px;
}

/* Get Your Pass Section */
.passes {
  padding: 60px 0;
  background-color: #f4f4f4;
  text-align: center;
}

.pass-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.pass-card {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.pass-card:hover {
  transform: translateY(-10px);
}

.pass-card .price {
  font-size: 2rem;
  font-weight: 600;
  color: #ff6f61;
  margin: 10px 0;
}

.pass-card ul {
  list-style: none;
  padding: 0;
  margin: 20px 0;
}

.pass-card ul li {
  margin-bottom: 10px;
  text-align: left;
}

.pass-card ul li i {
  color: #ff6f61;
  margin-right: 10px;
}

/* Speakers Section */
.speakers {
  padding: 60px 0;
  background-color: #fff;
  text-align: center;
}

.speaker-row {
  display: flex;
  justify-content: space-between;
  gap: 20px;
  margin-bottom: 20px;
}

.speaker-card {
  background-color: #f4f4f4;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
  flex: 1;
}

.speaker-card:hover {
  transform: translateY(-10px);
}

.speaker-card img {
  border-radius: 50%;
  margin-bottom: 15px;
}

.speaker-card h3 {
  font-size: 1.5rem;
  margin-bottom: 10px;
}

.speaker-card p {
  font-size: 1rem;
  color: #777;
}

/* Why Join Section */
.why-join {
  padding: 60px 0;
  background-color: #f4f4f4;
  text-align: center;
}

.why-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.why-card {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.why-card:hover {
  transform: translateY(-10px);
}

.why-card .icon {
  font-size: 2rem;
  color: #ff6f61;
  margin-bottom: 15px;
}

/* Previous Event Section */
.previous-event {
  padding: 60px 0;
  background-color: #fff;
  text-align: center;
}

.previous-event img {
  width: 100%;
  max-width: 800px;
  border-radius: 10px;
  margin-bottom: 20px;
}

/* Testimonials Section */
.testimonials {
  padding: 60px 0;
  background-color: #f4f4f4;
  text-align: center;
}

.testimonial-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.testimonial-card {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.testimonial-card:hover {
  transform: translateY(-10px);
}

.testimonial-card img {
  border-radius: 50%;
  margin-bottom: 15px;
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero-content h1 {
    font-size: 3rem;
  }

  .hero-content p {
    font-size: 1.2rem;
  }

  .speaker-row {
    flex-direction: column;
  }

  .pass-grid {
    grid-template-columns: 1fr;
  }
}
</style>
<body>
  <main>
    <!-- Hero Section -->
    <section class="hero">
      <div class="hero-content">
        <h1 class="animate__animated animate__fadeInDown">Everest Summit 2.0: Beyond the Mountains</h1>
        <p class="animate__animated animate__fadeInUp">Get ready to be inspired by extraordinary stories of courage and determination!</p>
        <a href="#highlights" class="btn animate__animated animate__fadeIn">Explore Highlights</a>
      </div>
    </section>

    <!-- Highlights Section -->
    <section id="highlights" class="highlights">
      <div class="container">
        <h2>Highlights</h2>
        <div class="highlight-grid">
          <div class="highlight-card animate__animated">
            <i class="fas fa-mountain icon"></i>
            <h3>Meet the Heroes</h3>
            <p>Experience firsthand accounts from mountaineers who have scaled the highest peaks on Earth.</p>
          </div>
          <div class="highlight-card animate__animated">
            <i class="fas fa-book-open icon"></i>
            <h3>Inspiring Stories</h3>
            <p>Dive into tales of perseverance and bravery that define the true spirit of adventure.</p>
          </div>
          <div class="highlight-card animate__animated">
            <i class="fas fa-users icon"></i>
            <h3>Community Spirit</h3>
            <p>Connect with fellow adventurers and outdoor enthusiasts in a truly memorable gathering.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Get Your Pass Section -->
    <section class="passes">
      <div class="container">
        <h2>Get Your Pass</h2>
        <div class="pass-grid">
          <!-- Silver Pass -->
          <div class="pass-card animate__animated">
            <h3>Silver</h3>
            <p class="price">₹ 2000</p>
            <ul>
              <li><i class="fas fa-check-circle"></i> Access to all keynote sessions with legendary mountaineers.</li>
              <li><i class="fas fa-check-circle"></i> Networking opportunities with fellow adventurers and enthusiasts.</li>
              <li><i class="fas fa-check-circle"></i> For Individual</li>
            </ul>
            <a href="#" class="btn">Buy Now</a>
          </div>
          <!-- Gold Pass -->
          <div class="pass-card animate__animated">
            <h3>Gold</h3>
            <p class="price">₹ 5000</p>
            <ul>
              <li><i class="fas fa-check-circle"></i> Access to all keynote sessions with legendary mountaineers.</li>
              <li><i class="fas fa-check-circle"></i> Networking opportunities with fellow adventurers and enthusiasts.</li>
              <li><i class="fas fa-check-circle"></i> For Corporate Delegates</li>
            </ul>
            <a href="#" class="btn">Buy Now</a>
          </div>
          <!-- Diamond Pass -->
          <div class="pass-card animate__animated">
            <h3>Diamond</h3>
            <p class="price">₹ 10000</p>
            <ul>
              <li><i class="fas fa-check-circle"></i> Access to all keynote sessions with legendary mountaineers.</li>
              <li><i class="fas fa-check-circle"></i> Networking opportunities with fellow adventurers and enthusiasts.</li>
              <li><i class="fas fa-check-circle"></i> Premium Seating</li>
            </ul>
            <a href="#" class="btn">Buy Now</a>
          </div>
          <!-- Platinum Pass -->
          <div class="pass-card animate__animated">
            <h3>Platinum</h3>
            <p class="price">₹ 20000</p>
            <ul>
              <li><i class="fas fa-check-circle"></i> Access to all keynote sessions with legendary mountaineers.</li>
              <li><i class="fas fa-check-circle"></i> Networking opportunities with fellow adventurers and enthusiasts.</li>
              <li><i class="fas fa-check-circle"></i> Access to Pre-Event</li>
              <li><i class="fas fa-check-circle"></i> Premium Seating</li>
            </ul>
            <a href="#" class="btn">Buy Now</a>
          </div>
        </div>
      </div>
    </section>

    <!-- Speakers Section -->
    <section class="speakers">
      <div class="container">
        <h2>Speakers</h2>
        <div class="speaker-row">
          <div class="speaker-card animate__animated">
            <img src="https://via.placeholder.com/150" alt="Speaker 1">
            <h3>Debraj Dutta</h3>
            <p>Mountaineer & Motivational Speaker</p>
          </div>
          <div class="speaker-card animate__animated">
            <img src="https://via.placeholder.com/150" alt="Speaker 2">
            <h3>Poorna Malavath</h3>
            <p>Youngest Everest Summiteer</p>
          </div>
          <div class="speaker-card animate__animated">
            <img src="https://via.placeholder.com/150" alt="Speaker 3">
            <h3>Sunil Nataraj</h3>
            <p>Adventurer & Environmentalist</p>
          </div>
        </div>
        <div class="speaker-row">
          <div class="speaker-card animate__animated">
            <img src="https://via.placeholder.com/150" alt="Speaker 4">
            <h3>Sharad Kulkarni</h3>
            <p>Mountaineer & Author</p>
          </div>
          <div class="speaker-card animate__animated">
            <img src="https://via.placeholder.com/150" alt="Speaker 5">
            <h3>Sangeeta Sindhi</h3>
            <p>Adventurer & Motivational Speaker</p>
          </div>
          <div class="speaker-card animate__animated">
            <img src="https://via.placeholder.com/150" alt="Speaker 6">
            <h3>Anand Kumar</h3>
            <p>Mountaineer & Educator</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Why Join Section -->
    <section class="why-join">
      <div class="container">
        <h2>Why You Should Join Our Event?</h2>
        <div class="why-grid">
          <div class="why-card animate__animated">
            <i class="fas fa-trophy icon"></i>
            <h3>Peak Performance</h3>
            <p>Achieving the summit of Everest represents the pinnacle of human endurance.</p>
          </div>
          <div class="why-card animate__animated">
            <i class="fas fa-users-cog icon"></i>
            <h3>Team Collaboration</h3>
            <p>Conquering Everest is a testament to the power of teamwork.</p>
          </div>
          <div class="why-card animate__animated">
            <i class="fas fa-book icon"></i>
            <h3>Endless Knowledge</h3>
            <p>The journey offers insights into geology, meteorology, and high-altitude physiology.</p>
          </div>
          <div class="why-card animate__animated">
            <i class="fas fa-heart icon"></i>
            <h3>Personal Growth</h3>
            <p>Scaling Everest is a journey of self-discovery and spiritual growth.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Previous Event Section -->
    <section class="previous-event">
      <div class="container">
        <h2>Previous Event</h2>
        <div class="event-content">
          <img src="https://via.placeholder.com/800x400" alt="Previous Event">
          <p>Everest Summit: Let's Win the Mountains (2023)</p>
          <a href="#" class="btn">View Gallery</a>
        </div>
      </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
      <div class="container">
        <h2>Testimonials</h2>
        <div class="testimonial-grid">
          <div class="testimonial-card animate__animated">
            <img src="https://via.placeholder.com/100" alt="Testimonial 1">
            <h3>Mr. Amit Modi</h3>
            <p>"The i3 Foundation Trekking to Annapurna Base Camp was a life-changing experience for me."</p>
          </div>
          <div class="testimonial-card animate__animated">
            <img src="https://via.placeholder.com/100" alt="Testimonial 2">
            <h3>Mr. Sanjay Kumar</h3>
            <p>"The support of the organization was exceptional, making the journey unforgettable."</p>
          </div>
        </div>
      </div>
    </section>
  </main>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.10.4/gsap.min.js"></script>
  <script src="script.js"></script>
</body>
</html>