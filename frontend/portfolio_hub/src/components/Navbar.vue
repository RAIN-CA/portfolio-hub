<template>
  <nav class="navbar">
    <div class="logo">Portfolio Hub</div>
    <div class="menu-container">
      <ul>
        <li><a href="#hero">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <div class="menu-spacer"></div>
    </div>
  </nav>
</template>

<script setup></script>

<style scoped>
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background: #f5f5f5;
  z-index: 1000;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

.logo {
  font-weight: 700;
  font-size: 1.4rem;
  letter-spacing: 1px;
  color: #222;
}

.menu-container {
  flex: 1;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

ul {
  list-style: none;
  display: flex;
  gap: 2rem;
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
  color: #333;
  font-weight: 500;
  transition: color 0.2s;
}

a:hover {
  color: #646cff;
}

.menu-spacer {
  width: 5rem; /* 控制右侧留白 */
}
</style>