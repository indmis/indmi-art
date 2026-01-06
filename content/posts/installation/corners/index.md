---
title: "Название проекта"
cover:
    image: "cover.webp"
    relative: true
---

Описание инсталляции или вступительный текст.

<a href="prisutstvie-otsutstviya.pdf" target="_blank" class="pdf-link">
  <span class="pdf-icon">📄</span>
  <span class="pdf-text">
    <span class="pdf-title">Смотреть PDF-материалы</span>
    <span class="pdf-subtitle">Отсканированный буклет, 15 МБ</span>
  </span>
</a>

{{< gallery >}}

DEBUG:
{{ range .Page.Resources }}
  Нашел файл: {{ .Name }} | Тип: {{ .MediaType }}
{{ end }}
