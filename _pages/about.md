---
permalink: /
# تایتل را از اینجا حذف نمی‌کنیم اما در نمایش آن را با CSS مخفی می‌کنیم
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* مخفی کردن تایتل پیش‌فرض قالب در این صفحه خاص */
  .page__title {
    display: none !important;
  }

  /* استایل باکس سرمه‌ای برای تیترهای اصلی */
  .poms-main-header {
    background-color: #0d1b3e;
    color: #f2e3c2;
    padding: 10px 20px;
    border-radius: 4px;
    margin: 10px 0 25px 0; /* فاصله کمتر برای تیتر اول */
    border-left: 8px solid #d4af37;
    font-size: 1.4em;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    display: block;
  }

  /* استایل لیست علایق پژوهشی */
  .interest-list {
    list-style: none;
    padding-left: 0;
    margin-top: 10px;
  }

  .interest-list li {
    padding: 10px 15px;
    margin-bottom: 6px;
    font-size: 0.95em;
    border-radius: 4px 4px 0 0;
    border: 1px solid #d4af37;
    transition: all 0.3s ease;
  }

  .interest-list li:hover {
    transform: translateX(8px);
    background-color: #d4af37;
    border-radius: 4px 4px 0 0;
    border: 1px solid #d4af37;
    color: #0d1b3e;
    border-left-color: #0d1b3e;
  }

  .interest-list i {
    color: #d4af37;
    margin-right: 10px;
    width: 15px;
    text-align: center;
    border-radius: 4px 4px 0 0;
    border: 1px solid #d4af37;
  }
</style>
<style>
  .sdg-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
    gap: 15px;
    margin-top: 20px;
  }

  .sdg-item {
    text-align: center;
    transition: transform 0.3s ease;
    cursor: default;
  }

  .sdg-item:hover {
    transform: scale(1.1);
  }

  .sdg-icon {
    width: 80px;
    height: 80px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-weight: bold;
    font-size: 1.2em;
    margin: 0 auto 5px auto;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  }

  .sdg-count {
    font-size: 0.85em;
    color: var(--primary-color);
    font-weight: bold;
  }

  /* رنگ‌های استاندارد SDG */
  .sdg-12 { background-color: #bf8b2e; } /* Responsible Consumption */
  .sdg-17 { background-color: #19486a; } /* Partnerships */
  .sdg-9  { background-color: #f36d25; } /* Industry & Innovation */
  .sdg-11 { background-color: #f99d26; } /* Sustainable Cities */
  .sdg-8  { background-color: #a21942; } /* Decent Work */
</style>

<div class="poms-main-header" style="margin-top: 50px;">Research Impact: Sustainable Development Goals</div>

<p style="margin-bottom: 25px;">My research contributes to several UN Sustainable Development Goals, specifically focusing on sustainable production and global partnerships.</p>

<div class="sdg-container">
  <div class="sdg-item">
    <div class="sdg-icon sdg-12">12</div>
    <div class="sdg-count">13 Documents</div>
  </div>

  <div class="sdg-item">
    <div class="sdg-icon sdg-17">17</div>
    <div class="sdg-count">10 Documents</div>
  </div>

  <div class="sdg-item">
    <div class="sdg-icon sdg-9">9</div>
    <div class="sdg-count">9 Documents</div>
  </div>

  <div class="sdg-item">
    <div class="sdg-icon sdg-11">11</div>
    <div class="sdg-count">8 Documents</div>
  </div>

  <div class="sdg-item">
    <div class="sdg-icon sdg-8">8</div>
    <div class="sdg-count">6 Documents</div>
  </div>
</div>
<div class="poms-main-header">About Me</div>

I am an early-career scholar in Engineering Management with strong experience in applied research on digital and sustainable engineering systems and in supervising students in project-based learning environments. My work bridges decision analytics, digital transformation, and strategic operations, with a particular focus on [Cloud Supply Chain as a Service](https://www.sciencedirect.com/science/article/abs/pii/S1366554525005824). My research is oriented toward supporting managerial decision-making and strategy formulation in operations-intensive industries.

I introduced the Base-Criterion Method (BCM) in 2020 and the HECON method in 2023, and have further developed advanced decision-analytics frameworks grounded in novel theoretical perspectives. I am also the Lead Editor of two Elsevier books: [Reliable Decision-Making for Sustainable Transportation](https://www.sciencedirect.com/book/edited-volume/9780443337406/reliable-decision-making-for-sustainable-transportation) and the [Encyclopedia of Multi-Attribute Decision-Making (MADM)](https://shop.elsevier.com/books/encyclopedia-of-multi-attribute-decision-making-madm/haseli/978-0-443-33275-3). My research has resulted in more than 25 peer-reviewed journal publications with leading publishers, including Elsevier, Springer, and IEEE, and I have served on scientific committees of several international conferences.

I am currently pursuing my Ph.D. at [Tecnológico de Monterrey](https://tec.mx/en) in Mexico. I have also been involved in international research collaborations, including the Digital Voting Hub for Sustainable Urban Transport Systems (VOTE-TRA) project [No. 22/NCF/DR/11309] funded by Science Foundation Ireland at [University College Dublin](https://www.ucd.ie), and the project Intersectoral and Interdisciplinary Cooperation in Research and Development of Communication and Information Technologies [CZ.02.01.01/00/23_021/0008402] at the [University of Hradec Králové](https://www.uhk.cz/en) in the Czech Republic. My current research aims to bridge decision sciences and cloud-based supply chain systems to support digital transformation, resilience, and intelligent decision support. I am open to international academic and industry collaborations.

<div class="poms-main-header" style="margin-top: 50px;">Research Interests</div>

<ul class="interest-list">
  <li><i class="fas fa-network-wired"></i> Supply Chain Management and Strategic Operations</li>
  <li><i class="fas fa-cloud"></i> Cloud Supply Chain as a Service Risk, Resilience, and Sustainability</li>
  <li><i class="fas fa-microchip"></i> Digital Transformation and Service-Oriented Platforms</li>
  <li><i class="fas fa-recycle"></i> Circular Economy, Waste Management, and Sustainability</li>
  <li><i class="fas fa-truck-moving"></i> Digitalization of Logistics and Transportation</li>
  <li><i class="fas fa-calculator"></i> Novel Quantitative Decision Analytics and MCDM Approaches</li>
</ul>
