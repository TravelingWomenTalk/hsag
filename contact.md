---
layout: page
title: Contact
permalink: /contact/
layout: default
---

<h2>Sign up for our newsletter or send us a message.</h2>
<form action="https://formspree.io/{{ site.email }}" method="POST">
  <div class="form-group">
    <label for="name">Name:</label>
    <input type="text" class="form-control" id="email" placeholder="Enter name" name="name">
  </div>
  <div class="form-group">
    <label for="email">Email:</label>
    <input type="email" class="form-control" id="email" placeholder="Enter email" name="_replyto">
  </div>
  <div class="form-group">
    <label for="message">Message:</label>
    <textarea type="text" name="message" class="form-control" rows="5" id="message" placeholder="Enter message"></textarea>
  </div>
  <div class="form-group">
    <label for="newsletter">Sign up for newsletter? (yes/no)</label>
    <input type="text" class="form-control" id="newsletter" placeholder="yes/no" name="newsletter">
  </div>
  <input type="submit" value="Send" class="btn btn-default">
</form>
