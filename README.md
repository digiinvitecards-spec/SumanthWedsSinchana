<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sumanth ❤️ Sinchana | Wedding Invitation</title>

<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Cinzel:wght@400;500;600&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>

:root {
    --black: #080C14;
    --dark: #101827;
    --card: #151F30;
    --blue: #A9C8E8;
    --lightblue: #DCEBFA;
    --silver: #BFCBDA;
    --white: #F5F7FA;
    --muted: #A5B1C0;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    background: var(--black);
    color: var(--white);
    font-family: 'Poppins', sans-serif;
    overflow-x: hidden;
}

/* HERO SECTION */

.hero {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    position: relative;
    padding: 35px 20px;

    background:
    linear-gradient(
        rgba(5,10,20,.72),
        rgba(5,10,20,.85)
    ),
    url('1.png');

    background-size: cover;
    background-position: center;
}

.hero::before {
    content: "";
    position: absolute;
    inset: 20px;
    border: 1px solid var(--blue);
    pointer-events: none;
}

.hero::after {
    content: "✧";
    position: absolute;
    top: 45px;
    color: var(--blue);
    font-size: 35px;
}

.hero-content {
    position: relative;
    z-index: 2;
    max-width: 750px;
    animation: fadeIn 2s ease;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(30px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.top-text {
    font-size: 12px;
    letter-spacing: 6px;
    color: var(--silver);
    margin-bottom: 35px;
}

.hero h1 {
    font-family: 'Cinzel', serif;
    font-size: clamp(38px, 8vw, 72px);
    font-weight: 400;
    color: var(--blue);
    margin: 15px 0;
    letter-spacing: 2px;
}

.ampersand {
    font-family: 'Cormorant Garamond', serif;
    font-size: 55px;
    color: var(--silver);
    margin: 5px;
}

.hero-description {
    font-family: 'Cormorant Garamond', serif;
    font-size: 24px;
    color: var(--white);
    line-height: 1.7;
    margin-top: 25px;
}

.ornament {
    color: var(--blue);
    font-size: 28px;
    margin: 25px 0;
}

.open-button {
    display: inline-block;
    margin-top: 35px;
    padding: 15px 40px;
    border: 1px solid var(--blue);
    color: var(--lightblue);
    text-decoration: none;
    letter-spacing: 3px;
    font-size: 12px;
    transition: .4s;
}

.open-button:hover {
    background: var(--blue);
    color: var(--black);
    box-shadow: 0 0 25px rgba(169,200,232,.3);
}

/* GENERAL SECTIONS */

section {
    padding: 90px 22px;
    position: relative;
}

.section-title {
    text-align: center;
    font-family: 'Cinzel', serif;
    font-size: clamp(30px, 6vw, 45px);
    color: var(--blue);
    font-weight: 400;
    margin-bottom: 15px;
}

.subtitle {
    text-align: center;
    font-family: 'Cormorant Garamond', serif;
    font-size: 23px;
    color: var(--muted);
    margin-bottom: 45px;
}

.divider {
    text-align: center;
    color: var(--blue);
    font-size: 25px;
    margin: 25px 0;
}

/* PHOTO GALLERY */

.gallery-section {
    background: var(--dark);
}

.gallery {
    display: flex;
    justify-content: center;
    max-width: 650px;
    margin: auto;
}

.gallery-item {
    width: 100%;
    background: var(--card);
    padding: 10px;
    border: 1px solid rgba(169,200,232,.35);
    overflow: hidden;
}

.gallery img {
    width: 100%;
    height: 450px;
    object-fit: cover;
    display: block;
    cursor: pointer;
    transition: .6s;
}

.gallery img:hover {
    transform: scale(1.04);
}

.gallery-caption {
    text-align: center;
    padding: 18px;
    font-family: 'Cormorant Garamond', serif;
    color: var(--blue);
    font-size: 24px;
}

/* COUNTDOWN */

.countdown-section {
    background:
    linear-gradient(
        135deg,
        #080C14,
        #17253A,
        #080C14
    );
}

.countdown {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 45px;
}

.countdown-box {
    width: 125px;
    padding: 25px 10px;
    text-align: center;
    background: rgba(255,255,255,.04);
    border: 1px solid rgba(169,200,232,.5);
    backdrop-filter: blur(10px);
    transition: .3s;
}

.countdown-box:hover {
    transform: translateY(-8px);
    background: rgba(169,200,232,.1);
}

.count-number {
    font-family: 'Cinzel', serif;
    font-size: 38px;
    color: var(--blue);
}

.count-label {
    font-size: 11px;
    letter-spacing: 2px;
    color: var(--silver);
    margin-top: 10px;
}

/* WEDDING DETAILS */

.details-section {
    background: var(--black);
}

.details-card {
    max-width: 700px;
    margin: auto;
    padding: 50px 25px;
    text-align: center;

    background: linear-gradient(
        145deg,
        #172235,
        #0D1421
    );

    border: 1px solid rgba(169,200,232,.5);
    box-shadow: 0 20px 60px rgba(0,0,0,.4);
    position: relative;
}

.details-card::before {
    content: "";
    position: absolute;
    inset: 9px;
    border: 1px solid rgba(169,200,232,.2);
    pointer-events: none;
}

.details-date {
    font-family: 'Cinzel', serif;
    font-size: clamp(25px, 5vw, 36px);
    color: var(--blue);
    margin: 25px 0;
}

.details-text {
    font-family: 'Cormorant Garamond', serif;
    font-size: 25px;
    line-height: 2;
    color: var(--white);
}

.details-text b {
    color: var(--blue);
}

.map-button {
    display: inline-block;
    margin-top: 35px;
    padding: 14px 35px;
    color: var(--black);
    background: var(--blue);
    text-decoration: none;
    font-size: 12px;
    letter-spacing: 2px;
    transition: .3s;
}

.map-button:hover {
    background: var(--lightblue);
    box-shadow: 0 0 25px rgba(169,200,232,.3);
}

/* CLOSING */

.closing {
    background: var(--dark);
    text-align: center;
}

.closing-card {
    max-width: 750px;
    margin: auto;
    padding: 45px 20px;
    border: 1px solid rgba(169,200,232,.4);
}

.closing-card p {
    font-family: 'Cormorant Garamond', serif;
    font-size: 25px;
    line-height: 1.8;
    color: var(--silver);
}

.signature {
    font-family: 'Cinzel', serif;
    font-size: clamp(25px, 5vw, 40px);
    color: var(--blue);
    margin-top: 30px;
}

/* FOOTER */

footer {
    background: #05080E;
    padding: 45px 20px;
    text-align: center;
    color: var(--muted);
    font-family: 'Cormorant Garamond', serif;
    font-size: 21px;
}

/* FLOATING PETALS */

.petal {
    position: fixed;
    top: -40px;
    z-index: 100;
    pointer-events: none;
    color: var(--blue);
    animation: falling linear infinite;
}

@keyframes falling {
    0% {
        transform: translateY(-50px) rotate(0deg);
        opacity: 0;
    }

    15% {
        opacity: .7;
    }

    100% {
        transform: translateY(110vh) rotate(360deg);
        opacity: 0;
    }
}

/* MUSIC BUTTON */

#musicBtn {
    position: fixed;
    bottom: 25px;
    right: 20px;
    height: 55px;
    width: 55px;
    border-radius: 50%;
    background: var(--blue);
    color: var(--black);
    border: 1px solid var(--silver);
    font-size: 22px;
    cursor: pointer;
    z-index: 999;
    box-shadow: 0 5px 25px rgba(169,200,232,.2);
}

/* IMAGE VIEWER */

.viewer {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,.96);
    display: none;
    justify-content: center;
    align-items: center;
    z-index: 2000;
    padding: 20px;
}

