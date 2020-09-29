---
layout: default
title: Accueil
noborder: true
---

{::options parse_block_html="true" /}
<div class="intro">
  <p class="citation">
    <span class="over">
      <span class="welcome">
        Bienvenue
      </span>
      <span class="line1">
        Soyez acteur de votre chemin de santé
      </span>
      <span class="actions">
        <a href="/cours#le-planning">
          <span>
            Le planning
          </span>
        </a>
        <a href="/ma_philosophie">
          <span>
            Me connaître
          </span>
        </a>
      </span>
    </span>
  </p>

  {% responsive_image_block %}
      path: assets/images/IMG_20200524_154816.jpg
      alt: "Inna au barrage"
      class: "home"
  {% endresponsive_image_block %}

  <!-- <img class="home" src="/assets/images/IMG_20200524_154816.jpg" /> -->
</div>

<div class="boxes">
  <span class="boxe">
    <h3>
      Nouveau en Yoga et/ou Dō-In ?
    </h3>
    <p>
      Découvrez différentes pratiques de bien-être et leurs bienfaits.
    </p>
    <a href="/nouveau" title="Découvrir" class="button">Découvrir</a>
  </span>
  <span class="boxe">
    <h3>
      Accompagnement individuel
    </h3>
    <p>
      Envie de prendre du temps pour vous avec des conseils personnalisés ?
    </p>
    <a href="/#contact" title="Prendre contact" class="btn btn-style-2">Prendre contact</a>
  </span>
  <span class="boxe">
    <h3>
      Nos prochains événements
    </h3>
    <p>
      Découvrez nos prochaines activités et rejoignez nous !
    </p>
    <a href="/events" title="Voir les événements" class="btn btn-style-2">Voir les événements</a>
  </span>
</div>

<div class="contact-div">
  <h1 style="text-align: center; margin-top: 120px; padding-top: 100px;" id="contact">Me contacter</h1>
  <div class="telephone">
    Par téléphone: <a href="tel:+33749171258">07 49 17 12 58</a>
  </div>
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
