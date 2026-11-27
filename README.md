<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sumanth ❤️ Sinchana | Wedding Invitation</title>

<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Cinzel:wght@400;500;600&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>

/* ==============================
   PISTA GREEN LUXURY THEME
============================== */

:root {

    --pista: #B7C9A8;
    --pista-dark: #718568;
    --pista-light: #E3EBD9;

    --green: #344B3B;
    --deep-green: #1D3025;

    --ivory: #F8F6EC;
    --cream: #EFEBDD;

    --gold: #C6A96C;
    --gold-light: #E8D6A7;

    --white: #FFFFFF;
    --text: #405344;

}

* {

    margin: 0;
    padding: 0;
    box-sizing: border-box;

    scroll-behavior: smooth;

}

body {

    background: var(--ivory);

    color: var(--text);

    font-family: 'Poppins', sans-serif;

    overflow-x: hidden;

}


/* ==============================
   BACKGROUND DECORATION
============================== */

body::before {

    content: "";

    position: fixed;

    inset: 0;

    background-image:
    radial-gradient(rgba(198,169,108,.12) 1px, transparent 1px);

    background-size: 35px 35px;

    pointer-events: none;

    z-index: -1;

}


/* ==============================
   HERO SECTION
============================== */

.hero {

    min-height: 100vh;

    display: flex;

    justify-content: center;

    align-items: center;

    text-align: center;

    position: relative;

    padding: 40px 20px;

    perspective: 1200px;

    background:

    linear-gradient(
        rgba(29,48,37,.82),
        rgba(29,48,37,.92)
    ),

    url('1.png');

    background-size: cover;

    background-position: center;

    overflow: hidden;

}


/* Decorative border */

.hero::before {

    content: "";

    position: absolute;

    inset: 22px;

    border: 1px solid var(--gold);

    pointer-events: none;

}

.hero::after {

    content: "✧";

    position: absolute;

    top: 40px;

    color: var(--gold-light);

    font-size: 35px;

    animation: sparkle 3s infinite;

}


/* 3D CARD */

.hero-content {

    position: relative;

    z-index: 2;

    max-width: 750px;

    width: 100%;

    padding: 55px 35px;

    background:

    linear-gradient(
        145deg,
        rgba(248,246,236,.97),
        rgba(227,235,217,.94)
    );

    border: 2px solid var(--gold);

    outline: 1px solid rgba(198,169,108,.5);

    outline-offset: 8px;

    box-shadow:

    0 35px 80px rgba(0,0,0,.35),

    0 15px 30px rgba(0,0,0,.2),

    inset 0 0 30px rgba(255,255,255,.7);

    transform-style: preserve-3d;

    animation: cardEntrance 1.8s ease forwards,
               cardFloat 6s ease-in-out 2s infinite;

    transition: transform .5s ease;

}

.hero-content:hover {

    transform: rotateX(3deg) rotateY(-3deg) translateY(-8px);

}


/* Card animation */

@keyframes cardEntrance {

    0% {

        opacity: 0;

        transform: rotateX(20deg) translateY(100px) scale(.85);

    }

    100% {

        opacity: 1;

        transform: rotateX(0) translateY(0) scale(1);

    }

}

@keyframes cardFloat {

    0%,100% {

        translate: 0 0;

    }

    50% {

        translate: 0 -10px;

    }

}


.top-text {

    font-size: 11px;

    letter-spacing: 6px;

    color: var(--pista-dark);

    margin-bottom: 30px;

}


.hero h1 {

    font-family: 'Cinzel', serif;

    font-size: clamp(35px, 8vw, 65px);

    font-weight: 500;

    color: var(--green);

    margin: 12px 0;

    letter-spacing: 2px;

    text-shadow: 2px 3px 5px rgba(52,75,59,.12);

}


.ampersand {

    font-family: 'Cormorant Garamond', serif;

    font-size: 55px;

    color: var(--gold);

}


.hero-description {

    font-family: 'Cormorant Garamond', serif;

    font-size: 23px;

    line-height: 1.7;

    color: var(--text);

    margin-top: 25px;

}


.ornament {

    color: var(--gold);

    font-size: 27px;

    margin: 25px 0;

    animation: sparkle 3s infinite;

}


@keyframes sparkle {

    0%,100% {

        opacity: 1;

        text-shadow: 0 0 5px var(--gold);

    }

    50% {

        opacity: .55;

        text-shadow: 0 0 20px var(--gold);

    }

}


/* BUTTON */

