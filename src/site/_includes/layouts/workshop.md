---
layout: layouts/base.njk
pageClass: workshops
templateEngineOverride: njk, md
---

<main>
  {{ content | safe }}
  <div class="footnote">
    <p>
      <strong>Fun fact</strong>: This is a workshop.
    </p>
  </div>
</main>
