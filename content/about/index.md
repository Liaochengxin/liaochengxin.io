---
title: "About"
date: 2024-03-19
draft: false
description: "About Chengxin Liao"
---

<style>
  h3 {
    font-size: 1.8rem;
    font-family: Montserrat, serif !important;
    color: #4a5a7a;
  }
</style>


<!-- Swiper CSS -->
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css"
/>
<!-- Swiper JS -->
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

<style>
/* 让 Swiper 的箭头变成半透明白色 */
.swiper-button-next,
.swiper-button-prev {
  color: rgba(255,255,255,0.7);   /* 半透明白色 */
  background: rgba(0,0,0,0.15);   /* 可选：加点黑色半透明背景让箭头更清晰 */
  border-radius: 50%;
  width: 40px;
  height: 40px;
  transition: background 0.2s, color 0.2s;
}
.swiper-button-next:hover,
.swiper-button-prev:hover {
  color: #fff;
  background: rgba(0,0,0,0.3);
}
.swiper-button-next::after,
.swiper-button-prev::after {
  font-size: 20px;
}
</style>

<div class="about-container">

<div class="about-text">

### Biography 

I am currently pursuing my Master's degree at the **Institute of High-Energy Physics**, Chinese Academy of Sciences in Beijing.  
As a member of the **ATLAS collaboration**, my research focuses on searches for supersymmetric particles and other Beyond-the-Standard-Model (BSM) phenomena.

I am also deeply interested in **machine learning applications** in high-energy physics.  
For more details about my academic background and research experience, please refer to my Curriculum Vitae.

---

### Education

- **2021-2025**, Department of Physics, Shandong University, *Bachelor of Science (BS)*
- **2025-present**, Institute of High-Energy Physics(IHEP), Chinese Academy of Sciences(CAS), *Master of Science(MSc)*

  **Supervisor**: Xuai Zhuang

---

### Research Interests

- Experimental High-Energy Physics  
- Machine Learning in HEP-EX

---

### Contact

- Email: [liaocx@ihep.ac.cn](mailto:liaocx@ihep.ac.cn)

<div class="swiper" style="width: 320px; max-width: 100%;">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="static/home/IMG_5229.JPG" alt="Photo 1" style="width: 100%; border-radius: 8px;">
    </div>
    <div class="swiper-slide">
      <img src="static/home/111.png" alt="Photo 2" style="width: 100%; border-radius: 8px;">
    </div>
    <div class="swiper-slide">
      <img src="static/home/me.jpg" alt="Photo 3" style="width: 100%; border-radius: 8px;">
    </div>
  </div>
  <!-- 如果需要导航按钮 -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    new Swiper('.swiper', {
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      },
      slidesPerView: 1,
      spaceBetween: 16,
      loop: true,
    });
  });
</script>

</div>

</div>

