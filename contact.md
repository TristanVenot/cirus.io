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

<div class="container_techno">
  <div class="video-box_techno">
  <video src="{{ site.baseurl }}/assets/video/contact.mp4" type="video/mp4" width="720"
  height="480" autoplay muted loop playsinline>></video>
  </div>

  <!-- Your original form on the right -->
  <form id="contact-form" style="flex: 1; padding: 24px;">
    <label for="name" style="display:block;margin-bottom:8px;color: #00008B;">Name</label>
    <input 
  type="text" 
  id="name" 
  name="name" 
  required 
  style="
    width: 200px; 
    height: 200px; 
    margin-bottom: 16px; 
    padding: 8px; 
    border-radius: 6px; 
    border: 1px solid #ccc; 
    background-color: white;
    color: black;
  ">

  <label for="email" style="display:block;margin-bottom:8px;color: #00008B;">Email</label>
    <input 
  type="text" 
  id="email" 
  name="email" 
  required 
  style="
    width: 200px; 
    height: 200px; 
    margin-bottom: 16px; 
    padding: 8px; 
    border-radius: 6px; 
    border: 1px solid #ccc; 
    background-color: white;
    color: black;
  ">

  <label for="message" style="display:block;margin-bottom:8px;color: #00008B;">Message</label>
    <input 
  type="text" 
  id="message" 
  name="message" 
  required 
  style="
    width: 200px; 
    height: 200px; 
    margin-bottom: 16px; 
    padding: 8px; 
    border-radius: 6px; 
    border: 1px solid #ccc; 
    background-color: white;
    color: black;
  ">

  <button type="submit" style="background:#4da6ff;color:#fff;padding:10px 24px;border:none;border-radius:6px;font-weight:bold;cursor:pointer;">Send</button>
</form>
  </div>
</form>
