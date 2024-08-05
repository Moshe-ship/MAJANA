+++
title = "MAJANA: We cut your cost"
description = "Your digital growth partner. Helping you achieve success through tailored marketing strategies."
+++

<style>
body {
    font-family: 'Open Sans', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: var(--background);
    color: var(--text);
}
h1, h2, h3 {
    color: var(--title-color);
}
h1 {
    font-size: 4rem;
    text-transform: uppercase;
    font-weight: bold;
}
h2 {
    font-size: 2.5rem;
    border-bottom: 2px solid var(--title-color);
    padding-bottom: 10px;
    margin-top: 40px;
}
h3 {
    font-size: 2rem;
}
.description {
    font-size: 1.5rem;
    font-style: italic;
    color: var(--title-color);
}
p {
    margin: 20px 0;
}
ul {
    list-style-type: disc;
    margin-left: 20px;
}
form {
    max-width: 600px;
    margin: 40px auto;
    padding: 20px;
    background-color: var(--form-bg);
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
    background-color: var(--button-bg);
    color: var(--button-text);
    padding: 15px 20px;
    border: none;
    cursor: pointer;
    border-radius: 3px;
    font-size: 1.2rem;
    font-weight: bold;
    display: block;
    margin: 0 auto;
}
form button:hover {
    background-color: var(--button-hover-bg);
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
.animated-lines {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    white-space: nowrap;
    font-size: 1.5rem;
    font-weight: bold;
}
.animated-line {
    display: inline-block;
    animation: scroll-left 20s linear infinite;
}
.animated-line:nth-child(2) {
    animation-direction: reverse;
}

@keyframes scroll-left {
    0% {
        transform: translateX(100%);
    }
    100% {
        transform: translateX(-100%);
    }
}

.services {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    justify-content: center;
}

.service-box {
    border: 1px solid var(--service-border);
    border-radius: 5px;
    padding: 20px;
    text-align: center;
    flex: 1 1 calc(33.333% - 2rem);
    box-sizing: border-box;
}

.service-icon {
    font-size: 3rem;
    color: var(--service-icon);
    margin-bottom: 10px;
}

.btn {
    display: inline-block;
    padding: 15px 30px;
    font-size: 1.2rem;
    font-weight: bold;
    border-radius: 5px;
    text-align: center;
    cursor: pointer;
    text-decoration: none;
    margin: 20px 10px;
}

.btn-primary {
    background-color: var(--button-bg);
    color: var(--button-text);
    border: 2px solid var(--button-bg);
}
.btn-primary:hover {
    background-color: var(--button-hover-bg);
    border-color: var(--button-hover-bg);
}
.btn-secondary {
    background-color: transparent;
    color: var(--button-bg);
    border: 2px solid var(--button-bg);
}
.btn-secondary:hover {
    color: var(--button-hover-bg);
    border-color: var(--button-hover-bg);
}
</style>

<div class="text-center">
    <h1>MAJANA</h1>
    <p class="description">We cut your cost</p>
    <p class="description">Your digital growth partner. Helping you achieve success through tailored marketing strategies.</p>
    <a href="#contact-form" class="btn btn-primary">Hire Us</a>
    <a href="/about" class="btn btn-secondary">Learn More</a>
</div>

<div class="section animated-lines">
    <div class="animated-line">Google Ads • Local SEO • Technical SEO • Media Buying • META Ads • TikTok Ads • Google Ranking • X Ads • Local Growth •</div>
    <div class="animated-line">Google Ads • Local SEO • Technical SEO • Media Buying • META Ads • TikTok Ads • Google Ranking • X Ads • Local Growth •</div>
</div>

<div class="section">
    <h2 class="text-center">Our Services</h2>
    <div class="container services">
        <div class="service-box">
            <div class="service-icon">📊</div>
            <h3 class="uppercase font-bold">Media Buying</h3>
            <p>Effective media buying strategies to maximize your ad spend and reach your target audience.</p>
        </div>
        <div class="service-box">
            <div class="service-icon">📍</div>
            <h3 class="uppercase font-bold">Local SEO</h3>
            <p>Improve your local search rankings and attract more customers to your business.</p>
        </div>
        <div class="service-box">
            <div class="service-icon">🎯</div>
            <h3 class="uppercase font-bold">Lead Generation</h3>
            <p>Generate high-quality leads to grow your business and increase sales.</p>
        </div>
        <div class="service-box">
            <div class="service-icon">📈</div>
            <h3 class="uppercase font-bold">Digital Marketing Strategy</h3>
            <p>Comprehensive digital marketing strategies to help you achieve your business goals.</p>
        </div>
    </div>
</div>

<div class="section">
    <h2 class="text-center">Contact Us</h2>
    <p class="text-center">If you have any questions or want to work with us, feel free to contact us through the form below.</p>
    <form id="contact-form" method='POST' name='contact'><input type='hidden' name='form-name' value='contact' />
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
