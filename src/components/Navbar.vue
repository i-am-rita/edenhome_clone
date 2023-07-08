<template>
  <nav class="navbar">
    <img
      src="https://res.cloudinary.com/eden-life-inc/image/upload/v1611230252/eden-website-v2/eden-logo_lcepc6.svg"
    />
    <ul class="nav-list">
      <li>Why Eden</li>
      <li>Services</li>
      <li>Companies</li>
      <li>Pricing</li>
      <li>Contact Us</li>
      <li class="btn">Get Started</li>
      <li>✔️</li>
    </ul>
  </nav>
</template>

<script>
</script>

<style scoped>
.navbar {
  display: flex;
  align-items: center;

  width: 83%;
  padding: 20px 0 0 0;
  margin: 0 auto !important;
}

img {
  margin-right: 100px;
}
ul {
  list-style-type: none;

  display: flex;
  justify-content: space-around;
  align-items: center;

  width: 100%;
}

li {
  line-height: 24px;
  font-size: 1rem;
  font-weight: 500;
  color: #21312a;
  cursor: pointer;
}

li:hover {
  color: #4caf50;
}

.btn {
  background-color: #4caf50;
  border: none;
  border-radius: 5px;
  color: white;
  padding: 10px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-flex;
  font-size: 16px;
  cursor: pointer;
}
</style>