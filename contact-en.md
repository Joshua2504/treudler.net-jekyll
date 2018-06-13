---
layout: page
title: Contact
tagline: Contact me
excerpt: >
  Contact me through this contact form
permalink: /contact.html
header:
  image: /assets/img/header/2018-03-30-contact.jpg
ref: contact
lang: en  
order: 3
menu: main
---

# Simply use the form below to contact me.

"Create a contact form and you're good to go", they said.

I'm too lazy for that. I know that this contact form looks bad, but it's fine for now.

<form action="https://formspree.io/joshua@treudler.net" method="POST" id="contact">
  <input type="email" name="email" placeholder="Your Email">
  <input type="text" name="name" placeholder="Your Name">
  <input type="textarea" name="message" type="hidden"><br><br>
  <textarea name="message" form="contact" placeholder="Your Message" rows="10" cols="50"></textarea><br><br>
  <input type="hidden" name="_language" value="en" />
  <button type="submit">Submit</button>
</form>

*Please note that pressing "Submit" will redirect you to [Formspree](https://formspree.io/){:target="_blank"}. They'll forward your message to me through email. This website is containing static content only, so no chance to send emails on my own as of now. If you want to avoid formspree, simply send an email to joshua at treudler dot net.*

For any legal concerns, please send a letter to my mailing address listed on the [Imprint](imprint.html) page.

{% include go-to-home-page.html %}
