<template>
  <div class="home-container">
    <div class="right-container">
      <h1>Say goodbye to <br />long cooking hours <br />forever</h1>
      <!-- <div> -->

      <li>
        <font-awesome-icon icon="fa-solid fa-period" />Chef-cooked meals:
        delivered fresh. ✔️
      </li>
      <li>
        <font-awesome-icon icon="fa-solid fa-period" />Laundry: picked up and
        delivered. ✔️
      </li>
      <li>
        <font-awesome-icon icon="fa-solid fa-period" />Home cleaning: executed
        by professional cleaners. ✔️
      </li>

      <p>Schedule them, and never worry about them again. Ever.</p>

      <!-- </div> -->
      <div class="watch-video">
        <button>I want an easy life</button>
        <p>✔️ Watch the video</p>
      </div>
    </div>

    <div class="left-container">
      <img
        class="image1"
        src="https://res.cloudinary.com/eden-life-inc/image/upload/q_auto/v1611303384/eden-website-v2/hero-phone_hmfvpb.svg"
        alt="phone"
      />
      <img
        class="image2"
        src="https://ouredenlife.com/_nuxt/img/hero-cleaning.1045270.svg"
        alt="phone"
      />
    </div>
  </div>
</template>

<script>
</script>

<style>
.home-container {
  background-color: #fff9f5;
  height: 85vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 83%;
  margin: 0 auto;
}

.right-container {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.right-container h1 {
  text-align: start;
  line-height: 70px;
  font-size: 3.375rem;
  font-weight: 700;
  color: #203129;

  font-family: "PT Serif", serif;
}

.right-container li {
  /* gap: 100px; */
  margin: 5px 0;
    font-size: 1.125rem;
    color: #203129;
    font-weight: 500;
}

.right-container p{
    font-weight: 500;
    font-size: 1.125rem;
    line-height: 29px;
    margin: 20px 0 20px 0px;
}

.watch-video {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 20px;
}

.watch-video button {
  background-color: #4caf50;
  border: none;
  border-radius: 4px;
  color: white;
  padding: 20px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-flex;
  font-size: 1.125rem;
  cursor: pointer;
  text-transform: capitalize;
}

.left-container {
  position: relative;
  right: 4%;
  height: 700px;
  flex: 0 0 45%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.left-container .image1 {
  position: absolute;
  bottom: 1%;
  z-index: 2;
}
.left-container .image2 {
  position: absolute;
  bottom: 12%;
  z-index: 1;
}
</style>