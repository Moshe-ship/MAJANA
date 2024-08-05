+++
title = "Majana: Elevate Your Business with Strategic Marketing"
description = "Discover how Majana's strategic marketing can help you achieve your business goals."
+++

<style>
body {
    font-family: 'Open Sans', sans-serif;
    line-height: 1.6;
    background-color: #000;
    color: #fff;
}
h1, h2, h3 {
    color: #2c3e50;
    margin-top: 20px;
}
h2 {
    border-bottom: 2px solid #4CAF50;
    padding-bottom: 5px;
}
ul {
    list-style-type: disc;
    margin-left: 20px;
}
form {
    max-width: 600px;
    margin: auto;
    padding: 20px;
    background-color: #f9f9f9;
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
.container {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
}
.section {
    padding: 60px 0;
}
.flex {
    display: flex;
    justify-content: center;
    align-items: center;
}
.text-center {
    text-align: center;
}
.uppercase {
    text-transform: uppercase;
}
.font-bold {
    font-weight: bold;
}
</style>

<div class="section text-center">
    <h1 class="font-display uppercase text-[6rem] sm:text-[14vw] 2xl:text-[18rem] leading-[100%]">Majana</h1>
</div>

<div class="section text-center">
    <p>Welcome to Majana, where we elevate your business through strategic marketing. Our team of experts is dedicated to helping you achieve your business goals with tailored marketing strategies.</p>
</div>

<div class="section">
    <h2 class="text-center">Our Services</h2>
    <div class="container flex flex-col lg:flex-row gap-[2rem] lg:gap-[4rem] justify-center">
        <div class="lg:max-w-[50%] 2xl:max-w-[33%]">
            <h3 class="uppercase font-bold">Digital Marketing</h3>
            <ul>
                <li>SEO</li>
                <li>Social Media Management</li>
                <li>Content Marketing</li>
            </ul>
        </div>
        <div class="lg:max-w-[50%] 2xl:max-w-[33%]">
            <h3 class="uppercase font-bold">Branding</h3>
            <ul>
                <li>Brand Strategy</li>
                <li>Logo Design</li>
                <li>Brand Identity</li>
            </ul>
        </div>
        <div class="lg:max-w-[50%] 2xl:max-w-[33%]">
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
