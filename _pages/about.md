---
permalink: /
# تایتل را از اینجا حذف نمی‌کنیم اما در نمایش آن را با CSS مخفی می‌کنیم
layout: single
classes: wide
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
    margin: -15px 0 10px 0; /* فاصله کمتر برای تیتر اول */
    border-left: 8px solid #d4af37;
    font-size: 1.2em;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    display: block;
  }
<style>
  /* استایل کلی باکس‌ها (حفظ ساختار اصلی مورد علاقه شما) */
  .poms-research-box {
    border: 1px solid var(--border-color, #f2f3f3); /* خط دور ظریف */
    background: transparent !important;
    padding: 15px 20px;
    border-radius: 6px;
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    transition: all 0.3s ease; /* انیمیشن نرم */
    cursor: pointer;
    box-shadow: 0 1px 3px rgba(0,0,0,0.05);
  }

  /* افکت تعاملی هنگام هاور (حفظ رنگ زرد/طلایی مورد علاقه شما) */
  .poms-research-box:hover {
    background-color: rgba(212, 175, 55, 0.1) !important; /* پس‌زمینه طلایی ملایم */
    border-color: #d4af37 !important; /* خط دور طلایی پررنگ */
    transform: translateY(-3px); /* کمی بالا رفتن باکس */
    box-shadow: 0 5px 15px rgba(212, 175, 55, 0.2); /* سایه طلایی */
  }

  /* استایل آیکون‌های جدید وکتور */
  .research-icon {
    margin-right: 20px;
    font-size: 1.6em; /* بزرگ‌تر برای وضوح بیشتر */
    min-width: 35px;
    text-align: center;
    background: transparent !important;
    opacity: 0.9;
    transition: all 0.3s ease;
  }
  
  /* افکت آیکون هنگام هاور: بزرگ‌تر شدن و درخشش */
  .poms-research-box:hover .research-icon {
    transform: scale(1.1);
    opacity: 1;
  }

  /* متن: ارث‌بری رنگ از تم اصلی */
  .research-text {
    font-size: 1.05em;
    font-weight: 500;
    color: inherit; /* خوانایی در تم مشکی و سفید */
  }
</style>
  /* ۱. باز کردن عرض کل سایت به ۹۵ درصد (مشابه POMS) */
  .wrapper {
    max-width: 95% !important;
    margin: 0 auto !important;
  }
  /* ۲. حذف محدودیت عرض از بخش اصلی محتوا */
  #main {
    max-width: 95% !important;
  }

  /* ۳. اجازه به بخش متن برای پهن شدن در فضای باقی‌مانده */
  .initial-content, 
  .page__content {
    width: 95% !important;
  }

  /* ۴. حذف ستون خالی سمت راست که باعث عدم تقارن شده بود */
  @media (min-width: 64em) {
    .archive, .page {
      padding-right: 0 !important;
      margin-right: 0 !important;
    }
  }
  /* ۷. واکنش‌گرایی برای موبایل */
  @media (max-width: 64em) {
    #main { display: block !important; }
    .wrapper { max-width: 100% !important; padding: 0 15px !important; }
    .sidebar { width: 100% !important; margin-bottom: 30px !important; }
    .interest-grid { grid-template-columns: 1.2fr; } /* تک ستونه در موبایل */
  }
  /* ۵. تنظیمات موبایل برای حفظ حاشیه ایمن */
}
</style>
<div class="poms-main-header" style="margin-top: 0px;">About Me</div>

