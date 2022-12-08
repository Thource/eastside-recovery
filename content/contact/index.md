---
title: "Contact Us"
date: 2022-04-26T21:03:59+00:00
draft: false
header_img: "img/img1.jpg"
---

{{< rawhtml >}}
<form action={FORM_ENDPOINT} method="POST" target="_blank">
  <p><b>If your enquiry is urgent, call us on <a href="tel:07598503402">07598 503 402</a>, otherwise, please use the form below.</b></p>

  <div class="mb-3 pt-0">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required />
  </div>
  <div class="mb-3 pt-0">
    <label for="email">Email Address</label>
    <input type="email" id="email" name="email" required />
  </div>
  <div class="mb-3 pt-0">
    <label for="message">Message</label>
    <textarea id="message" name="message" required></textarea>
  </div>
  <div class="mb-3 pt-0">
    <button class="btn btn--primary" type="submit">Send message</button>
  </div>
</form>
{{< /rawhtml >}}