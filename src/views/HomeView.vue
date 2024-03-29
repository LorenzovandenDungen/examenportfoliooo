<template>
    <div class="container">
      <!-- Header with navigation links -->
      <header class="header">
        <nav>
          <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#">Websites</a></li>
            <li><a href="#">Tarieven</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">Offerte</a></li>
          </ul>
        </nav>
      </header>
  
      <!-- Main content area -->
      <div class="main-content">
        <h1>Heading</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        <div class="image-placeholder">Afbeelding</div>
        <div class="buttons">
          <button>Contact</button>
          <button>Offerte</button>
        </div>
        <div class="content-box">
          <h2>Websites laten maken?</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>
        <div class="content-box">
          <h2>Contact</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>
        <div class="content-box">
          <h2>Tarieven</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>
      </div>
  
      <!-- Footer area -->
      <footer class="footer">
        <p>Footer</p>
      </footer>
    </div>
  </template>
  
  <style scoped>
  .container {
    display: grid;
    grid-template-rows: auto 1fr auto;
    height: 100vh;
  }
  
  .header {
    border-bottom: 1px solid #000;
  }
  
  .nav-links {
    display: flex;
    justify-content: space-evenly;
    list-style-type: none;
    margin: 0;
    padding: 0;
  }
  
  .nav-links a {
    text-decoration: none;
  }
  
  .main-content {
    text-align: center;
    padding: 1rem;
  }
  
  .buttons {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin: 1rem 0;
  }
  
  button {
    padding: 0.5rem 1rem;
    border: none;
    background-color: #000;
    color: white;
  }
  
  .image-placeholder {
    margin: 2rem auto;
    width: 80%;
    height: 200px;
    background-color: #ddd;
    border: 1px solid #000;
  }
  
  .content-box {
    border: 1px solid #000;
    margin: 1rem;
    padding: 1rem;
  }
  
  .footer {
    border-top: 1px solid #000;
    text-align: center;
    padding: 0.5rem 0;
  }
  </style>
  