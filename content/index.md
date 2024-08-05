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

<form name="contact" netlify>
  <p>
    <label>Name <input type="text" name="name" required style="width: 100%; padding: 10px; margin: 5px 0;" /></label>
  </p>
  <p>
    <label>Email <input type="email" name="email" required style="width: 100%; padding: 10px; margin: 5px 0;" /></label>
  </p>
  <p>
    <label>Your Message <textarea name="message" required style="width: 100%; padding: 10px; margin: 5px 0;"></textarea></label>
  </p>
  <p>
    <button type="submit" style="background-color: #4CAF50; color: white; padding: 15px 20px; border: none; cursor: pointer;">Send</button>
  </p>
</form>
