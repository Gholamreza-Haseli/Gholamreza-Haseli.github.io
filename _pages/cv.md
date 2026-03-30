---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  /* مخفی کردن تایتل پیش‌فرض */
  .page__title {
    display: none !important;
  }

  /* باکس اصلی سرمه‌ای */
  .poms-cv-header {
    background-color: #0d1b3e;
    color: #f2e3c2;
    padding: 15px 25px;
    border-radius: 4px;
    margin-bottom: 30px;
    border-left: 10px solid #d4af37;
    font-size: 1.2em;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 2px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  }

  /* کارت دانلود PDF */
  .cv-download-card {
    display: flex;
    align-items: center;
    background: var(--receiver-msg-bg, #f9f9f9);
    border: 1px solid #d4af37;
    border-radius: 8px;
    padding: 30px;
    margin-top: 20px;
    transition: all 0.3s ease;
  }

  .cv-download-card:hover {
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    transform: translateY(-5px);
  }

  .pdf-icon {
    font-size: 4em;
    color: #0d1b3e;
    margin-right: 25px;
  }

  .cv-info h3 {
    margin: 0 0 10px 0;
    color: #0d1b3e;
  }

  /* دکمه طلایی دانلود */
  .btn-poms-gold {
    display: inline-block;
    background-color: #d4af37;
    color: #0d1b3e !important;
    padding: 12px 25px;
    border-radius: 5px;
    font-weight: bold;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 0.9em;
    border: 2px solid #0d1b3e;
    transition: 0.3s;
  }

  .btn-poms-gold:hover {
    background-color: #0d1b3e;
    color: #f2e3c2 !important;
    border-color: #d4af37;
  }
  /
  .wrapper {
    max-width: 95% !important;
    margin: 0 100 !important;
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
    .interest-grid { grid-template-columns: 1fr; } /* تک ستونه در موبایل */
  }
</style>

<div class="poms-cv-header">Curriculum Vitae</div>

<p style="font-size: 0.95em; line-height: 1.4; margin-top: 15px;">
  You can download my full Curriculum Vitae (CV) by clicking the button below. 
  The document includes my detailed research experience, publications, editorial roles, and academic achievements.
</p>

<div class="cv-download-card">
  <div class="pdf-icon">
    <i class="fas fa-file-pdf"></i>
  </div>
  <div class="cv-info">
    <h3>Full Academic CV</h3>
    <p style="margin-bottom: 15px; opacity: 0.8;">Last updated: March 2026</p>
    <a href="{{ base_path }}/files/Haseli_CV.pdf" class="btn-poms-gold" target="_blank">
      <i class="fas fa-download"></i> Download PDF
    </a>
  </div>
</div>

<div style="margin-top: 50px; padding: 20px; border-left: 4px solid #0d1b3e; background: rgba(13, 27, 62, 0.05);">
  <p style="font-style: italic; font-size: 0.9em;">
    Note: For collaboration inquiries or detailed information regarding specific research projects, 
    please feel free to reach out via email.
  </p>
</div>
