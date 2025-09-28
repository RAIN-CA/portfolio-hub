<template>
  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p class="email">
      📧 Email: <a href="mailto:me@example.com">me@example.com</a>
    </p>
    <div class="links">
      <a href="https://github.com/yourname" target="_blank">🐙 GitHub</a>
      <a href="https://linkedin.com/in/yourname" target="_blank">💼 LinkedIn</a>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
.contact {
  padding: 3rem 1rem;
  text-align: center;
  background: #f5f5f5;
  color: #333;
}

.contact h2 {
  font-size: 2rem;
  margin-bottom: 1.5rem;
}

.email {
  font-size: 1.1rem;
  margin-bottom: 1.5rem;
}

.links {
  display: flex;
  justify-content: center;
  gap: 2rem;
}

.links a {
  text-decoration: none;
  font-weight: 600;
  color: #2d6a4f;
  font-size: 1.1rem;
  transition: color 0.2s, transform 0.2s;
}

.links a:hover {
  color: #1b4332;
  transform: translateY(-2px);
}
</style>