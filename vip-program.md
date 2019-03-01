---
layout: default
title: VIP Program | The Scott Gregory Team
permalink: /vip-program/
---
<div class="center">
<h1>Join Our VIP Program</h1>
<img src="/img/vip.png" class="half-image"><br>
</div>

<form class="contact-form" method="post" action="https://formspree.io/{{site.data.settings.client.email}}">
  <input type="text" name="first-name" placeholder="First Name" required>
  <input type="text" name="last-name" placeholder="Last Name" required>
  <input type="email" name="_replyto" placeholder="Email" required>
  <input type="text" name="phone" placeholder="Phone Number" required>
  <input type="text" name="address" placeholder="Address" required>
  <textarea name="Message" placeholder="Message"></textarea>
  <!-- Cloud cannon settings field -->
  <div class="hidden">
    <input type="hidden" name="_to" value="{{site.data.settings.client.email}}">
    <input type="hidden" name="_subject" value="VIP Program Message From Your Vyral Video Blog">
    <input type="text" name="_gotcha">
  </div>

  <input type="submit" value="submit">
</form>
