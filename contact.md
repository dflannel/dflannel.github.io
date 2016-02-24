---
layout: page
title: Contact
---

## Feel free to drop me some lines

<form action="//formspree.io/dflannel+formspree@gmail.com" method="POST" id="contact">
    <div class="form-item">
      <label for="name">Nome:</label>
      <input type="text" name="name" placeholder="Es. Mario Rossi">
    </div>
    <div class="form-item">
      <label for="_replyto">Email:</label>
      <input type="email" name="_replyto" placeholder="Es. mario.rossi@example.com">
    </div>

    <div class="form-item">
      <label for="comment">Comment:</label>
      <textarea name="comment" id="comment" rows="5" placeholder="Your message...">
      </textarea>
    </div>

    <input type="hidden" name="_subject" value="Flannel Blog contact" />
    <input type="hidden" name="_next" value="http://www.dflannel.it" />
    <input type="submit" value="Send" class="button">
</form>
