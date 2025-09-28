<template>
  <section id="hero" class="hero">
    <h1>Hello, I’m <span class="highlight">Mao Yuhui</span> 👋</h1>
    <h2>MSc @ NTU · Robotics & Autonomous Systems</h2>
    <p>
      Exploring <strong>robotics</strong>, <strong>autonomy</strong>, and
      <strong>AI-driven control systems</strong>.
    </p>
    <div class="buttons">
      <a class="btn primary" href="/resume.pdf" target="_blank">📄 View Resume</a>
      <a class="btn secondary" href="#contact">✉️ Contact Me</a>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
.hero {
  text-align: center;
  padding: 6rem 1rem 4rem;
  background: linear-gradient(120deg, #d4fc79, #96e6a1);
  color: #222;
}

.hero h1 {
  font-size: 2.8rem;
  margin-bottom: 1rem;
}

.hero h2 {
  font-size: 1.5rem;
  font-weight: 400;
  margin-bottom: 1rem;
  color: #444;
}

.hero p {
  font-size: 1.1rem;
  margin-bottom: 2rem;
}

.highlight {
  color: #2d6a4f;
  font-weight: 700;
}

.buttons {
  display: flex;
  justify-content: center;
  gap: 1rem;
  flex-wrap: wrap; /* 小屏幕自动换行 */
}

.btn {
  text-decoration: none;
  padding: 0.7rem 1.5rem;
  border-radius: 6px;
  font-weight: 600;
  transition: all 0.2s ease-in-out;
}

.btn.primary {
  background: #2d6a4f;
  color: white;
}

.btn.primary:hover {
  background: #1b4332;
}

.btn.secondary {
  background: white;
  color: #2d6a4f;
  border: 2px solid #2d6a4f;
}

.btn.secondary:hover {
  background: #e9f5ec;
}

/* 响应式 - 小屏优化 */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 2rem;
  }
  .hero h2 {
    font-size: 1.2rem;
  }
  .hero p {
    font-size: 1rem;
  }
}
</style>