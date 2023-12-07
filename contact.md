---
layout: single
title: Contact Us
permalink: /contact/
---

<div class="container">
  <form action="{FORM_ENDPOINT}" method="POST" class="form">
    <div class="form-group">
      <label for="name">name</label>
      <input type="text" id="name" name="name" required>
    </div>

    <div class="form-group">
      <label for="email">email address</label>
      <input type="email" id="email" name="email" required>
    </div>

    <div class="form-group">
      <label for="message">message</label>
      <textarea id="message" name="message" rows="5" required></textarea>
    </div>

    <div class="form-group">
      <button type="submit" class="btn btn--primary">SEND</button>
    </div>
  </form>
</div>