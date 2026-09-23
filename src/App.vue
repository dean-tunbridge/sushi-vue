<script setup lang="ts"></script>

<template>
  <header>
    <nav class="header__nav">
      <div class="header__logo">
        <h4>SUSHIBONSON</h4>
        <div class="header__logo-overlay"></div>
      </div>

      <ul class="header__menu">
        <li>
          <a href="#Menu">Menu</a>
        </li>
        <li>
          <a href="#Food">Food</a>
        </li>
        <li>
          <a href="#Servcies">Servcies</a>
        </li>
        <li>
          <a href="#About-us">About Us</a>
        </li>
        <li>
          <img src="/assets/search.svg" alt="search" />
        </li>
      </ul>

      <ul class="header__menu-mobile">
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
  font-family: var(--playfair-display);
  color: #fff;
  opacity: 0.8;
}
</style>
