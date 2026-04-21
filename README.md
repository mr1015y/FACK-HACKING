# FACK-HACKING
<!DOCTYPE html>
<html>
<head>
  <title>Hacker Ultra Pro</title>

  <style>
    body {
      margin: 0;
      background: black;
      color: #00ff00;
      font-family: monospace;
      overflow: hidden;
    }

    canvas {
      position: fixed;
      top: 0;
      left: 0;
      z-index: -1;
    }

    #screen {
      padding: 20px;
      white-space: pre-line;
    }

    input {
      background: black;
      border: none;
      color: #00ff00;
      font-family: monospace;
      padding: 10px;
      outline: none;
    }

    #progress {
      padding: 20px;
    }

    .glitch {
      animation: glitch 0.2s infinite;
    }

    @keyframes glitch {
      0% {transform: translate(1px, -1px);}
      25% {transform: translate(-1px, 1px);}
      50% {transform: translate(1px, 1px);}
      75% {transform: translate(-1px, -1px);}
      100% {transform: translate(0, 0);}
    }

    .alert {
      color: red;
      font-size: 20px;
    }
  </style>

</head>

<body>

<canvas id="matrix"></canvas>

<div id="screen"></div>
<input id="input" placeholder="Enter target name..." />
<div id="progress"></div>

<script>
/* MATRIX RAIN */
const canvas = document.getElementById("matrix");
const ctx = canvas.getContext("2d");

canvas.height = window.innerHeight;
canvas.width = window.innerWidth;

const letters = "01ABCDEFGHIJKLMNOPQRSTUVWXYZ";
const fontSize = 14;
const columns = canvas.width / fontSize;
const drops = Array(Math.floor(columns)).fill(1);

function drawMatrix() {
  ctx.fillStyle = "rgba(0, 0, 0, 0.05)";
  ctx.fillRect(0, 0, canvas.width, canvas.height);

  ctx.fillStyle = "#0f0";
  ctx.font = fontSize + "px monospace";

  for (let i = 0; i < drops.length; i++) {
    const text = letters.charAt(Math.floor(Math.random() * letters.length));
    ctx.fillText(text, i * fontSize, drops[i] * fontSize);

    if (drops[i] * fontSize > canvas.height && Math.random() > 0.975)
      drops[i] = 0;

    drops[i]++;
  }
}

setInterval(drawMatrix, 33);

/* MAIN SYSTEM */
const screen = document.getElementById("screen");
const input = document.getElementById("input");

input.addEventListener("keydown", function(e) {
  if (e.key === "Enter") {
    startHack(input.value);
    input.style.display = "none";
  }
});

function typeLine(text, speed = 40) {
  return new Promise(resolve => {
    let i = 0;
    function typing() {
      if (i < text.length) {
        screen.innerHTML += text.charAt(i);
        i++;
        setTimeout(typing, speed);
      } else {
        screen.innerHTML += "\n";
        resolve();
      }
    }
    typing();
  });
}

async function startHack(name) {

  document.body.classList.add("glitch");

  await typeLine("Initializing system...");
  await typeLine("Connecting to secure server...");
  await typeLine("Target: " + name);
  await typeLine("Tracking IP...");
  await typeLine("Location: Khulna, Bangladesh");
  await typeLine("Bypassing firewall...");
  await typeLine("Accessing database...");
  await typeLine("Downloading files...");
  await typeLine("passwords.txt downloaded");
  await typeLine("system_data.zip downloaded");

  loadBar();
}

/* PROGRESS BAR */
let progress = 0;

function loadBar() {
  const bar = document.getElementById("progress");

  let interval = setInterval(() => {
    if (progress <= 100) {
      let p = "█".repeat(progress/10) + "░".repeat(10 - progress/10);
      bar.innerHTML = "[" + p + "] " + progress + "%";
      progress += 10;
    } else {
      clearInterval(interval);
      finishHack();
    }
  }, 300);
}

/* FINAL ALERT */
function finishHack() {
  screen.innerHTML += "\nACCESS GRANTED 🔥\n";
  setTimeout(() => {
    screen.innerHTML += "\nWARNING: TRACE DETECTED!";
    screen.classList.add("alert");
  }, 1500);

  document.body.classList.remove("glitch");
}

</script>

</body>
</html>