.open-button {

    display: inline-block;

    margin-top: 35px;

    padding: 15px 40px;

    background: var(--green);

    color: var(--ivory);

    text-decoration: none;

    letter-spacing: 3px;

    font-size: 11px;

    border: 1px solid var(--gold);

    transition: .4s;

    box-shadow: 0 8px 20px rgba(52,75,59,.2);

}

.open-button:hover {

    background: var(--gold);

    color: var(--deep-green);

    transform: translateY(-5px);

    box-shadow: 0 15px 30px rgba(198,169,108,.35);

}


/* ==============================
   GENERAL SECTIONS
============================== */

section {

    padding: 100px 22px;

    position: relative;

}

.section-title {

    text-align: center;

    font-family: 'Cinzel', serif;

    font-size: clamp(30px, 6vw, 45px);

    color: var(--green);

    font-weight: 400;

    margin-bottom: 15px;

}

.subtitle {

    text-align: center;

    font-family: 'Cormorant Garamond', serif;

    font-size: 24px;

    color: var(--pista-dark);

    margin-bottom: 40px;

}

.divider {

    text-align: center;

    color: var(--gold);

    font-size: 25px;

    margin: 25px 0;

}


/* ==============================
   GALLERY
============================== */

.gallery-section {

    background:

    linear-gradient(
        135deg,
        #E5EBDD,
        #F8F6EC,
        #DCE7D5
    );

}

.gallery {

    display: flex;

    justify-content: center;

    max-width: 600px;

    margin: auto;

    perspective: 1000px;

}

.gallery-item {

    width: 100%;

    padding: 13px;

    background: var(--ivory);

    border: 2px solid var(--gold);

    box-shadow:

    0 25px 50px rgba(52,75,59,.2),

    0 10px 20px rgba(0,0,0,.1);

    transform: rotateY(-4deg);

    transition: .7s;

}

.gallery-item:hover {

    transform: rotateY(0deg) rotateX(3deg) translateY(-10px);

    box-shadow: 0 35px 65px rgba(52,75,59,.25);

}

.gallery img {

    width: 100%;

    height: 480px;

    object-fit: cover;

    display: block;

    cursor: pointer;

    transition: .6s;

}

.gallery img:hover {

    transform: scale(1.02);

}

.gallery-caption {

    text-align: center;

    padding: 20px;

    font-family: 'Cormorant Garamond', serif;

    color: var(--green);

    font-size: 27px;

}


/* ==============================
   COUNTDOWN
============================== */

.countdown-section {

    background:

    linear-gradient(
        135deg,
        #263E30,
        #405B45,
        #203629
    );

}

.countdown-section .section-title {

    color: var(--pista-light);

}

.countdown-section .subtitle {

    color: var(--pista);

}

.countdown {

    display: flex;

    justify-content: center;

    flex-wrap: wrap;

    gap: 22px;

    margin-top: 45px;

}

.countdown-box {

    width: 130px;

    padding: 25px 10px;

    text-align: center;

    background: rgba(248,246,236,.08);

    border: 1px solid var(--gold);

    backdrop-filter: blur(15px);

    box-shadow: 0 10px 30px rgba(0,0,0,.15);

    transition: .4s;

}

.countdown-box:hover {

    transform: translateY(-12px) scale(1.06);

    background: rgba(248,246,236,.16);

}

.count-number {

    font-family: 'Cinzel', serif;

    font-size: 40px;

    color: var(--gold-light);

}

.count-label {

    font-size: 10px;

    letter-spacing: 2px;

    color: var(--pista-light);

    margin-top: 10px;

}


/* ==============================
   WEDDING DETAILS
============================== */

.details-section {

    background: var(--ivory);

}

.details-card {

    max-width: 700px;

    margin: auto;

    padding: 55px 25px;

    text-align: center;

    position: relative;

    background:

    linear-gradient(
        145deg,
        #F8F6EC,
        #E3EBD9
    );

    border: 2px solid var(--gold);

    box-shadow:

    0 30px 60px rgba(52,75,59,.15),

    inset 0 0 30px rgba(255,255,255,.8);

    transition: .6s;

}

.details-card:hover {

    transform: perspective(1000px) rotateX(3deg) translateY(-8px);

    box-shadow: 0 40px 70px rgba(52,75,59,.22);

}

.details-card::before {

    content: "";

    position: absolute;

    inset: 10px;

    border: 1px solid rgba(198,169,108,.6);

    pointer-events: none;

}

.details-date {

    font-family: 'Cinzel', serif;

    font-size: clamp(25px, 5vw, 36px);

    color: var(--green);

    margin: 25px 0;

}

