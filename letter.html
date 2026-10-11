
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Letter for Someone Special 💌</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    min-height: 100vh;
    font-family: Georgia, serif;
    background: linear-gradient(135deg, #ffe5ec, #f2e7ff, #fff5e8);
    color: #583b61;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 25px 15px;
    overflow-x: hidden;
}

.container {
    width: 100%;
    max-width: 650px;
    text-align: center;
}

h1 {
    font-size: clamp(27px, 6vw, 40px);
    margin-bottom: 10px;
}

.subtitle {
    line-height: 1.7;
    color: #82668a;
}

.screen {
    background: rgba(255,255,255,0.82);
    padding: 30px 20px;
    border-radius: 25px;
    box-shadow: 0 12px 40px #8c649022;
    border: 1px solid white;
    margin-top: 25px;
}

.hidden {
    display: none !important;
}

.envelope {
    font-size: 95px;
    cursor: pointer;
    display: inline-block;
    transition: transform 0.3s;
    animation: float 2s ease-in-out infinite;
}

.envelope:hover {
    transform: scale(1.1);
}

@keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
}

button {
    border: none;
    background: linear-gradient(135deg, #bd77c9, #8060cb);
    color: white;
    padding: 13px 22px;
    margin: 8px 5px;
    border-radius: 30px;
    font-size: 15px;
    cursor: pointer;
    font-family: inherit;
    transition: transform 0.2s, opacity 0.2s;
}

button:hover {
    transform: translateY(-2px);
    opacity: 0.9;
}

button:focus-visible {
    outline: 3px solid #583b61;
    outline-offset: 3px;
}

.letter {
    background: #fffaf4;
    border-radius: 18px;
    padding: 25px 22px;
    text-align: left;
    line-height: 1.9;
    white-space: pre-wrap;
    overflow-wrap: anywhere;
    min-height: 180px;
    border: 1px solid #f3dce9;
}

.letter-title {
    text-align: center;
    color: #a25ba9;
}

.signature {
    text-align: right;
    font-style: italic;
    margin-top: 20px;
}

.heart {
    position: fixed;
    bottom: -30px;
    pointer-events: none;
    animation: rise 5s linear forwards;
    z-index: 5;
}

@keyframes rise {
    to {
        transform: translateY(-110vh) rotate(25deg);
        opacity: 0;
    }
}

#finalMessage {
    background: #fff0f6;
    padding: 20px;
    margin-top: 18px;
    border-radius: 16px;
    line-height: 1.8;
}

footer {
    margin-top: 22px;
    font-size: 13px;
    color: #8d7393;
}
</style>
</head>

<body>

<main class="container">
    <h1>For Someone Truly Special 💗</h1>
    <p class="subtitle">
        Some feelings are difficult to say aloud.<br>
        So, I decided to write them instead.
    </p>

    <!-- First screen -->
    <section id="welcome" class="screen">
        <div class="envelope" aria-hidden="true">💌</div>
        <h2>A Little Letter for You</h2>
        <p>
            There is something I have wanted to tell you.
            Take a moment, and open this little surprise.
        </p>
        <button id="openButton">Open Your Letter 💌</button>
    </section>

    <!-- Letter screen -->
    <section id="letterScreen" class="screen hidden">
        <h2 class="letter-title">Dear Senior, 🌷</h2>

        <div id="letterText" class="letter" aria-live="polite"></div>

        <div class="signature">
            With lots of respect and gratitude,<br>
            Someone who appreciates you 💗
        </div>

        <button id="revealButton" class="hidden">
            One More Little Thing ✨
        </button>

        <div id="finalMessage" class="hidden" aria-live="polite">
            <h3>🌸 One Last Thing 🌸</h3>
            <p>
                You may not always realize the difference you make,
                but your kindness can stay in someone's heart
                long after an ordinary day has passed.
            </p>
            <p>
                Thank you for being someone worth appreciating.
                I hope life gives you countless reasons to smile,
                peaceful days, and all the happiness you deserve.
            </p>
            <p><strong>Never forget how much good you bring into the world. 💗</strong></p>
        </div>

        <button id="closeButton">Close Letter</button>
    </section>

    <footer>Made with care, a little courage, and lots of heart ♡</footer>
</main>

<script>
const welcome = document.getElementById("welcome");
const letterScreen = document.getElementById("letterScreen");
const letterText = document.getElementById("letterText");
const openButton = document.getElementById("openButton");
const revealButton = document.getElementById("revealButton");
const closeButton = document.getElementById("closeButton");
const finalMessage = document.getElementById("finalMessage");

const message = `I may not say this enough, but I truly appreciate you.

Sometimes, a person becomes important not because they do something extraordinary, but because of how they make ordinary moments feel.

Your guidance, your kindness, and the comfort of knowing that there is someone I can learn from mean more than words can explain.

Thank you for the little conversations, the laughter, the advice, and the moments that might seem small to you but mean something to me.

You have reminded me that a good person can make a difference without even realizing it.

I hope you know that you are appreciated not just for what you do, but for the person you are.

No matter how busy life becomes or how much things change, I will always be grateful that I got to know someone like you.

I wish you success in every dream you chase, peace on difficult days, and happiness in all the little things.

You deserve the same kindness that you give to others.

Thank you for being you. 🌷`;

let typingTimer = null;
let heartTimer = null;
let hasOpened = false;

function stopTyping() {
    if (typingTimer !== null) {
        clearInterval(typingTimer);
        typingTimer = null;
    }
}

function startTyping() {
    stopTyping();
    letterText.textContent = "";
    revealButton.classList.add("hidden");

    let index = 0;

    typingTimer = setInterval(() => {
        letterText.textContent += message.charAt(index);
        index++;

        if (index >= message.length) {
            stopTyping();
            revealButton.classList.remove("hidden");
        }
    }, 22);
}

function makeHeart() {
    const heart = document.createElement("div");
    heart.className = "heart";
    heart.textContent = ["💗", "💕", "♡", "✨"][Math.floor(Math.random() * 4)];
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (16 + Math.random() * 18) + "px";
    heart.style.animationDuration = (3 + Math.random() * 3) + "s";

    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 6500);
}

function startHearts() {
    if (heartTimer !== null) return;
    heartTimer = setInterval(makeHeart, 650);
}

function stopHearts() {
    if (heartTimer !== null) {
        clearInterval(heartTimer);
        heartTimer = null;
    }

    document.querySelectorAll(".heart").forEach(heart => heart.remove());
}

openButton.addEventListener("click", () => {
    welcome.classList.add("hidden");
    letterScreen.classList.remove("hidden");
    finalMessage.classList.add("hidden");
    hasOpened = true;

    startTyping();
    startHearts();

    window.scrollTo({ top: 0, behavior: "smooth" });
});

revealButton.addEventListener("click", () => {
    finalMessage.classList.remove("hidden");
    revealButton.classList.add("hidden");
    makeHeart();

    finalMessage.scrollIntoView({
        behavior: "smooth",
        block: "nearest"
    });
});

closeButton.addEventListener("click", () => {
    stopTyping();
    stopHearts();

    letterScreen.classList.add("hidden");
    welcome.classList.remove("hidden");

    finalMessage.classList.add("hidden");
    revealButton.classList.add("hidden");
    letterText.textContent = "";

    window.scrollTo({ top: 0, behavior: "smooth" });
});

// Also allow opening the envelope by clicking it.
document.querySelector(".envelope").addEventListener("click", () => {
    openButton.click();
});
</script>

</body>
</html>
