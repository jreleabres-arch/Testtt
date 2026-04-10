// Create HUD
const hud = document.createElement("div");
hud.id = "sol-hud";

// Style (mobile friendly)
hud.style.position = "fixed";
hud.style.top = "10px";
hud.style.right = "10px";
hud.style.background = "rgba(0,0,0,0.6)";
hud.style.color = "white";
hud.style.padding = "10px";
hud.style.borderRadius = "12px";
hud.style.fontSize = "12px";
hud.style.zIndex = "9999";

// Default stats
let mood = "Neutral";
let affection = 50;

// HUD content
hud.innerHTML = `
  <div>📍 Home</div>
  <div id="hud-mood">💬 Mood: ${mood}</div>
  <div id="hud-love">❤️ ${affection}</div>
  <div id="hud-time"></div>
`;

document.body.appendChild(hud);

// Clock (always safe)
setInterval(() => {
  const now = new Date();
  document.getElementById("hud-time").textContent =
    "🕒 " + now.toLocaleTimeString();
}, 1000);
