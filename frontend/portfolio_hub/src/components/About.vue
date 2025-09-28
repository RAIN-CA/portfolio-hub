<template>
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      I am an MSc student specializing in 
      <strong>Robotics</strong> & 
      <strong>End-to-End Autonomous Systems</strong>.  
      Passionate about bridging simulation and real-world robotics 
      with AI-driven methods.
    </p>
    <h3>Skills</h3>
    <ul class="skills">
      <li>⚙️ Python</li>
      <li>🤖 ROS2</li>
      <li>🌐 Vue</li>
      <li>🔥 Flask</li>
    </ul>
  </section>
</template>

<script setup></script>

<style scoped>
.about {
  text-align: center;
  padding: 4rem 1rem;
  background: #f9f9f9;
  color: #333;
}

.about h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.about p {
  font-size: 1.1rem;
  max-width: 700px;
  margin: 0 auto 2rem;
  line-height: 1.6;
}

.about h3 {
  margin-top: 2rem;
  font-size: 1.3rem;
}

.skills {
  display: flex;
  flex-wrap: wrap;     /* 小屏幕自动换行 */
  justify-content: center;
  gap: 0.8rem;
  margin-top: 1rem;
  padding: 0;
  list-style: none;
}

.skills li {
  background: #e0f7fa;
  color: #006064;
  padding: 0.5rem 1rem;
  border-radius: 20px;  /* 圆角标签风格 */
  font-weight: 500;
  font-size: 0.95rem;
  transition: all 0.2s ease-in-out;
}

.skills li:hover {
  background: #b2ebf2;
  transform: translateY(-2px); /* hover 时微微上浮 */
}
</style>