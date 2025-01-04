---
layout: default
title: 写博客
---
<div class="page-header">
  <h1>{{ page.title }}</h1>
</div>
 
<form action="https://formspree.io/your@email.com" method="POST">
  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" class="form-control" placeholder="Your name">
  </div>
  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" id="email" name="email" class="form-control" placeholder="Your email">
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" class="form-control" rows="4" placeholder="Type your message here..."></textarea>
  </div>
  <button type="submit" class="btn btn-success">Submit</button>
</form>