.viewer img {
    max-width: 95%;
    max-height: 85vh;
    border: 1px solid var(--blue);
}

.close {
    position: absolute;
    top: 25px;
    right: 30px;
    color: white;
    font-size: 40px;
    cursor: pointer;
}

/* MOBILE RESPONSIVE */

@media(max-width:600px) {

    section {
        padding: 65px 18px;
    }

    .gallery img {
        height: 350px;
    }

    .countdown-box {
        width: 105px;
        padding: 20px 5px;
    }

    .count-number {
        font-size: 29px;
    }

    .details-card {
        padding: 40px 18px;
    }

    .top-text {
        letter-spacing: 3px;
    }

}

</style>

</head>

<body>

<!-- OPENING INVITATION -->

<div class="hero">

<div class="hero-content">

<div class="top-text">
A BEAUTIFUL BEGINNING
</div>

<div class="ornament">✧ ─── ❦ ─── ✧</div>

<h1>Sumanth S</h1>

<div class="ampersand">&</div>

<h1>Sinchana P</h1>

<div class="ornament">✧ ─── ❦ ─── ✧</div>

<div class="hero-description">

Together with our families<br>

request the pleasure of your presence<br>

to celebrate our wedding.

</div>

<a href="#gallery" class="open-button">
EXPLORE INVITATION
</a>

