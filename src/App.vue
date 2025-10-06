<template>
  <HeaderSection/>
  <router-view></router-view>
  <FooterSection />
</template>

<script setup>
import FooterSection from "./components/sections/FooterSection.vue";
import HeaderSection from "./components/sections/HeaderSection.vue";
</script>

<style scoped>
/* Navbar stylings */
/* navbar 1 */
.navbar-overall-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 999;
}

.navbar-list {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  text-align: center;
  gap: 15px;
  background-color: #f2f2f2;
  padding: 5px 20px;
}

.navbar-list p {
  font-size: 20px;
  font-weight: 600;
  margin: 0;
}

.list-1 {
  background: none;
  border: none;
  font-size: 12px;
}

.list-1 a {
  color: #000000;
  text-decoration: none;
}

.navbar-lists {
  display: flex;
  gap: 20px;
}

.list-2 {
  background: none;
  border: none;
  color: #000000;
  font-size: 15px;
}

.list-2 a {
  color: #000000;
  text-decoration: none;
}

.list-2 a:hover {
  color: #000000;
  font-weight: 550;
}

/* navbar 2 */
.navbar {
  display: flex;
  /* justify-content: center; */
  align-items: center;
  text-align: center;
  background-color: #dedede;
  padding: 5px 20px;
}

.logo {
  display: flex;
  justify-content: start;
  align-items: center;
  gap: 10px;
  padding: 0 20px 0 20px;
}

.logo img {
  height: 50px;
  width: 50px;
}

.list-3 {
  background: none;
  border: none;
  font-size: 16px;
  font-weight: 600;
}

.list-3 a {
  color: #000000;
  text-decoration: none;
  margin: 0;
}

.logo-list {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  padding: 0 25% 0 0;
  gap: 13px;
  position: relative;
}

/* ========== Nav links ========== */
.list-4 {
  position: relative;
  font-size: 16px;
  font-weight: 600;
  color: #000;
  text-decoration: none;
  transition: color 0.3s ease;
  /* padding: 0 10px; */
}

.list-4::before {
  content: "";
  position: absolute;
  width: 0%;
  height: 2px;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  background-color: #0025b9;
  transition: width 0.3s ease;
}

.list-4:hover::before {
  width: 100%;
}

.list-4:hover {
  color: #0025b9;
}

/* ========== Dropdown styling ========== */
.dropdown {
  position: relative;
}

.dropbtn {
  color: #000;
  text-decoration: none;
  font-weight: 600;
}

.dropdown-content {
  position: absolute;
  top: 100%;
  left: 0;
  background: #dedede;
  border: none;
  border-radius: 5px;
  border-top-left-radius: 0;
  border-top-right-radius: 0;
  min-width: 180px;
  display: none;
  flex-direction: column;
  box-shadow: 0px 10px 25px rgba(0, 0, 0, 0.1);
  z-index: 99;
  opacity: 0;
  transform: translateY(10px);
  transition: opacity 0.3s ease, transform 0.3s ease;
}

.dropdown-content a {
  padding: 8px 10px;
  color: #000000;
  text-decoration: none;
  white-space: nowrap;
  transition: background 0.3s;
  font-size: 10px;
}

.dropdown-content a:hover {
  background-color: #f5f5f5;
  color: #0025b9;
}

/* Hover logic */
.dropdown:hover .dropdown-content {
  display: flex;
  opacity: 1;
  transform: translateY(0);
}

.card-text {
  margin: 5px 0;
}
.card-title {
  margin: 8px 0;
}

.card-btn-body {
  margin: 0 0 30px 0;
}

.card-btn-body a {
  border-radius: 20px;
  background-color: transparent;
  border: 2px solid #ffffff;
  color: #ffffff;
  font-size: 13px;
  padding: 8px 20px;
  margin: 0;
}
</style>
