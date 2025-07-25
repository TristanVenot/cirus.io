---
layout: default
title: Contact
---

<div class="background">
     <div class="nav-links">
    <a href="{{ site.baseurl }}">Home</a>
    <a href="{{ site.baseurl }}/about.html">Agenda</a>
    <a href="{{ site.baseurl }}/projects.html">Technologie</a>
    <a href="{{ site.baseurl }}/gallery.html">Fondateurs</a>
    <a href="{{ site.baseurl }}/contact.html">Contact</a>
  </div>
  
</div>
<h1 style="text-align:center;  padding: 34px 34px 34px 84px;color: black;font-size: 3rem">Contactez-nous !</h1>
<div class="container_contact">

  <div class="video-box_contact">
    <video
    src="{{ site.baseurl }}/assets/video/contact.mp4"
    type="video/mp4"
    autoplay
    muted
    loop
    playsinline
    style="transform: rotate(90deg); width: 640px; height: 480px; object-fit: cover;"
  ></video>
  </div>

<form id="contact-form" style="flex: 1; padding: 24px 24px 24px 64px;">
  <div style="display: flex; flex-direction: column; align-items: flex-start; gap: 16px; width: 300px;">
    
    <label for="name" style="color: #00008B;">Name</label>
    <input 
      type="text" 
      id="name" 
      name="name" 
      required 
      style="
        width: 100%; 
        height: 40px; 
        padding: 8px; 
        border-radius: 6px; 
        border: 1px solid #ccc; 
        background-color: white;
        color: black;
      ">

    <label for="email" style="color: #00008B;">Email</label>
    <input 
      type="text" 
      id="email" 
      name="email" 
      required 
      style="
        width: 100%; 
        height: 40px; 
        padding: 8px; 
        border-radius: 6px; 
        border: 1px solid #ccc; 
        background-color: white;
        color: black;
      ">

    <label for="message" style="color: #00008B;">Message</label>
    <textarea 
      id="message" 
      name="message" 
      required 
      style="
        width: 100%; 
        height: 300px; 
        padding: 8px; 
        border-radius: 6px; 
        border: 1px solid #ccc; 
        background-color: white;
        color: black;
        resize: vertical;
      "></textarea>

    <button 
      type="submit" 
      style="
        width: 100%; 
        background:#4da6ff; 
        color:#fff; 
        padding: 10px; 
        border: none; 
        border-radius: 6px; 
        font-weight: bold; 
        cursor: pointer;">
      Send
    </button>
  </div>
</form>
</div>

