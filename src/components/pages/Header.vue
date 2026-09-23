<script setup lang="ts"></script>

<template>
  <header>
    <nav class="header__nav">
      <div class="header__logo">
        <h4>寿司 sushi<br />ボンソン Bonson</h4>
        <div class="header__logo-overlay"></div>
      </div>

      <ul class="header__menu" data-aos="fade-down">
        <li>
          <a href="#Menu">Menu</a>
        </li>
        <li>
          <a href="#Food">Food</a>
        </li>
        <li>
          <a href="#Services">Services</a>
        </li>
        <li>
          <a href="#About-us">About Us</a>
        </li>
        <li>
          <img src="/assets/search.svg" alt="search" />
        </li>
      </ul>

      <ul class="header__menu-mobile" data-aos="fade-down">
        <img src="/assets/menu.svg" alt="menu" />
      </ul>
    </nav>
  </header>
</template>

<style lang="css" scoped>
.header__nav {
  display: flex;
  overflow: hidden;
}

.header__logo {
  flex: 1;
  display: flex;
  position: relative;
  padding: 20px;
}

.header__logo-overlay {
  position: absolute;
  inset: 0;
  width: 100%;
  background-color: var(--primary-color);
  z-index: -1;
}

.header__logo h4 {
  padding-left: 30px;
  font-weight: 700;
  font-size: 24px;
  text-transform: uppercase;
  font-family: 'Dela Gothic One', sans-serif;
  color: #fff;
  opacity: 0.8;
}

.header__menu,
.header__menu-mobile {
  padding: 20px;
  flex: 1.236;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  gap: 64px;
  list-style: none;
}

.header__menu li {
  font-weight: 500;
  font-family: var(--plus-jakarta-sans);
  color: var(--secondary-color);
  font-size: 16px;
  text-transform: uppercase;
  line-height: 20px;
  cursor: pointer;
}

.header__menu li img {
  width: 24px;
  height: 24px;
  object-fit: contain;
}

.header__menu-mobile {
  display: none;
  gap: 20px;
  position: relative;
}
</style>
