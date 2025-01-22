---
layout: default
title: Contact Me
permalink: /contact-me/
---
  <div id="contact-me" class="tab active">
    <h1>Contact Me</h1>
    <form id="contact-form" action="https://formspree.io/f/mrbeznpg" method="POST" onsubmit="handleSubmit(event)">
        <label for="name">Your Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Your Email:</label><br>
        <input type="email" id="email" name="_replyto" required><br><br>
        <label for="message">Your Message:</label><br>
        <textarea id="message" name="message" required></textarea><br><br>
        <button type="submit">Send</button><br><br>
    </form>
    <div id="thankYouMessage" style="display:none;">
        <h2>Thank You for Your Message!</h2>
        <p>I will get back to you as soon as possible.</p>
    </div>
  </div>

<script>
  function handleSubmit(event) {
    event.preventDefault(); // Prevent form submission (page refresh)
    
    // Check if the function is triggered
    console.log("Form submission triggered");
    
    // Hide the form
    document.getElementById('contact-form').style.display = 'none';
    
    // Show the thank you message
    document.getElementById('thankYouMessage').style.display = 'block';
    
    // Optionally, submit the form data to Formspree
    fetch(event.target.action, {
      method: event.target.method,
      body: new FormData(event.target),
    })
    .then(response => {
      if (response.ok) {
        console.log("Form submitted successfully");
      } else {
        console.error("Form submission failed");
      }
    })
    .catch(error => {
      console.error("Error during form submission:", error);
    });
  }
</script>

