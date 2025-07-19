---
layout: archive
title: "Contact"
permalink: /fr/contact/
lang: fr
author_profile: true
---
{% include base_path %}

## Me contacter

Si vous avez des questions ou souhaitez collaborer sur un projet, n'hésitez pas à me joindre ! Remplissez le formulaire ci-dessous et je vous répondrai rapidement. Vous pouvez aussi me retrouver sur [LinkedIn](https://www.linkedin.com/in/anthonylegourrierec) ou m'écrire directement par [email](mailto:anthonylegourrierec@gmail.com).

<form action="https://formspree.io/f/xjkbznoz" method="POST" class="contact-form">
  <label for="name">Votre nom&nbsp;:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Votre email&nbsp;:</label>
  <input type="email" id="email" name="email" required>

  <label for="message">Votre message&nbsp;:</label>
  <textarea id="message" name="message" rows="5" required></textarea>

  <button type="submit">Envoyer</button>
</form>

<style>
  .contact-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 8px;
    background-color: #f9f9f9;
  }
  .contact-form label {
    font-weight: bold;
  }
  .contact-form input,
  .contact-form textarea {
    padding: 10px;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 4px;
  }
  .contact-form button {
    padding: 12px;
    font-size: 16px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  .contact-form button:hover {
    background-color: #0056b3;
  }
</style>
