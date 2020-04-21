---
layout: default
title: Me contacter
---

<div class="contact-div">
  <div class="contact-form">
    <form action="{{site.contact_action}}" method="POST">
      <div class="item">
        <label>
          Email *
        </label>
        <input type="email" name="_replyto" placeholder="Votre adresse email...">
      </div>
      <div class="item">
        <label>
          Nom *
        </label>
        <input type="text" name="name" placeholder="Votre nom...">
      </div>
      <div class="item">
        <label>
          Message *
        </label>
        <textarea name="message" placeholder="Votre message..."></textarea>
      </div>
      <div class="actions">
        <input type="submit" value="Envoyer le message" class="button">
      </div>
    </form>
  </div>
</div>