.details-text {

    font-family: 'Cormorant Garamond', serif;

    font-size: 25px;

    line-height: 2;

    color: var(--text);

}

.details-text b {

    color: var(--pista-dark);

}

.map-button {

    display: inline-block;

    margin-top: 35px;

    padding: 15px 35px;

    color: var(--ivory);

    background: var(--green);

    border: 1px solid var(--gold);

    text-decoration: none;

    font-size: 11px;

    letter-spacing: 2px;

    transition: .4s;

}

.map-button:hover {

    background: var(--gold);

    color: var(--deep-green);

    transform: translateY(-5px);

}


/* ==============================
   CLOSING SECTION
============================== */

.closing {

    background:

    linear-gradient(
        135deg,
        #E3EBD9,
        #F8F6EC
    );

    text-align: center;

}

.closing-card {

    max-width: 750px;

    margin: auto;

    padding: 50px 25px;

    background: rgba(255,255,255,.5);

    border: 1px solid var(--gold);

    box-shadow: 0 20px 50px rgba(52,75,59,.1);

    transition: .5s;

}

.closing-card:hover {

    transform: scale(1.02);

}

.closing-card p {

    font-family: 'Cormorant Garamond', serif;

    font-size: 25px;

    line-height: 1.8;

    color: var(--text);

}

.signature {

    font-family: 'Cinzel', serif;

    font-size: clamp(23px, 5vw, 38px);

    color: var(--green);

    margin-top: 30px;

}


/* ==============================
   FOOTER
============================== */

footer {

    background: var(--deep-green);

    padding: 45px 20px;

    text-align: center;

    color: var(--pista-light);

    font-family: 'Cormorant Garamond', serif;

    font-size: 22px;

}


/* ==============================
   FLOATING GOLDEN PARTICLES
============================== */

.petal {

    position: fixed;

    top: -40px;

    z-index: 100;

    pointer-events: none;

    color: var(--gold);

    animation: falling linear infinite;

}

@keyframes falling {

    0% {

        transform: translateY(-50px) rotate(0deg);

        opacity: 0;

    }

    15% {

        opacity: .8;

    }

    100% {

        transform: translateY(110vh) rotate(360deg);

        opacity: 0;

    }

}


/* ==============================
   MUSIC BUTTON
============================== */

#musicBtn {

    position: fixed;

    bottom: 25px;

    right: 20px;

    height: 58px;

    width: 58px;

    border-radius: 50%;

    background: var(--green);

    color: var(--gold-light);

    border: 1px solid var(--gold);

    font-size: 23px;

    cursor: pointer;

    z-index: 999;

    box-shadow: 0 8px 25px rgba(52,75,59,.3);

    transition: .4s;

}

#musicBtn:hover {

    transform: rotate(20deg) scale(1.1);

}

#musicBtn.playing {

    animation: musicPulse 2s infinite;

}

@keyframes musicPulse {

    0%,100% {

        box-shadow: 0 0 10px rgba(198,169,108,.3);

    }

    50% {

        box-shadow: 0 0 30px rgba(198,169,108,.8);

    }

}


/* ==============================
   IMAGE VIEWER
============================== */

.viewer {

    position: fixed;

    inset: 0;

    background: rgba(20,35,25,.96);

    display: none;

    justify-content: center;

    align-items: center;

    z-index: 2000;

    padding: 20px;

    backdrop-filter: blur(10px);

}

.viewer img {

    max-width: 95%;

    max-height: 85vh;

    border: 2px solid var(--gold);

    box-shadow: 0 20px 60px rgba(0,0,0,.5);

    animation: imageZoom .5s ease;

}

@keyframes imageZoom {

    from {

        transform: scale(.7);

        opacity: 0;

    }

    to {

        transform: scale(1);

        opacity: 1;

    }

}

.close {

    position: absolute;

    top: 25px;

    right: 30px;

    color: var(--gold-light);

    font-size: 40px;

    cursor: pointer;

}


/* ==============================
   SCROLL REVEAL
============================== */

.reveal {

    opacity: 0;

    transform: translateY(50px);

    transition: opacity 1s ease, transform 1s ease;

}

.reveal.active {

    opacity: 1;

    transform: translateY(0);

}


/* ==============================
   MOBILE RESPONSIVE
============================== */

