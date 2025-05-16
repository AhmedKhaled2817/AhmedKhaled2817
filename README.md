from pathlib import Path

# محتوى ملف README.md بعد التعديل الأخير
readme_content = """
<h1 align="center">Hi 👋, I'm Ahmed Khaled</h1>
<h3 align="center">A passionate Front-End Angular Developer from Egypt</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ahmedkhaled2817&label=Profile%20views&color=0e75b6&style=flat" alt="ahmedkhaled2817" />
</p>

---

- 🌱 I’m currently learning **advanced Angular, TypeScript, and UI/UX best practices**

- 👨‍💻 All of my projects are available at [My GitHub Projects](https://github.com/AhmedKhaled2817?tab=repositories)

- 💬 Ask me about **Angular, HTML, CSS, Bootstrap, JavaScript**

- 📫 How to reach me: **youremail@example.com**

- ⚡ Fun fact: I love building pixel-perfect UIs and solving real-world problems!

---

### 🛠️ Languages and Tools:

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" alt="angular" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="js" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="html5" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="css3" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="bootstrap" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="github" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/>
</p>

---

### 📈 GitHub Stats:

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ahmedkhaled2817&show_icons=true&locale=en" alt="ahmedkhaled2817" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=ahmedkhaled2817&show_icons=true&locale=en&layout=compact" alt="Top Languages" />
</p>

---

### 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ahmedkhaled2817&theme=gruvbox&column=7" alt="trophies"/>
</p>

---

### 📌 Featured Projects:

- 🔹 [Bank Management System - C++](https://github.com/AhmedKhaled2817/Bank-Management-System)
- 🔹 [Library Management System - C++](https://github.com/AhmedKhaled2817/Library-Management-System)
- 🔹 [50 Project - HTML, CSS, JS](https://github.com/AhmedKhaled2817/50-Project-HTML-CSS-JS)

---

### 🔗 Connect with me:

<p align="left">
  <a href="https://linkedin.com/in/YOUR-LINKEDIN" target="blank"><img align="center" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="linkedin" height="30" width="30" /></a>
  <a href="mailto:youremail@example.com"><img align="center" src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="email" height="30" width="30" /></a>
</p>
"""

# حفظ الملف
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content.strip())

readme_path.name
