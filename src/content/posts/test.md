---
title: Contoh Postingan dengan Link Tab Baru
author: WDP ML GRATIS
pubDatetime: 2022-06-06T04:06:31Z
slug: contoh-test-link
featured: false
draft: false
tags:
  - Test
description: Mencoba link dengan target blank di dalam konten.
---

## Percobaan Link HTML

Di bawah ini adalah link yang dibuat menggunakan HTML agar bisa terbuka di tab baru:

<span>
  AstroPaper is a minimal, accessible and SEO-friendly blog theme built with 
  <a 
    href="https://astro.build/" 
    target="_blank" 
    rel="noopener noreferrer" 
    class="underline decoration-dashed underline-offset-4 hover:text-skin-accent"
  >
    Astro
  </a> 
  and 
  <a 
    href="https://tailwindcss.com/" 
    target="_blank" 
    rel="noopener noreferrer" 
    class="underline decoration-dashed underline-offset-4 hover:text-skin-accent"
  >
    Tailwind CSS
  </a>.
</span>

## Kenapa pakai cara ini?
Karena standar Markdown `[Teks](URL)` tidak mendukung `target="_blank"`. Dengan menyisipkan HTML di atas, kamu bisa memaksa link terbuka di tab baru tanpa merusak desain AstroPaper kamu.