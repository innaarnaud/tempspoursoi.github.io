---
layout: default
title: Accueil
---

<p class="citation">
	<span class="over">
		<span class="line1">
			Quand nous nous manquons à nous-même,
		</span>
		<span class="line2">
			tout nous manque.
		</span>
		<span class="author">
			Johann Wolfgang von Goethe
		</span>
	</span>
</p>

<img class="home" src="/assets/images/mudra.jpg" />

<h1 style="text-align: center; margin-top: 120px;">Me contacter</h1>

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
