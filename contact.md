---
layout: default
title: "Обратная связь"
---

<section class="section">
  <div class="container">
    <h1>Обратная связь</h1>

    <p>Если у вас есть вопросы или предложения, заполните форму ниже или свяжитесь со мной напрямую.</p>

    <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
      <label for="name">Имя:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="_replyto" required>

      <label for="message">Сообщение:</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit">Отправить</button>
    </form>
  </div>
</section>
