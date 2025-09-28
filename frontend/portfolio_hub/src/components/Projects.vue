<template>
  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="grid">
      <div class="card">
        <h3>Project 1</h3>
        <p>Short description of project 1.</p>
        <a href="#" target="_blank" class="btn">🔗 View More</a>
      </div>
      <div class="card">
        <h3>Project 2</h3>
        <p>Short description of project 2.</p>
        <a href="#" target="_blank" class="btn">🔗 View More</a>
      </div>
      <div class="card">
        <h3>Project 3</h3>
        <p>Another interesting project description.</p>
        <a href="#" target="_blank" class="btn">🔗 View More</a>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
.projects {
  text-align: center;
  padding: 4rem 1rem;
  background: #ffffff;
  color: #333;
}

.projects h2 {
  font-size: 2rem;
  margin-bottom: 2rem;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
  gap: 1.5rem;
  max-width: 1000px;
  margin: 0 auto;
}

.card {
  background: #fafafa;
  padding: 1.5rem;
  border: 1px solid #ddd;
  border-radius: 12px;
  text-align: left;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.card:hover {
  transform: translateY(-6px);
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
}

.card h3 {
  margin-top: 0;
  font-size: 1.2rem;
  margin-bottom: 0.5rem;
}

.card p {
  font-size: 0.95rem;
  margin-bottom: 1rem;
  color: #555;
}

.btn {
  display: inline-block;
  padding: 0.5rem 1rem;
  background: #2d6a4f;
  color: white;
  border-radius: 6px;
  font-size: 0.9rem;
  text-decoration: none;
  font-weight: 600;
  transition: background 0.2s ease;
}

.btn:hover {
  background: #1b4332;
}
</style>