I am an early-career scholar in Engineering Management with strong experience in applied research on digital and sustainable engineering systems and in supervising students in project-based learning environments. My work bridges decision analytics, digital transformation, and strategic operations, with a particular focus on [Cloud Supply Chain as a Service](https://www.sciencedirect.com/science/article/abs/pii/S1366554525005824). My research is oriented toward supporting managerial decision-making and strategy formulation in operations-intensive industries.

I introduced the Base-Criterion Method (BCM) in 2020 and the HECON method in 2023, and have further developed advanced decision-analytics frameworks grounded in novel theoretical perspectives. I am also the Lead Editor of two Elsevier books: [Reliable Decision-Making for Sustainable Transportation](https://www.sciencedirect.com/book/edited-volume/9780443337406/reliable-decision-making-for-sustainable-transportation) and the [Encyclopedia of Multi-Attribute Decision-Making (MADM)](https://shop.elsevier.com/books/encyclopedia-of-multi-attribute-decision-making-madm/haseli/978-0-443-33275-3). My research has resulted in more than 25 peer-reviewed journal publications with leading publishers, including Elsevier, Springer, and IEEE, and I have served on scientific committees of several international conferences.

I am currently pursuing my Ph.D. at [Tecnológico de Monterrey](https://tec.mx/en) in Mexico. I have also been involved in international research collaborations, including the Digital Voting Hub for Sustainable Urban Transport Systems (VOTE-TRA) project [No. 22/NCF/DR/11309] funded by Science Foundation Ireland at [University College Dublin](https://www.ucd.ie), and the project Intersectoral and Interdisciplinary Cooperation in Research and Development of Communication and Information Technologies [CZ.02.01.01/00/23_021/0008402] at the [University of Hradec Králové](https://www.uhk.cz/en) in the Czech Republic. My current research aims to bridge decision sciences and cloud-based supply chain systems to support digital transformation, resilience, and intelligent decision support. I am open to international academic and industry collaborations.

<div class="poms-main-header" style="margin-top: 20px;">Research Interests</div>

<div class="research-container" style="margin-top: 25px;">
  
  <div class="poms-research-box">
    <i class="fas fa-boxes research-icon" style="color: #0d1b3e;"></i>
    <span class="research-text">Supply Chain Management and Strategic Operations</span>
  </div>

  <div class="poms-research-box">
    <i class="fas fa-cloud-download-alt research-icon" style="color: #4285f4;"></i>
    <span class="research-text">Cloud Supply Chain as a Service Risk, Resilience, and Sustainability</span>
  </div>

  <div class="poms-research-box">
    <i class="fas fa-microchip research-icon" style="color: #9b59b6;"></i>
    <span class="research-text">Digital Transformation and Service-Oriented Platforms</span>
  </div>

  <div class="poms-research-box">
    <i class="fas fa-recycle research-icon" style="color: #27ae60;"></i>
    <span class="research-text">Circular Economy, Waste Management, and Sustainability</span>
  </div>

  <div class="poms-research-box">
    <i class="fas fa-truck-loading research-icon" style="color: #e67e22;"></i>
    <span class="research-text">Digitalization of Logistics and Transportation</span>
  </div>

  <div class="poms-research-box">
    <i class="fas fa-calculator research-icon" style="color: #e74c3c;"></i>
    <span class="research-text">Novel Quantitative Decision Analytics and MCDM Approaches</span>
  </div>

</div>
<style>

  /* کانتینر شبکه‌ای مینیمال برای تصاویر SDG */
  .sdg-image-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(85px, 0fr)); /* چیدمان خودکار در موبایل و دسکتاپ */
    gap: 2px; /* فاصله بین تصاویر */
    margin-top: 15px;
    margin-bottom: 25px;
    justify-items: left; /* تراز کردن در مرکز */
  }

  /* استایل هر کارت تصویر */
  .sdg-image-card {
    transition: all 0.3s ease;
    cursor: default;
  }

  /* افکت زیبا هنگام حرکت موس (شناور شدن ملایم) */
  .sdg-image-card:hover {
    transform: translateY(-8px) scale(1.05);
    filter: drop-shadow(0 8px 15px rgba(0,0,0,0.3)); /* سایه باکیفیت‌تر */
  }

  /* تنظیم اندازه و حاشیه تصاویر */
  .sdg-image-card img {
    width: 90px; /* اندازه بهینه تصاویر */
    height: 90px;
    object-fit: contain; /* حفظ تناسب تصویر */
  }
</style>


<Strong>Sustainable Developments Goals:</Strong>

<div class="sdg-image-grid">
  <div class="sdg-image-card">
    <img src="{{ site.baseurl }}/images/sdg08.png" alt="SDG 8">
  </div>
  <div class="sdg-image-card">
    <img src="{{ site.baseurl }}/images/sdg09.png" alt="SDG 9">
  </div>
  <div class="sdg-image-card">
    <img src="{{ site.baseurl }}/images/sdg11.png" alt="SDG 11">
  </div>
  <div class="sdg-image-card">
    <img src="{{ site.baseurl }}/images/sdg12.png" alt="SDG 12">
  </div>
  <div class="sdg-image-card">
    <img src="{{ site.baseurl }}/images/sdg17.png" alt="SDG 17">
  </div>
</div>

<div class="language-section" style="margin-top: 20px;">
  <h4 style="border-bottom: 1px solid #d4af37; padding-bottom: 5px;"><strong>Languages</strong></h4>
  <p style="font-size: 0.9em;">
    <span class="badge-lang">English (Advanced)</span>
    <span class="badge-lang">Azerbaijani (Native)</span>
    <span class="badge-lang">Persian (Native)</span>
    <span class="badge-lang">Turkish (Advanced)</span>
    <span class="badge-lang">Spanish (Elementary)</span>
  </p>
</div>

<style>
  .badge-lang {
    display: inline-block;
    background: rgba(13, 27, 62, 0.05);
    border: 1px solid #d4af37;
    padding: 2px 10px;
    margin: 3px;
    border-radius: 15px;
    font-weight: 500;
  }
</style>