</div>

</div>


<!-- OUR JOURNEY: ONLY ONE IMAGE -->

<section class="gallery-section" id="gallery">

<h2 class="section-title">
Our Journey
</h2>

<p class="subtitle">
Two hearts. One beautiful forever.
</p>

<div class="divider">
✧ ❦ ✧
</div>

<div class="gallery">

<div class="gallery-item">

<img src="3.png" alt="Sumanth and Sinchana">

<div class="gallery-caption">
Our Forever Story
</div>

</div>

</div>

</section>


<!-- COUNTDOWN -->

<section class="countdown-section">

<h2 class="section-title">
Save The Date
</h2>

<p class="subtitle">
The countdown to our forever begins.
</p>

<div class="divider">
✧ ─── ❦ ─── ✧
</div>

<div class="countdown" id="countdown">

<div class="countdown-box">
<div class="count-number" id="days">00</div>
<div class="count-label">DAYS</div>
</div>

<div class="countdown-box">
<div class="count-number" id="hours">00</div>
<div class="count-label">HOURS</div>
</div>

<div class="countdown-box">
<div class="count-number" id="minutes">00</div>
<div class="count-label">MINUTES</div>
</div>

<div class="countdown-box">
<div class="count-number" id="seconds">00</div>
<div class="count-label">SECONDS</div>
</div>

</div>

</section>


<!-- WEDDING DETAILS -->

<section class="details-section">

<h2 class="section-title">
Wedding Celebration
</h2>

<p class="subtitle">
A day filled with love, blessings and happiness.
</p>

<div class="details-card">

<div class="ornament">✧</div>

<div class="details-date">
25 December 2026
</div>

<div class="divider">
──── ❦ ────
</div>

<div class="details-text">

🕙 <b>Muhurtham</b>

<br>

12:25 PM Onwards

<br><br>

📍 <b>Kannada Bhavana</b>

<br>

Near Swaraj Maidan

<br>

Moodbidri

</div>

<a
class="map-button"
href="https://maps.app.goo.gl/vP5ina9rLYnSjTJo8"
target="_blank"
rel="noopener">

VIEW VENUE LOCATION

</a>

</div>

</section>


<!-- CLOSING -->

<section class="closing">

<h2 class="section-title">
We Await Your Presence
</h2>

<div class="divider">
✧ ❦ ✧
</div>

<div class="closing-card">

<p>

Your presence will make our celebration
more joyful and memorable.

<br><br>

We cannot wait to celebrate
our forever with you.

</p>

<div class="signature">
Sumanth S ❤️ Sinchana P
</div>

<br>

<p>
25 December 2026
</p>

</div>

</section>


<!-- FOOTER -->

<footer>

<div class="divider">
✧ ❦ ✧
</div>

Made with Love ❤️

<br>

Sumanth S & Sinchana P

</footer>


