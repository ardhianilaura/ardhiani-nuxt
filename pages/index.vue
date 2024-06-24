<template>
  <div>
    <nav class="justify-content-end">
      <div class="nav-item">
        <a class="nav-link" href="home.html">Home</a>
      </div>
      <div class="nav-item">
        <a class="nav-link" href="about.html">About</a>
      </div>
      <div class="nav-item">
        <a class="nav-link" href="menu.html">Menu</a>
      </div>
      <div class="nav-item">
        <a class="nav-link" href="chef.html">Chef</a>
      </div>
      <div class="nav-item">
        <a class="nav-link" href="blog.html">Blog</a>
      </div>
      <div class="nav-item">
        <a class="nav-link" href="contact.html">Contact</a>
      </div>
    </nav><br>
    <div class="col-6 col-s-9">
      <img src="">
    </div>
  </div>
</template>

<script>

export default {
  name: 'ArdhianiNuxt',


}
</script>

<style>
*{
  padding: 0;
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

nav {
  background-color: #ffffff;
  border-bottom: 1px solid #E7E6E1;
  display: flex;
}

.nav-item {
  position: relative;
}

.nav-link {
  display: block;
  padding: 20px 15px;
  margin: 0;
  color: #314E52;
  text-decoration: none;
}

.nav-item:hover .nav-dropdown {
  display: block;
}

.nav-dropdown {
  position: absolute;
  display: none;
  z-index: 999;
  top: 58px;
  left: px;
  width: 200px;
  padding-bottom: 10px;
  border-radius: 3px;
  background-color: #fff;
  border: 1px solid #E8E8E8;
}

.nav-dropdown a {
  display: block;
  padding: 10px;
  color: #314E52;
  text-decoration: none;
}

.nav-dropdown a:hover {
  background-color: #ffffff;
}
</style>