<template>
  <div>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
      <div class="container">
        <a class="navbar-brand" href="#">MyPortfolio</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" href="#about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#portfolio">Portfolio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#testimonials">Testimonials</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Hero Section -->
    <header
      class="hero-section d-flex align-items-center text-center text-white"
    >
      <div class="container">
        <h1 class="display-4 fw-bold">Hi, I'm Gabriel</h1>
        <p class="lead">
          A passionate software engineer creating elegant, user-friendly
          solutions.
        </p>
        <a href="#portfolio" class="btn btn-primary btn-lg mt-3"
          >View My Work</a
        >
      </div>
    </header>

    <!-- About Section -->
    <section id="about" class="py-5 bg-light text-center">
      <div class="container">
        <h2>About Me</h2>
        <p class="mt-3">
          I'm a dedicated software engineer with expertise in web development
          and design. I love creating impactful, user-centric experiences that
          solve real-world problems.
        </p>
        <img
          src="https://via.placeholder.com/200"
          alt="Your Image"
          class="rounded-circle mt-4"
        />
      </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-5">
      <div class="container">
        <h2 class="text-center">Portfolio</h2>
        <div class="row mt-4">
          <div class="col-md-4">
            <img
              src="https://via.placeholder.com/400x300"
              alt="Project 1"
              class="img-fluid rounded shadow"
            />
            <p class="text-center mt-2">Project 1</p>
          </div>
          <div class="col-md-4">
            <img
              src="https://via.placeholder.com/400x300"
              alt="Project 2"
              class="img-fluid rounded shadow"
            />
            <p class="text-center mt-2">Project 2</p>
          </div>
          <div class="col-md-4">
            <img
              src="https://via.placeholder.com/400x300"
              alt="Project 3"
              class="img-fluid rounded shadow"
            />
            <p class="text-center mt-2">Project 3</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-5 bg-light text-center">
      <div class="container">
        <h2>Testimonials</h2>
        <div class="row mt-4">
          <div class="col-md-4">
            <blockquote class="blockquote">
              <p class="mb-0">
                "Gabriel's work is outstanding. My business has never looked so
                professional!"
              </p>
              <footer class="blockquote-footer">Client A</footer>
            </blockquote>
          </div>
          <div class="col-md-4">
            <blockquote class="blockquote">
              <p class="mb-0">
                "Amazing skills and incredible attention to detail. Highly
                recommended!"
              </p>
              <footer class="blockquote-footer">Client B</footer>
            </blockquote>
          </div>
          <div class="col-md-4">
            <blockquote class="blockquote">
              <p class="mb-0">
                "Delivered on time and exceeded expectations. I couldn't be
                happier!"
              </p>
              <footer class="blockquote-footer">Client C</footer>
            </blockquote>
          </div>
        </div>
      </div>
    </section>

    <!-- Call-to-Action Section -->
    <section
      id="contact"
      class="cta-section bg-primary text-white py-5 text-center"
    >
      <div class="container">
        <h2>Contact Me</h2>
        <form class="mt-4">
          <div class="row">
            <div class="col-md-6 mb-3">
              <input
                type="text"
                class="form-control"
                placeholder="Your Name"
                required
              />
            </div>
            <div class="col-md-6 mb-3">
              <input
                type="email"
                class="form-control"
                placeholder="Your Email"
                required
              />
            </div>
          </div>
          <textarea
            class="form-control mb-3"
            rows="4"
            placeholder="Your Message"
            required
          ></textarea>
          <button type="submit" class="btn btn-light btn-lg">
            Send Message
          </button>
        </form>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer bg-dark text-white text-center py-3">
      <div class="container">
        <p>&copy; 2024 Gabriel's Portfolio. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<style>
.hero-section {
  height: 100vh;
  background: url("https://via.placeholder.com/1920x1080") no-repeat center
    center/cover;
}
</style>
