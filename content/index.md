+++
title = "Majana: Elevate Your Business with Strategic Marketing"
description = "Discover how Majana's strategic marketing can help you achieve your business goals."
+++

# Welcome to Majana

Welcome to Majana, where we elevate your business through strategic marketing. Our team of experts is dedicated to helping you achieve your business goals with tailored marketing strategies.

## Our Services

### Digital Marketing
- SEO
- Social Media Management
- Content Marketing

### Branding
- Brand Strategy
- Logo Design
- Brand Identity

### Web Development
- Custom Websites
- E-commerce Solutions
- Website Maintenance

## Recent Blog Posts

<h2>Recent Blog Posts</h2>
<ul>
  {{ range first 5 (where .Site.RegularPages "Section" "blog") }}
    <li>
      <a href="{{ .RelPermalink }}">{{ .Title }}</a>
      <p>{{ .Summary }}</p>
    </li>
  {{ end }}
</ul>

## Contact Us

If you have any questions or want to work with us, feel free to contact us through the form below.

<form name="contact" method="POST" data-netlify="true" style="max-width: 600px; margin: auto; padding: 20px; background-color: #f9f9f9; border-radius: 5px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);">
  <p>
    <label>Your Name: <input type="text" name="name" required style="width: 100%; padding: 10px; margin: 5px 0;" /></label>
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" required style="width: 100%; padding: 10px; margin: 5px 0;" /></label>
  </p>
  <p>
    <label>Your Message: <textarea name="message" required style="width: 100%; padding: 10px; margin: 5px 0;"></textarea></label>
  </p>
  <p>
    <button type="submit" style="background-color: #4CAF50; color: white; padding: 15px 20px; border: none; cursor: pointer;">Send</button>
  </p>
</form>
