---
layout: default
title: Contact
---

<div class="background" style="background-image: url('{{ site.baseurl }}/assets/images/bg1.jpg');">
      <div class="nav-links">
    <a href="{{ site.baseurl }}">Home</a>
    <a href="{{ site.baseurl }}/about.html">Histoire</a>
    <a href="{{ site.baseurl }}/projects.html">Technologie</a>
    <a href="{{ site.baseurl }}/gallery.html">Fondateurs</a>
    <a href="{{ site.baseurl }}/contact.html">Contact</a>
  </div>
  <h1>Contactez nous !</h1>
</div>

<div style="display: flex; align-items: stretch; max-width: 900px; margin: 40px auto; background: #222; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 24px #0003; font-family: 'Heiti TC', sans-serif;">
  
  <!-- Image on the left -->
  <div style="flex: 1; background: url('https://source.unsplash.com/400x400/?brain,technology') center/cover no-repeat;">
  </div>

  <!-- Your original form on the right -->
  <form id="contact-form" style="flex: 1; padding: 24px;">
    <label for="name" style="display:block;margin-bottom:8px;color: #00008B;">Name</label>
    <input type="text" id="name" name="name" required style="width:100%;margin-bottom:16px;padding:8px;border-radius:6px;border:1px solid #ccc;">

    <label for="email" style="display:block;margin-bottom:8px;color: #00008B;">Email</label>
    <input type="email" id="email" name="email" required style="width:100%;margin-bottom:16px;padding:8px;border-radius:6px;border:1px solid #ccc;">

    <label for="message" style="display:block;margin-bottom:8px;color:#00008B;">Message</label>
    <textarea id="message" name="message" rows="5" required style="width:100%;margin-bottom:16px;padding:8px;border-radius:6px;border:1px solid #ccc;"></textarea>

    <button type="submit" style="background:#4da6ff;color:#00008B;padding:10px 24px;border:none;border-radius:6px;font-weight:bold;cursor:pointer;">Send</button>
  </form>
</div>
</form>
