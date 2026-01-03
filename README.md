<div align="center">

<!-- Animated Title with Gradient -->
<span style="background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1, #f9ca24, #f0932b); background-size: 400% 400%; animation: gradientShift 3s ease-in-out infinite;">Sayed Mirchoni</span>
<br><br>

<!-- Particle Background Effect -->
<div style="position: relative; overflow: hidden;">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: 
    radial-gradient(circle at 20% 50%, rgba(120,119,198,0.3) 0%, transparent 50%),
    radial-gradient(circle at 80% 20%, rgba(255,119,198,0.3) 0%, transparent 50%),
    radial-gradient(circle at 40% 80%, rgba(120,219,255,0.3) 0%, transparent 50%);
    animation: particleFloat 20s ease-in-out infinite;">
  </div>
</div>

<!-- Animated Profile Stats -->
<div style="background: rgba(15, 15, 25, 0.95); backdrop-filter: blur(20px); border-radius: 20px; padding: 30px; margin: 20px 0; border: 1px solid rgba(255,255,255,0.1); box-shadow: 0 20px 40px rgba(0,0,0,0.3);">
  
  ### 🚀 About Me
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin: 20px 0;">
    
    <div style="text-align: left;">
      🔭 **Web Enthusiast**<br>
      👯 Looking to collaborate on **dynamic web projects**<br>
      🌱 Currently learning **Firebase & Next.js**<br>
      💬 Ask me about **React, Java, Python, Full-Stack**<br>
      ⚡ **1 Cup ☕ = 2 Hours of Code**
    </div>
    
    <!-- Dynamic Typing Effect -->
    <div style="text-align: left;">
      <span id="typed-text" style="font-weight: bold; color: #4ecdc4; font-size: 1.2em;"></span>
      <script>
        const texts = ["Full-Stack Developer", "React Enthusiast", "Backend Architect", "Firebase Expert", "Code Artist"];
        let index = 0;
        let charIndex = 0;
        let forward = true;
        function typeWriter() {
          const element = document.getElementById('typed-text');
          if (forward) {
            element.textContent = texts[index].slice(0, charIndex);
            charIndex++;
            if (charIndex > texts[index].length) {
              forward = false;
              setTimeout(typeWriter, 1000);
            } else {
              setTimeout(typeWriter, 100);
            }
          } else {
            element.textContent = texts[index].slice(0, charIndex);
            charIndex--;
            if (charIndex < 0) {
              forward = true;
              index = (index + 1) % texts.length;
              setTimeout(typeWriter, 500);
            } else {
              setTimeout(typeWriter, 50);
            }
          }
        }
        typeWriter();
      </script>
    </div>
  </div>
</div>

<!-- Glowing Social Badges -->
## 🌐 Connect With Me
<div style="display: flex; gap: 15px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <a href="https://instagram.com/Xtremer_25">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white&style=for-the-badge" 
         style="animation: badgeGlow 2s ease-in-out infinite alternate; box-shadow: 0 0 20px rgba(228,64,95,0.5);">
  </a>
  <a href="https://linkedin.com/in/sayed-mirchoni">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white&style=for-the-badge" 
         style="animation: badgeGlow 2s ease-in-out infinite alternate; box-shadow: 0 0 20px rgba(0,119,181,0.5);">
  </a>
  <a href="mailto:www.naayaab2004@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white&style=for-the-badge" 
         style="animation: badgeGlow 2s ease-in-out infinite alternate; box-shadow: 0 0 20px rgba(209,72,54,0.5);">
  </a>
</div>

<style>
@keyframes gradientShift {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
@keyframes particleFloat {
  0%, 100% { transform: translateY(0px) rotate(0deg); }
  50% { transform: translateY(-20px) rotate(180deg); }
}
@keyframes badgeGlow {
  from { filter: drop-shadow(0 0 5px currentColor); }
  to { filter: drop-shadow(0 0 20px currentColor); }
}
</style>

<!-- Interactive Tech Stack with Categories -->
## 🛠️ Tech Arsenal
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px;">

  ### 🌐 Frontend
  <div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
    ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
    ![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
    ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
    ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
    ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
  </div>

  ### ⚙️ Backend
  <div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
    ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
    ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
    ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
    ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
    ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
  </div>

  ### 🗄️ Database
  <div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
    ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
    ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
    ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase&logoColor=white)
  </div>

  ### 📱 Mobile & Deployment
  <div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
    ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
    ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
    ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
    ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
  </div>
</div>

<!-- Live GitHub Stats -->
## 📊 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Xtremer25&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=f0f6fc&text_color=f0f6fc" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Xtremer25&layout=compact&theme=radical&hide_border=true&bg_color=0d1117" />
</div>

<!-- Skills Radar Chart -->
## 🎯 Skills Radar
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=Xtremer25&layout=card&langs_count=7&theme=radical&border_radius=12" />
</div>

<!-- Featured Projects -->
## 🔥 Featured Projects
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin: 30px 0;">

  <div style="background: rgba(20, 20, 40, 0.8); padding: 20px; border-radius: 15px; border: 1px solid rgba(100,200,255,0.2); transition: all 0.3s ease;">
    <h3>🚀 Portfolio Website</h3>
    <p>Modern responsive portfolio built with React, TailwindCSS & Framer Motion</p>
    <div style="display: flex; gap: 10px; margin-top: 10px;">
      ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB?style=social)
      ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white?style=social)
    </div>
  </div>

  <div style="background: rgba(20, 20, 40, 0.8); padding: 20px; border-radius: 15px; border: 1px solid rgba(100,200,255,0.2); transition: all 0.3s ease;">
    <h3>📱 E-Commerce App</h3>
    <p>Full-stack e-commerce platform with Firebase backend & Stripe integration</p>
    <div style="display: flex; gap: 10px; margin-top: 10px;">
      ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase&logoColor=white?style=social)
      ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB?style=social)
    </div>
  </div>

</div>

<!-- Streak Stats -->
## 🔥 Current Streak
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Xtremer25&theme=radical&hide_border=true" />
</div>

### ✍️ Random Dev Quote
> "Code is like humor. When you have to explain it, it's bad." – Cory House

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Xtremer25&color=4ecdc4&style=flat-square" />
</div>

<!-- GitHub Profile Trophy -->
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Xtremer25&theme=radical&no-frame=true&no-bg=true&margin-w=4" />
</div>

</div>

<script>
// Hover effects for project cards
document.querySelectorAll('[style*="background: rgba(20, 20, 40"]').forEach(card => {
  card.style.cursor = 'pointer';
  card.addEventListener('mouseenter', function() {
    this.style.transform = 'translateY(-10px) scale(1.02)';
    this.style.boxShadow = '0 25px 50px rgba(0,0,0,0.4)';
  });
  card.addEventListener('mouseleave', function() {
    this.style.transform = 'translateY(0) scale(1)';
    this.style.boxShadow = '0 10px 30px rgba(0,0,0,0.2)';
  });
});
</script>

---
*⭐ Star this repository if you found it helpful!*
