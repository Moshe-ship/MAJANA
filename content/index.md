+++
title = "Majana: Elevate Your Business with Strategic Marketing"
description = "Discover how Majana's strategic marketing can help you achieve your business goals."
+++

<style>
body {
    font-family: 'Bebas Neue', 'Open Sans', sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}
h1, h2, h3 {
    color: var(--text-color);
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
    justify-content: center;
    align-items: center;
}
.scroll-container {
    display: flex;
    flex-direction: column;
    align-items: center;
}
.scroll-text {
    display: inline-block;
    font-size: 1.5rem;
    font-weight: bold;
    white-space: nowrap;
    margin: 0;
}
.scroll-text-left {
    animation: scroll-text-left 20s linear infinite;
}
.scroll-text-right {
    animation: scroll-text-right 20s linear infinite;
}
@keyframes scroll-text-left {
    0% {
        transform: translateX(100%);
    }
    100% {
        transform: translateX(-100%);
    }
}
@keyframes scroll-text-right {
    0% {
        transform: translateX(-100%);
    }
    100% {
        transform: translateX(100%);
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
.services-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 2rem;
}
.service-item {
    width: calc(50% - 2rem);
    background-color: var(--bg-secondary);
    padding: 2rem;
    text-align: center;
    border-radius: 8px;
    transition: transform 0.3s ease;
}
.service-item:hover {
    transform: scale(1.05);
}
.service-item h3 {
    margin-bottom: 1rem;
}
.service-item p {
    margin: 0;
}
form {
    max-width: 600px;
    margin: 40px auto;
    padding: 20px;
    background-color: var(--bg-secondary);
    color: var(--text-color);
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

<script>
document.addEventListener("DOMContentLoaded", function () {
    let scrollTextsLeft = document.querySelectorAll('.scroll-text-left');
    let scrollTextsRight = document.querySelectorAll('.scroll-text-right');
    scrollTextsLeft.forEach((scrollText) => {
        scrollText.style.animation = "scroll-text-left 20s linear infinite";
    });
    scrollTextsRight.forEach((scrollText) => {
        scrollText.style.animation = "scroll-text-right 20s linear infinite";
    });
});
</script>

<div class="section text-center">
    <h1 class="uppercase font-bold">Majana</h1>
    <p>Welcome to Majana, where we elevate your business through strategic marketing. Our team of experts is dedicated to helping you achieve your business goals with tailored marketing strategies.</p>
</div>

<div class="scroll-container">
    <div class="flex">
        <div class="scroll-text scroll-text-left">Google Ads • Local SEO • Technical SEO • Media Buying • META Ads • TikTok Ads • </div>
    </div>
    <div class="flex">
        <div class="scroll-text scroll-text-right">Google Ads • Local SEO • Technical SEO • Media Buying • META Ads • TikTok Ads • </div>
    </div>
</div>

<div class="section">
    <h2 class="text-center">Our Services</h2>
    <div class="container services-grid">
        <div class="service-item">
            <h3 class="uppercase font-bold">Media Buying</h3>
            <p>Programmatic Buying, Direct Buys, Ad Networks</p>
        </div>
        <div class="service-item">
            <h3 class="uppercase font-bold">Local SEO</h3>
            <p>Local Listings, Reviews Management, Geo-targeted SEO</p>
        </div>
        <div class="service-item">
            <h3 class="uppercase font-bold">Lead Generation</h3>
            <p>Quality Leads, Conversion Optimization, CRM Integration</p>
        </div>
        <div class="service-item">
            <h3 class="uppercase font-bold">Digital Marketing Strategy</h3>
            <p>Comprehensive Planning, Analytics, Execution</p>
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
