---
layout: default
title: Contact Me
permalink: /contact-me/
---
  <div id="contact-me" class="tab active">
    <h1>Contact Me</h1>
    <form id="contact-form" action="https://formspree.io/f/mrbeznpg" method="POST">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Your Email:</label>
        <input type="email" id="email" name="_replyto" required>
        <label for="message">Your Message:</label>
        <textarea id="message" name="message" required></textarea>
        <button type="submit">Send</button>
    </form>
  </div>
