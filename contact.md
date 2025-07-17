---
layout: default
title: Contact
---

<div class="background" style="background-image: url('{{ site.baseurl }}/assets/images/bg1.jpg');">
      <div class="nav-links">
    <a href="{{ site.baseurl }}">Home</a>
    <a href="{{ site.baseurl }}/about.html">Produit</a>
    <a href="{{ site.baseurl }}/projects.html">Technologie</a>
    <a href="{{ site.baseurl }}/gallery.html">Fondateurs</a>
    <a href="{{ site.baseurl }}/contact.html">Contact</a>
  </div>
  <h1>Nous contacter</h1>
  <p>Vous pouvez</p>
</div>

<form action="https://formspree.io/f/xpwlwzal" method="POST" style="max-width:400px;margin:40px auto;padding:24px;background:#222;border-radius:12px;box-shadow:0 4px 24px #0003;">
  <label for="name" style="display:block;margin-bottom:8px;color:#fff;">Name</label>
  <input type="text" id="name" name="name" required style="width:100%;margin-bottom:16px;padding:8px;border-radius:6px;border:1px solid #ccc;">

  <label for="email" style="display:block;margin-bottom:8px;color:#fff;">Email</label>
  <input type="email" id="email" name="email" required style="width:100%;margin-bottom:16px;padding:8px;border-radius:6px;border:1px solid #ccc;">

  <label for="message" style="display:block;margin-bottom:8px;color:#fff;">Message</label>
  <textarea id="message" name="message" rows="5" required style="width:100%;margin-bottom:16px;padding:8px;border-radius:6px;border:1px solid #ccc;"></textarea>

  <button type="submit" style="background:#4da6ff;color:#fff;padding:10px 24px;border:none;border-radius:6px;font-weight:bold;cursor:pointer;">Send</button>
</form>
