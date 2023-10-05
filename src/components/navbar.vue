<script setup></script>

<template>
  <div class="Navbar">
    <div class="Welcom">Welcome To MyWebsite</div>
    <div class="menu">
      <div class="box">
        <a href="#about">About Me</a>
      </div>
      <div class="box">
      <a href="#skills">Skills</a>
    </div>
    <div class="box">
      <a href="#activity">Activities</a>
    </div>
    </div>
  </div>
</template>

<style scoped>
.Navbar {
  display: flex;
  position: relative;
  height: 80px;
  background-color: linear-gradient(
    90deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(9, 17, 121, 1) 42%,
    rgba(2, 0, 36, 1) 100%
  );
  align-items: center;
}

.menu {
  position: absolute;
  right: 25px;
  display: flex;
  gap: 35px;
}
.Welcom {
  padding: 0 0 0 10px; /*บน ขวา ล่าง ซ้าย*/
}
a {
  text-decoration: none;
  color: white;
}
.box{
  height: 30px;
  width: 80px;
  background-color: rgb(59, 172, 238);
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center ;
}
.box:hover{
  background-color: black;
}
.box a:hover{
  color: #FF9900;
}
</style>
