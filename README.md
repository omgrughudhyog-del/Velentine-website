# Velentine-website
<! html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Pretty Boy 💕</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #ffd6e8, #ffc2e2);
    text-align: center;
    color: #333;
}

.section {
    padding: 40px 20px;
}

h1, h2 {
    color: #ff4d88;
}

img {
    max-width: 300px;
    width: 90%;
    border-radius: 20px;
    margin: 20px 0;
}

button {
    background: #ff4d88;
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 25px;
    cursor: pointer;
    margin: 10px;
    font-size: 16px;
}

button:hover {
    background: #ff1a66;
}

input, textarea {
    width: 80%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 10px;
    border: 1px solid #ccc;
}

.hidden {
    display: none;
}

#passwordPage {
    position: fixed;
    background: #ffd6e8;
    width: 100%;
    height: 100%;
    padding-top: 150px;
}

/* Floating Hearts */
.heart {
    position: fixed;
    bottom: -10px;
    font-size: 20px;
    animation: float 6s linear infinite;
}

@keyframes float {
    0% { transform: translateY(0); opacity: 1; }
    100% { transform: translateY(-800px); opacity: 0; }
}
</style>

<script>
function checkPassword() {
    var pass = document.getElementById("passwordInput").value;
    if(pass === "03082025") {
        document.getElementById("passwordPage").style.display = "none";
    } else {
        alert("Wrong password Pretty Boy 😌");
    }
}

function showLove() {
    document.getElementById("loveMsg").style.display = "block";
}

function showLetter() {
    document.getElementById("letter").style.display = "block";
}

/* Time Since We Met */
var loveStartDate = new Date("July 27, 2025 00:00:00").getTime();

setInterval(function() {
  var now = new Date().getTime();
  var difference = now - loveStartDate;

  var days = Math.floor(difference / (1000 * 60 * 60 * 24));
  var hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((difference % (1000 * 60)) / 1000);

  document.getElementById("loveTime").innerHTML =
    days + " Days 💕 " +
    hours + " Hours 💗 " +
    minutes + " Minutes 💘 " +
    seconds + " Seconds";
}, 1000);

/* Floating Hearts */
setInterval(function() {
  var heart = document.createElement("div");
  heart.className = "heart";
  heart.innerHTML = "💖";
  heart.style.left = Math.random() * 100 + "vw";
  heart.style.fontSize = (Math.random() * 20 + 10) + "px";
  document.body.appendChild(heart);
  setTimeout(function(){ heart.remove(); }, 6000);
}, 600);
</script>

</head>
<body>

<!-- PASSWORD PAGE -->
<div id="passwordPage">
    <h2>Enter Password 💕</h2>
    <input type="password" id="passwordInput" placeholder="Enter our secret date">
    <br>
    <button onclick="checkPassword()">Open My Surprise 💖</button>
</div>

<!-- COVER -->
<div class="section">
    <h1>Hi My Love 💖</h1>
    <p>
This is just a small surprise from your Cutuuu to remind you how special you are to me. I hope this makes you smile the way you make me smile every day 😍💖
    </p>
</div>

<!-- TIME TOGETHER -->
<div class="section">
    <h2>💖 Together Since 27 July 2025 💖</h2>
    <div id="loveTime" style="font-size:20px;font-weight:bold;"></div>
</div>

<!-- LETTER -->
<div class="section">
<button onclick="showLetter()">Open My Heart 💌</button>

<div id="letter" class="hidden">
<img src="https://i.ibb.co/ynLj2R5K/IMG-20260202-WA0015.jpg">

