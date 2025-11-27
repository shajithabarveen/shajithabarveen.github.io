---
title: Portfolio

layout: default



---
<button id="theme-toggle" style="
  padding: 10px 18px;
  font-size: 14px;
  margin-bottom: 15px;
  cursor: pointer;
  border-radius: 6px;
  border: none;
  background: #444;
  color: white;
">
 🌙 Toggle Dark Mode
</button>

<script src="/assets/js/theme-toggle.js"></script>
<link rel="stylesheet" href="/assets/css/style.css">


# 👋 Hi, I'm Shajitha Barveen

I'm a **Computer Science Engineer** and aspiring **Data Analyst** with skills in:

- Python (Pandas, NumPy)
- SQL (MySQL)
- Tableau & Power BI
- Excel
- HTML, CSS, Core Java

I enjoy exploring data, solving meaningful problems, and building dashboards that help decision-making.

---
---
---


### 🔍 Explore My Portfolio

- 📁 [Projects](projects.md)
- 📄 [Resume](resume.md)
- 👤 [About Me](about.md)
- ✉️ [Contact](contact.md)

<script>
document.querySelectorAll("h1, h2, h3, p, .card").forEach(el => {
  el.style.opacity = 0;
  el.style.transform = "translateY(20px)";
  el.style.transition = "all 0.6s ease";

  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.style.opacity = 1;
        entry.target.style.transform = "translateY(0)";
      }
    });
  });

  observer.observe(el);
});
</script>