@media(max-width:600px) {

    section {

        padding: 70px 18px;

    }

    .hero-content {

        padding: 45px 20px;

    }

    .hero h1 {

        font-size: 37px;

    }

    .top-text {

        letter-spacing: 3px;

    }

    .gallery img {

        height: 350px;

    }

    .countdown {

        gap: 12px;

    }

    .countdown-box {

        width: 105px;

        padding: 20px 5px;

    }

    .count-number {

        font-size: 30px;

    }

    .details-card {

        padding: 40px 18px;

    }

}


/* REDUCED MOTION ACCESSIBILITY */

@media(prefers-reduced-motion: reduce) {

    *,
    *::before,
    *::after {

        animation-duration: .01ms !important;

        animation-iteration-count: 1 !important;

        scroll-behavior: auto !important;

        transition-duration: .01ms !important;

    }

}

</style>

</head>


<body>


<!-- ==============================
     HERO / INVITATION CARD
============================== -->

<div class="hero">

    <div class="hero-content">

        <div class="top-text">

            TOGETHER WITH OUR FAMILIES

        </div>

        <div class="ornament">

            ✧ ───── ❦ ───── ✧

        </div>

        <h1>Sumanth S</h1>

        <div class="ampersand">&</div>

        <h1>Sinchana P</h1>

        <div class="ornament">

            ✧ ───── ❦ ───── ✧

        </div>

        <div class="hero-description">

            Two souls, one beautiful journey.<br>

            Together with our families<br>

            request the pleasure of your presence<br>

            to celebrate our wedding.

        </div>

        <a href="#gallery" class="open-button">

            EXPLORE OUR INVITATION

        </a>

    </div>

</div>



<!-- ==============================
     OUR JOURNEY
============================== -->

<section class="gallery-section reveal" id="gallery">

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



<!-- ==============================
     COUNTDOWN
============================== -->

<section class="countdown-section reveal">

    <h2 class="section-title">

        Save The Date

    </h2>

    <p class="subtitle">

        The countdown to our forever begins.

    </p>

    <div class="divider">

        ✧ ───── ❦ ───── ✧

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



<!-- ==============================
     WEDDING DETAILS
============================== -->

<section class="details-section reveal">

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

            ───── ❦ ─────

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



<!-- ==============================
     CLOSING MESSAGE
============================== -->

<section class="closing reveal">

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



<!-- ==============================
     FOOTER
============================== -->

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


/* ==============================
   COUNTDOWN
============================== */

const weddingDate = new Date(

    "2026-12-25T12:25:00+05:30"

).getTime();


function updateCountdown() {

    const now = Date.now();

    const distance = weddingDate - now;

    if (distance <= 0) {

        document.getElementById("countdown").innerHTML =

        "<h2 style='color:#E8D6A7'>The Wedding Day Has Arrived! ❤️</h2>";

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


let countdownTimer;

updateCountdown();

countdownTimer = setInterval(updateCountdown, 1000);



/* ==============================
   FLOATING GOLD DECORATIONS
============================== */

const petals = [

    "✧",

    "❀",

    "✦",

    "❋",

    "❦"

];

for (let i = 0; i < 22; i++) {

    const petal = document.createElement("div");

    petal.className = "petal";

    petal.innerHTML =

    petals[Math.floor(Math.random() * petals.length)];

    petal.style.left =

    Math.random() * 100 + "vw";

    petal.style.fontSize =

    (15 + Math.random() * 18) + "px";

    petal.style.animationDuration =

    (8 + Math.random() * 10) + "s";

    petal.style.animationDelay =

    Math.random() * 8 + "s";

    document.body.appendChild(petal);

}



/* ==============================
   SCROLL REVEAL ANIMATION
============================== */

const observer = new IntersectionObserver(

    entries => {

        entries.forEach(entry => {

            if (entry.isIntersecting) {

                entry.target.classList.add("active");

                observer.unobserve(entry.target);

            }

        });

    },

    {

        threshold: 0.12

    }

);


document.querySelectorAll(".reveal").forEach(section => {

    observer.observe(section);

});



/* ==============================
   BACKGROUND MUSIC
============================== */

const music = document.getElementById("music");

const musicBtn = document.getElementById("musicBtn");

let playing = false;


musicBtn.addEventListener("click", async function() {

    if (!playing) {

        try {

            await music.play();

            musicBtn.innerHTML = "⏸";

            musicBtn.classList.add("playing");

            playing = true;

        }

        catch(error) {

            alert("Please upload music.mp3 to your repository.");

        }

    }

    else {

        music.pause();

        musicBtn.innerHTML = "🎵";

        musicBtn.classList.remove("playing");

        playing = false;

    }

});



/* ==============================
   IMAGE VIEWER
============================== */

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
