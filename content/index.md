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
    margin: 0;
    padding: 0;
}
h1, h2, h3 {
    color: #4CAF50;
}
h1 {
    font-size: 3rem;
}
h2 {
    font-size: 2.5rem;
    border-bottom: 2px solid #4CAF50;
    padding-bottom: 10px;
    margin-top: 40px;
}
h3 {
    font-size: 2rem;
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

.marquee {
    width: 100%;
    white-space: nowrap;
    overflow: hidden;
    position: relative;
    box-sizing: border-box;
    background: black;
    padding: 1rem 0;
    margin: 0;
}

.marquee span {
    display: inline-block;
    padding-left: 100%;
    animation: marquee 15s linear infinite;
    font-size: 1.5rem;
    font-weight: bold;
    color: #4CAF50;
}

.marquee2 {
    width: 100%;
    white-space: nowrap;
    overflow: hidden;
    position: relative;
    box-sizing: border-box;
    background: black;
    padding: 1rem 0;
    margin: 0;
    transform: rotateX(180deg);
}

.marquee2 span {
    display: inline-block;
    padding-left: 100%;
    animation: marquee2 15s linear infinite;
    font-size: 1.5rem;
    font-weight: bold;
    color: #4CAF50;
    transform: rotateX(180deg);
}

@keyframes marquee {
    0% { transform: translate(0, 0); }
    100% { transform: translate(-100%, 0); }
}

@keyframes marquee2 {
    0% { transform: translate(0, 0); }
    100% { transform: translate(100%, 0); }
}
</style>

<div class="section text-center">
    <h1 class="uppercase font-bold">Majana</h1>
    <p>Welcome to Majana, where we elevate your business through strategic marketing. Our team of experts is dedicated to helping you achieve your business goals with tailored marketing strategies.</p>
</div>

<div class="marquee">
    <span>Google Ranking • Google Maps • Media Buying • Local SEO • Lead Generation • Digital Marketing Strategy</span>
</div>
<div class="marquee2">
    <span>Google Ranking • Google Maps • Media Buying • Local SEO • Lead Generation • Digital Marketing Strategy</span>
</div>

<div class="section">
    <h2 class="text-center">Our Services</h2>
    <div class="container flex flex-col lg:flex-row gap-4 lg:gap-8 justify-center">
        <div class="lg:max-w-[50%] 2xl:max-w-[33%] text-center">
            <h3 class="uppercase font-bold">Media Buying</h3>
            <p>Effective media buying strategies to maximize your ROI.</p>
        </div>
        <div class="lg:max-w-[50%] 2xl:max-w-[33%] text-center">
            <h3 class="uppercase font-bold">Local SEO</h3>
            <p>Boost your local presence and attract more customers.</p>
        </div>
        <div class="lg:max-w-[50%] 2xl:max-w-[33%] text-center">
            <h3 class="uppercase font-bold">Lead Generation</h3>
            <p>Generate high-quality leads for your business.</p>
        </div>
        <div class="lg:max-w-[50%] 2xl:max-w-[33%] text-center">
            <h3 class="uppercase font-bold">Digital Marketing Strategy</h3>
            <p>Customized digital marketing strategies for your business.</p>
        </div>
    </div>
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
