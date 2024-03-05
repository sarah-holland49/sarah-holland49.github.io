<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <header>
      <nav>
        <ul>
          <li><a href="#">Portfolio</a></li>
          <li><a href="#">About me</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="home">
        <h1>Sarah Holland</h1>
      </section>
      <section id="Home">
        <h2>Home</h2>
        <ul>
          <li><a href="#">Digital art</a></li>
          <li><a href="#">Photography</a></li>
        </ul>
      </section>
      <section id="about-me">
        <h2>About me</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla condimentum libero nec lorem bibendum, non dictum quam ultricies. Vivamus sed imperdiet nibh, eu maximus felis.</p>
        <img src="my-photo.jpg" alt="My photo">
      </section>
      <section id="contact">
        <h2>Contact</h2>
        <form action="#">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name">
          <label for="email">Email:</label>
          <input type="email" id="email" name="email">
          <label for="message">Message:</label>
          <textarea id="message" name="message"></textarea>
          <button type="submit">Send</button>
        </form>
        <div class="contact-box">
          <p>Don't hesitate to contact me!</p>
        </div>
      </section>
    </main>
    <footer>
      <ul class="social-media">
        <li><a href="#"><img src="fb-logo.png" alt="Facebook"></a></li>
        <li><a href="#"><img src="insta-logo.png" alt="Instagram"></a></li>
        <li><a href="#"><img src="email-logo.png" alt="Email"></a></li>
      </ul>
    </footer>
  </div>
</body>
</html>
