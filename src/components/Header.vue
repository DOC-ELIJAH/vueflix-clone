<template>
<section>
<div class="hero-background">
    <!-- <img src="../assets/hero.jpg" class="hero-background-img" /> -->
    <nav class="nav-items">
      <div class="logo-container">
        <img alt="Vue logo" src="../assets/vueflix.png" class="logo-img" />
      </div>
      <div>
        <button class="vueflix-btn">sign in</button>
      </div>
    </nav>
    
    <div class="header-info">
      <h1>Unlimited movies, TV shows, and more.</h1>
      <h2>Watch anywhere. Cancel anytime.</h2>
      <p>
        Ready to watch? Enter your email to create or restart your membership.
      </p>
      <input type="email" placeholder="Email address" />
      <button class="btn">get started <span><span></span><i class="fa-solid fa-greater-than"></i></span></button>
    </div>
  </div>
  <div>
      
  </div>
</section>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.hero-background {
  width: 100%;
  height: 100vh;
  background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.5)),
    url("../assets/hero.jpg");
  background-repeat: no-repeat;
  background-position: cover;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
.hero-background-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  background: linear-gradient();
}
.nav-items {
  display: flex;
  flex-direction: row;
  align-content: center;
  justify-content: space-between;
  margin: 0 3.5rem;
}
.logo-container {
  height: 45px;
  width: 150px;
}
.logo-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.header-info {
  color: #fff;
  text-align: center;
  position: relative;
  top: 150px;
  max-width: 740px;
  margin: auto;
}
.header-info h1 {
  font-size: 3.125rem;
  max-width: 640px;
  margin: auto;
}
.header-info h2 {
  font-weight: 300;
  margin: 20px auto;
}
.header-info input {
  padding: 20px 85px;
  border-radius: 2px;
  border: 1px solid #fff;
  text-align: right;
}
::placeholder {
    text-align: right;
}
.btn {
  padding: 20px 55px;
  border-radius:2px;
  border: 1px solid #fff;
  background: #e50914;
  border: 1px solid #e50914;
  text-transform: capitalize;
  font-weight: 300;
  color: #fff;
}
</style>