<p style="max-width:600px;margin:auto;line-height:1.8;">
To my pretty boy 💌❤️  
I’m writing this digital love letter for you, and I honestly don’t even know where to start… because every time I think about you, I just smile. You came into my life so softly, but now you have no idea how much you mean to me. The way you talk, the way you laugh, the way you care… it all feels so special. I love youuu so, so, so much 😭
From the moment I open my eyes till the moment I close them, you stay in my mind every second. Your eyes are the prettiest. Your smile is the most beautiful smile — it heals my soul. I love you so much, my lovee. I’m so grateful that you exist. With you, life feels amazing 😍 Thank you for being with me 🥰 You make my ordinary days feel exciting. Even a simple conversation with you becomes my favorite part of the day.
When I call you “Pretty Boy,” it’s not just a nickname — it’s the way I see you. Handsome, sweet, and someone who makes my heart feel safe. You have the most beautiful heart, and that’s what makes you truly “pretty” to me. The way you care, the way you understand me even when I don’t say much, the way you stay… it means more than you will ever know 😭🥺🫂
I promise I am, and I’ll always be by your side — standing beside you, cherishing every moment with you. No matter what hurdles life may give us, we both will figure them out. I believe in you & I believe in US ❤️🤞🏻 I know no human can be happy always, but promise me that you’ll be happy, you’ll be sad, you’ll feel everything with ME. We both are going to figure everything out. You’re never alone — you’ll always have me as your lover, darling, friend, therapist, bed partner, life partner, business partner… literally EVERYTHING!! 😚😚
You made my life so, so, so, so much better. Thank you for coming into my life when I wasn’t even expecting a miracle. Thanks for being the miracle 💫 Sometimes I sit and think about how you came into my life, and I honestly thank God for you. You are not just someone I love — you are someone who feels like home to me. Your smile calms my storms, your voice feels like comfort, and your presence alone makes everything better.🩷🩵
Loving you feels soft, pure, and real. With you, I don’t have to pretend to be someone else. I can be my true self, and you still choose me. That’s what makes our love so special. I’m so grateful for every laugh, every hug, every little moment we share. I promise to stand by you, support you, and love you in every season of life. I’m so grateful for every memory we’re creating. I don’t know what the future holds, but I know I’m happy choosing you today — and that happiness is real and pure.
You are my first love, and my heart’s most beautiful beginning. And this Valentine, I just want to ask you… will you be my last love too? Will you be my forever, my always, my once-in-a-lifetime? Because I don’t just want you for today — I want you for every tomorrow. I choose you not only now, but in every version of my future ♾️🤍🌷
My pretty boy, you are my heart’s favorite person, my safe place, and my sweetest blessing. Today and always, I choose you. Forever yours 🧿❤️✨
I love youuu so, so, so, so, so SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO SO muuuuuuuuccccccchhhhhhhhhhh 🫂🥺😭😭😭
And when we meet, I’ll make sure to make you my dinner, lunch, breakfast & dessert 😋🤤🤭😂 I know you’re giggling now, mereeeeeeee ghanduuuuuu insaaaan 🥺🫂❤️🤗
Happy Valentine's Day 💕
Forever cheering for us, 
Your Cutuuuu 💌✨
</p>
</div>
</div>

<!-- QUESTIONS -->
<div class="section">
<h2>Answer These For Me 🥺</h2>

<form action="https://formspree.io/f/xbdagbkg" method="POST">
<p>1. When did you first realize you liked me?</p>
<textarea name="Q1"></textarea>

<p>2. What's your favourite memory of us?</p>
<textarea name="Q2"></textarea>

<p>3. One thing you promise to do always for us</p>
<textarea name="Q3"></textarea>

<p>4. What is one thing you love most about me?</p>
<textarea name="Q4"></textarea>

<p>5. When do you feel most loved by me?</p>
<textarea name="Q5"></textarea>

<button type="submit">Send Answers 💕</button>
</form>
</div>

<!-- AGREEMENT -->
<div class="section">
<h2>💘 Mini Relationship Agreement 💘</h2>
<p>Between: Me 🤍 & My ghanduuu ❤️</p>
<p>We promise to love each other daily (no skipping allowed 😌)</p>
<p>Loyalty is permanent, no trial version</p>
<p>Arguments allowed, but ignoring each other is illegal. 🚫</p>
<p>Unlimited hugs, kisses & “I miss you” texts are compulsory. 💋</p>
<p>Pretty Boy belongs to me, and I proudly belong to him.
This contract is valid for lifetime… no cancellation policy available 😉💞</p>
<button onclick="alert('Agreement Accepted 😌💕')">I Agree 💖</button>
</div>

<!-- CLICK LOVE -->
<div class="section">
<button onclick="showLove()">Click if you love Meee 😌</button>
<p id="loveMsg" class="hidden">I knew it 😚💕</p>
</div>

<!-- VIDEO -->
<div class="section">
<h2>Open My Special Video 🎥</h2>
<button onclick="window.open('https://drive.google.com/file/d/105zxrH183oMkwAASaMejcpo-iVSYiSPJ/view?usp=sharing')">
Click To Watch 💖
</button
<div style="text-align:center; margin-top:60px;">
  <h2 style="color:#ff4d88; font-size:28px;">
    Will you be my forever Valentine? 💍💖
  </h2>

  <img src="https://media.giphy.com/media/MDJ9IbxxvDUQM/giphy.gif" 
       alt="Cute love gif"
       style="width:250px; border-radius:15px; margin:20px 0;">

  <br>

  <button onclick="document.getElementById('reply').innerHTML='Yayyyy 🥹💖 You just made me the happiest person alive! iloveeeuuusooomuchhh 🫂🥺❤️😭';"
          style="padding:10px 20px; font-size:18px; border:none; border-radius:20px; background:#ff4d88; color:white;">
    Yes 💕
  </button>
  <p id="reply" style="font-size:22px; color:#ff1493; margin-top:20px;"></p>
</div>
  <audio autoplay loop>
  <source src="https://drive.google.com/uc?export=download&id=1G5HYePdZ3lqadvTuVVyQnwrMBRnrfXun" type="audio/mpeg">
</audio>