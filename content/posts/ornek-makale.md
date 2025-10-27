---
title: "Hugo Markdown ve HTML Etiketleri Nasıl Görüntüler?"
description: "Bu örnek makale, Hugo'da Markdown ve HTML etiketlerinin birlikte nasıl işlendiğini göstermek için hazırlanmıştır."
date: 2025-10-26
slug: "hugo-markdown-html-ornek"
image: "/images/hugo-markdown.jpg"
tags: ["Hugo", "Markdown", "SEO", "Blog"]
draft: false
---

## Giriş

Bu makale, **Hugo** üzerinde yazı oluştururken hem *Markdown* hem de **HTML etiketlerinin** nasıl işlendiğini göstermek amacıyla hazırlanmıştır.  
Hugo, Markdown içeriği işlerken HTML kodlarını da **doğrudan geçerli** kabul eder.

---

## 1. Başlıklar, Kalın ve İtalik Yazılar

Markdown biçimlendirmesi oldukça kolaydır:

- `#` → `<h1>`
- `##` → `<h2>`
- `###` → `<h3>`

Örnek:
> **Bu metin kalın**, *bu metin italik*,  
> ve ***bu metin hem kalın hem italik.***

---

## 2. Alıntı, Kod ve Liste Örnekleri

> Bu bir alıntı satırıdır.  
> Hugo, Markdown quote (`>`) yapısını da destekler.

Aşağıda bir kod bloğu örneği var:

```html
<div class="example-box">
  <p>Bu bir HTML paragrafıdır.</p>
</div>
