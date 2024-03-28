<template>
  <div class="main-content">
    <h1>Heading</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    <div class="buttons">
      <button>Contact</button>
      <button>Offerte</button>
    </div>
    <div class="image-placeholder">Afbeelding</div>
    <div class="content-box">Websites laten maken?</div>
    <div class="content-box">Contact</div>
    <div class="content-box">Tarieven</div>
  </div>
</template>

<style scoped>
.main-content {
  text-align: center;
}

.buttons {
  display: flex;
  justify-content: center;
  gap: 1rem;
  padding: 1rem 0;
}

button {
  padding: 0.5rem 1rem;
  border: 1px solid #000;
  background: none;
}

.image-placeholder {
  margin: 1rem auto;
  width: 60%;
  height: 150px;
  background-color: #ddd;
  border: 1px solid #000;
}

.content-box {
  border: 1px solid #000;
  margin: 1rem;
  padding: 1rem;
  text-align: center;
}
</style>
