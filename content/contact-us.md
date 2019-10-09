---
title: "Contact Us"
date: 2018-07-13T04:05:26+01:00
draft: false
---
<style>
    label {width:20px;}
    input {width:300px;}
    .hidden {display:none;}
</style>
<form name="contact" method="POST" netlify-honeypot="bot-field" netlify>
  <p class="hidden">
    <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
  </p>
  <p>
    <label>Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Email: <input type="email" name="email" /></label>
  </p>  
  <p>
    <label>Message: <textarea name="message" rows=5 cols=50></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>