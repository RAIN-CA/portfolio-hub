<template>
  <footer class="footer">
    <p>© 2025 Mao Yuhui · Built with Vue + Flask</p>
    <div class="socials">
      <a href="https://github.com/yourname" target="_blank">🐙 GitHub</a>
      <a href="https://linkedin.com/in/yourname" target="_blank">💼 LinkedIn</a>
    </div>
  </footer>
</template>

<script setup></script>

<style scoped>
.footer {
  text-align: center;
  padding: 1.5rem 1rem;
  background: #f0f0f0;
  color: #333;
  font-size: 0.9rem;
  border-top: 1px solid #ddd;
}

.footer p {
  margin: 0.5rem 0;
}

.socials {
  margin-top: 0.5rem;
  display: flex;
  justify-content: center;
  gap: 1.5rem;
}

.socials a {
  text-decoration: none;
  font-weight: 500;
  color: #2d6a4f;
  transition: color 0.2s, transform 0.2s;
}

.socials a:hover {
  color: #1b4332;
  transform: translateY(-2px);
}
</style>