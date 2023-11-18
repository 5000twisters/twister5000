---
layout: page
title: "Sign Up"
permalink: /signup/
---

<form action="https://formspree.io/f/https://formspree.io/f/xqkvoglj" method="POST">
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name"><br>
  <label for="contact">Preferred Contact Method:</label><br>
  <select id="contact" name="contact">
    <option value="email">Email</option>
    <option value="phone">Phone</option>
  </select><br>
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="_replyto"><br>
  <label for="phone">Phone:</label><br>
  <input type="tel" id="phone" name="phone"><br>
  <label for="commitment">Are you in?</label><br>
  <select id="commitment" name="commitment">
    <option value="in">I'm in!</option>
    <option value="try">I'll try</option>
    <option value="maybe">Maybe...</option>
    <option value="spread">Nah, but I'll spread the word</option>
    <option value="no">I want nothing to do with this</option>
  </select><br>
  <label for="updates">Update Preferences:</label><br>
  <input type="checkbox" id="updates" name="updates" value="goal">
  <label for="goal">Tell me when you reach your goal</label><br>
  <input type="checkbox" id="updates" name="updates" value="progress">
  <label for="progress">Send me occasional progress updates</label><br>
  <input type="checkbox" id="updates" name="updates" value="never">
  <label for="never">Never contact me</label><br>
  <input type="submit" value="Submit">
</form>
