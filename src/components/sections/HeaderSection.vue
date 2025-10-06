<template>
  <nav class="navbar navbar-expand-lg d-none d-lg-block bg-body-tertiary">
    <div class="container-fluid">
      <router-link class="navbar-brand d-flex justify-content-start">
        <img
          src="/src/Assets/image/DBDM.png"
          alt="DBDM"
          class="logoImage d-lg-none"
        />
      </router-link>
      <button
        class="navbar-toggler border-0 p-0"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <router-link to="/" class="nav-link active text-dark"
              >FIND A CHURCH</router-link
            >
          </li>
          <li class="nav-item d-md-block">
            <router-link to="/" class="nav-link active text-dark"
              >|</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/" class="nav-link active text-dark"
              >DBDM</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/course" class="nav-link active text-dark"
              >JESUS</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/about" class="nav-link active text-dark"
              >COLLEGE</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/pricing" class="nav-link active text-dark"
              >MUSIC</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/contact" class="nav-link active text-dark"
              >CONFERENCE</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/contact" class="nav-link active text-dark"
              >STORE</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/contact" class="nav-link active text-dark"
              >BLOG</router-link
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="container m-0">
    <nav class="navbar navbar-expand-lg bg-body-tertiary align-items-center d-flex p-0">
      <router-link
        class="navbar-brand d-flex align-items-center justify-content-center"
      >
        <img src="/src/Assets/image/DBDM.png" alt="DBDM" class="logoImage" />
        <p class="mb-0 ms-2 logoText">DAY BY DAY MINISTRY</p>
      </router-link>
      <button
        class="navbar-toggler border-0 p-0 m-0 mt-1"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent fs-2"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        MENU
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <img src="...." alt="" class="img-fluid" />
            <router-link to="/" class="nav-link active text-dark"></router-link>
          </li>
          <li class="nav-item">
            <router-link to="/" class="nav-link active text-dark"
              >ABOUT</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/course" class="nav-link active text-dark"
              >LOCATION</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/about" class="nav-link active text-dark"
              >SERMON</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/pricing" class="nav-link active text-dark"
              >CONFERENCES</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/contact" class="nav-link active text-dark"
              >SCHOOL</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/contact" class="nav-link active text-dark"
              >TESTIMONIES</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/contact" class="nav-link active text-dark"
              >ONLINE</router-link
            >
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.logoImage {
  width: 30px;
  height: 30px;
}
.logoText {
  font-size: 13px;
  font-weight: 700;
}
.navbar-toggler {
  font-size: 13px;
  font-weight: 700;
  color: #000000;
  border-color: none;
}
</style>
