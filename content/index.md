+++
title = "Majana: Elevate Your Business with Strategic Marketing"
description = "Discover how Majana's strategic marketing can help you achieve your business goals."
+++

<style>
body {
    font-family: 'Bebas Neue', 'Open Sans', sans-serif;
    background-color: #000;
    color: #fff;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}
h1, h2, h3 {
    color: #4CAF50;
    margin: 0;
}
h1 {
    font-size: 6rem;
    text-align: center;
    margin-top: 20vh;
}
h2 {
    font-size: 4rem;
    text-align: center;
    margin: 2rem 0;
}
.section {
    padding: 6rem 1.5rem;
}
.text-center {
    text-align: center;
}
.flex {
    display: flex;
    flex-wrap: nowrap;
    overflow: hidden;
    justify-content: center;
    align-items: center;
    white-space: nowrap;
}
.scroll-text {
    display: inline-block;
    font-size: 2rem;
    margin: 0 1rem;
    animation: scroll-text 10s linear infinite;
}
@keyframes scroll-text {
    0% {
        transform: translateX(100%);
    }
    100% {
        transform: translateX(-100%);
    }
}
.uppercase {
    text-transform: uppercase;
}
.font-bold {
    font-weight: bold;
}
.container {
    max-width: 1200px;
    margin: auto;
}
form {
    max-width: 600px;
    margin: 40px auto;
    padding: 20px;
    background-color: #f9f9f9;
    color: #000;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
form p {
    margin-bottom: 15px;
}
form label {
    display: block;
    margin-bottom: 5px;
}
form input, form textarea {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #ccc;
    border-radius: 3px;
}
form button {
    background-color: #4CAF50;
    color: white;
    padding: 15px 20px;
    border: none;
    cursor: pointer;
    border-radius: 3px;
}
form button:hover {
    background-color: #45a049;
}
</style>

<div class="section text-center">
    <h1 class="uppercase font-bold">Majana</h1>
    <p>Welcome to Majana, where we elevate your business through strategic marketing.</p>
</div>

<div class="section flex">
    <div class="scroll-text">Web Development • Static Websites • Hugo SSG • Full-Stack Applications • Next.JS • Supabase • </div>
    <div class="scroll-text">Web Development • Static Websites • Hugo SSG • Full-Stack Applications • Next.JS • Supabase • </div>
</div>

<div class="section">
    <h2 class="text-center">Our Services</h2>
    <div class="container flex">
        <div>
            <h3 class="uppercase font-bold">Digital Marketing</h3>
            <ul>
                <li>SEO</li>
                <li>Social Media Management</li>
                <li>Content Marketing</li>
            </ul>
        </div>
        <div>
            <h3 class="uppercase font-bold">Branding</h3>
            <ul>
                <li>Brand Strategy</li>
                <li>Logo Design</li>
                <li>Brand Identity</li>
            </ul>
        </div>
        <div>
            <h3 class="uppercase font-bold">Web Development</h3>
            <ul>
                <li>Custom Websites</li>
                <li>E-commerce Solutions</li>
                <li>Website Maintenance</li>
            </ul>
        </div>
    </div>
</div>

<div class="section">
    <h2 class="text-center">Recent Blog Posts</h2>
    <ul class="container">
        {{ range first 5 (where .Site.RegularPages "Section" "blog") }}
        <li>
            <a href="{{ .RelPermalink }}">{{ .Title }}</a>
            <p>{{ .Summary }}</p>
        </li>
        {{ end }}
    </ul>
</div>

<div class="section">
    <h2 class="text-center">Contact Us</h2>
    <p class="text-center">If you have any questions or want to work with us, feel free to contact us through the form below.</p>
    <form name="contact" method="POST" netlify>
        <p>
            <label>Your Name: <input type="text" name="name" required /></label>
        </p>
        <p>
            <label>Your Email: <input type="email" name="email" required /></label>
        </p>
        <p>
            <label>Your Message: <textarea name="message" required></textarea></label>
        </p>
        <p>
            <button type="submit">Send</button>
        </p>
    </form>
</div>