<!-- MUSIC BUTTON -->

<button id="musicBtn" aria-label="Play background music">
🎵
</button>

<audio id="music" loop>

<source src="music.mp3" type="audio/mpeg">

</audio>


<!-- IMAGE VIEWER -->

<div class="viewer" id="viewer">

<span class="close" id="closeViewer">&times;</span>

<img id="preview" src="" alt="Full size photograph">

</div>


<script>

/* COUNTDOWN */

const weddingDate = new Date(
    "2026-12-25T12:25:00+05:30"
).getTime();

function updateCountdown() {

    const now = Date.now();

    const distance = weddingDate - now;

    if (distance <= 0) {

        document.getElementById("countdown").innerHTML =
        "<h2 style='color:#A9C8E8'>The Wedding Day Has Arrived! ❤️</h2>";

        clearInterval(countdownTimer);

        return;

    }

    const days = Math.floor(
        distance / (1000 * 60 * 60 * 24)
    );

    const hours = Math.floor(
        (distance % (1000 * 60 * 60 * 24)) /
        (1000 * 60 * 60)
    );

    const minutes = Math.floor(
        (distance % (1000 * 60 * 60)) /
        (1000 * 60)
    );

    const seconds = Math.floor(
        (distance % (1000 * 60)) / 1000
    );

    document.getElementById("days").innerText = days;
    document.getElementById("hours").innerText = hours;
    document.getElementById("minutes").innerText = minutes;
    document.getElementById("seconds").innerText = seconds;

}

updateCountdown();

const countdownTimer = setInterval(updateCountdown, 1000);


/* FLOATING BLUE DECORATIONS */

const petals = ["✧", "❀", "✦", "❋"];

for (let i = 0; i < 18; i++) {

    const petal = document.createElement("div");

    petal.className = "petal";

    petal.innerHTML =
    petals[Math.floor(Math.random() * petals.length)];

    petal.style.left =
    Math.random() * 100 + "vw";

    petal.style.fontSize =
    (15 + Math.random() * 18) + "px";

    petal.style.animationDuration =
    (8 + Math.random() * 8) + "s";

    petal.style.animationDelay =
    Math.random() * 8 + "s";

    document.body.appendChild(petal);

}


/* SCROLL ANIMATION */

const observer = new IntersectionObserver(entries => {

    entries.forEach(entry => {

        if (entry.isIntersecting) {

            entry.target.animate(
                [
                    {
                        opacity: 0,
                        transform: "translateY(35px)"
                    },

                    {
                        opacity: 1,
                        transform: "translateY(0)"
                    }
                ],

                {
                    duration: 1000,
                    fill: "forwards"
                }
            );

            observer.unobserve(entry.target);

        }

    });

}, { threshold: 0.1 });

document.querySelectorAll("section").forEach(section => {

    observer.observe(section);

});


/* BACKGROUND MUSIC */

const music = document.getElementById("music");

const musicBtn = document.getElementById("musicBtn");

let playing = false;

musicBtn.addEventListener("click", async function() {

    if (!playing) {

        try {

            await music.play();

            musicBtn.innerHTML = "⏸";

            playing = true;

        }

        catch(error) {

            alert("Please upload music.mp3 to your repository.");

        }

    }

    else {

        music.pause();

        musicBtn.innerHTML = "🎵";

        playing = false;

    }

});


/* SINGLE PHOTO VIEWER */

const viewer = document.getElementById("viewer");

const preview = document.getElementById("preview");

document.querySelectorAll(".gallery img").forEach(img => {

    img.addEventListener("click", function() {

        viewer.style.display = "flex";

        preview.src = this.src;

    });

});

document.getElementById("closeViewer").onclick = function() {

    viewer.style.display = "none";

};

viewer.onclick = function(event) {

    if (event.target === viewer) {

        viewer.style.display = "none";

    }

};

document.addEventListener("keydown", function(event) {

    if (event.key === "Escape") {

        viewer.style.display = "none";

    }

});

</script>

</body>

</html>
