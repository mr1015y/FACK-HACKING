<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>SHADOWNET — HACKER RED MODE v3</title>
<style>
*{box-sizing:border-box;margin:0;padding:0;}
body{background:#000;display:flex;justify-content:center;padding:20px;min-height:100vh;}
.wrap{font-family:monospace;width:100%;max-width:620px;}
.terminal{border:1.5px solid #c0392b;border-radius:3px;background:#050000;overflow:hidden;}
.topbar{background:#0f0000;border-bottom:1px solid #330000;padding:6px 12px;display:flex;align-items:center;gap:8px;}
.dot{width:10px;height:10px;border-radius:50%;}
.d1{background:#ff3333;}.d2{background:#ff8800;}.d3{background:#ffcc00;}
.topbar-title{flex:1;text-align:center;font-size:11px;color:#660000;letter-spacing:3px;}
.login-screen{padding:2rem 1.5rem;display:flex;flex-direction:column;align-items:center;gap:16px;}
.login-skull{font-size:36px;animation:pulse 2s ease-in-out infinite;}
@keyframes pulse{0%,100%{opacity:1;}50%{opacity:.4;}}
.login-title{font-size:15px;color:#ff3333;letter-spacing:6px;text-align:center;}
.login-sub{font-size:10px;color:#550000;letter-spacing:2px;text-align:center;}
.login-field{width:100%;max-width:340px;display:flex;flex-direction:column;gap:6px;}
.login-label{font-size:9px;color:#660000;letter-spacing:3px;}
.login-input{background:#020000;border:1px solid #440000;color:#ff4444;font-family:monospace;font-size:15px;padding:10px 14px;border-radius:2px;letter-spacing:3px;outline:none;width:100%;text-align:center;}
.login-input:focus{border-color:#cc2222;}
.login-alias{font-size:11px;color:#880000;letter-spacing:2px;text-align:center;min-height:16px;}
.login-btn{background:transparent;border:1.5px solid #cc2222;color:#cc2222;font-family:monospace;font-size:12px;letter-spacing:4px;padding:10px 32px;border-radius:2px;cursor:pointer;margin-top:4px;}
.login-btn:hover{background:#150000;}
.login-btn:disabled{opacity:.3;cursor:not-allowed;}
.login-score-box{width:100%;max-width:340px;background:#0a0000;border:0.5px solid #220000;border-radius:2px;padding:10px 14px;display:none;flex-direction:column;gap:4px;}
.login-score-box.show{display:flex;}
.lsb-title{font-size:9px;color:#440000;letter-spacing:2px;}
.lsb-row{display:flex;justify-content:space-between;font-size:11px;color:#993333;}
.game-screen{display:none;}
.player-bar{background:#0a0000;border-bottom:1px solid #1a0000;padding:6px 12px;display:flex;align-items:center;justify-content:space-between;}
.player-info{display:flex;align-items:center;gap:8px;}
.player-avatar{width:28px;height:28px;border-radius:2px;background:#1a0000;border:0.5px solid #550000;display:flex;align-items:center;justify-content:center;font-size:11px;color:#cc2222;font-weight:bold;}
.player-name{font-size:12px;color:#cc2222;letter-spacing:2px;}
.player-alias{font-size:9px;color:#550000;letter-spacing:1px;}
.player-best{font-size:10px;color:#550000;letter-spacing:1px;}
.player-best span{color:#ff8800;}
.stats-row{display:grid;grid-template-columns:repeat(5,1fr);gap:1px;background:#1a0000;border-bottom:1px solid #1a0000;}
.stat{background:#080000;padding:7px 4px;text-align:center;}
.stat-l{font-size:9px;color:#660000;letter-spacing:2px;margin-bottom:2px;}
.stat-v{font-size:16px;color:#ff3333;font-weight:bold;}
.stat-v.hi{color:#ff8800;}.stat-v.ok{color:#22ff44;}.stat-v.warn{color:#ffcc00;}
.target-area{padding:8px 12px;border-bottom:1px solid #110000;display:flex;align-items:center;gap:10px;flex-wrap:wrap;}
.target-label{font-size:9px;color:#550000;letter-spacing:2px;white-space:nowrap;}
.target-ip{font-size:12px;color:#cc2222;letter-spacing:2px;}
.breach-bar-wrap{flex:1;min-width:80px;background:#0d0000;border:0.5px solid #330000;border-radius:2px;height:7px;overflow:hidden;}
.breach-bar{height:100%;background:#cc2222;transition:width .4s ease;width:0%;}
.breach-pct{font-size:10px;color:#cc2222;min-width:32px;text-align:right;}
.trace-wrap{display:flex;align-items:center;gap:8px;padding:6px 12px;}
.trace-label{font-size:9px;color:#880000;letter-spacing:2px;}
.trace-bar-bg{flex:1;background:#0d0000;border:0.5px solid #330000;border-radius:2px;height:5px;overflow:hidden;}
.trace-fill{height:100%;background:#ff2200;transition:width .3s ease;width:0%;}
.trace-val{font-size:10px;color:#880000;min-width:72px;text-align:right;}
.wpm-bar{display:flex;align-items:center;gap:8px;padding:0 12px 6px;border-bottom:1px solid #110000;}
.wpm-label{font-size:9px;color:#440000;letter-spacing:2px;}
.wpm-val{font-size:12px;color:#ff6600;font-weight:bold;min-width:48px;}
.acc-label{font-size:9px;color:#440000;letter-spacing:2px;margin-left:12px;}
.acc-val{font-size:12px;color:#22cc44;font-weight:bold;min-width:40px;}
.streak-label{font-size:9px;color:#440000;letter-spacing:2px;margin-left:auto;}
.streak-dots{display:flex;gap:3px;}
.sdot{width:7px;height:7px;border-radius:50%;background:#1a0000;border:0.5px solid #330000;}
.sdot.active{background:#ff3333;box-shadow:0 0 4px #ff3333;}
.cmd-screen{background:#020000;margin:0 12px 8px;border:0.5px solid #220000;border-radius:2px;padding:10px;text-align:center;min-height:68px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:4px;position:relative;}
.cmd-prompt{font-size:10px;color:#550000;letter-spacing:3px;}
.cmd-text{font-size:24px;color:#ff4444;font-weight:bold;letter-spacing:7px;min-height:30px;}
.cmd-sub{font-size:10px;color:#880000;letter-spacing:1px;min-height:14px;}
.mode-badge{position:absolute;top:5px;right:7px;font-size:9px;padding:2px 6px;border-radius:2px;letter-spacing:2px;}
.mode-normal{background:#110000;color:#550000;border:0.5px solid #330000;}
.mode-alert{background:#220000;color:#ff4400;border:0.5px solid #882200;animation:blink .5s step-end infinite;}
.mode-surge{background:#221100;color:#ffaa00;border:0.5px solid #884400;animation:blink .4s step-end infinite;}
@keyframes blink{50%{opacity:.3;}}
.mission-tag{position:absolute;top:5px;left:7px;font-size:9px;color:#330066;letter-spacing:1px;}
.log-area{padding:6px 12px;min-height:58px;border-bottom:1px solid #110000;font-size:11px;line-height:1.65;display:flex;flex-direction:column;gap:1px;overflow:hidden;}
.log-line{display:flex;gap:6px;}
.log-ts{color:#330000;min-width:48px;}
.log-ok{color:#1a9933;}.log-err{color:#cc2222;}.log-warn{color:#cc7700;}.log-info{color:#0066aa;}.log-sys{color:#660066;}
.ctrl-row{display:flex;gap:6px;padding:0 12px 8px;}
.ctrl-row select{flex:1;background:#050000;border:1px solid #440000;color:#cc2222;font-family:monospace;font-size:11px;padding:5px 8px;border-radius:2px;letter-spacing:1px;outline:none;cursor:pointer;}
.ctrl-row select option{background:#050000;}
.hbtn{background:transparent;border:1px solid #cc2222;color:#cc2222;font-family:monospace;font-size:11px;letter-spacing:2px;padding:6px 12px;border-radius:2px;cursor:pointer;white-space:nowrap;}
.hbtn:hover{background:#150000;}
.hbtn:active{transform:scale(.97);}
.input-row{display:flex;gap:8px;padding:0 12px 10px;}
.hack-input{flex:1;background:#020000;border:1px solid #440000;color:#ff4444;font-family:monospace;font-size:14px;padding:8px 12px;border-radius:2px;letter-spacing:3px;outline:none;}
.hack-input:focus{border-color:#cc0000;}
.hack-input:disabled{opacity:.2;cursor:not-allowed;}
.gameover-screen{display:none;padding:1.5rem;flex-direction:column;align-items:center;gap:12px;}
.go-title{font-size:18px;color:#ff3333;letter-spacing:6px;}
.go-name{font-size:14px;color:#ff8800;letter-spacing:4px;}
.go-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;width:100%;}
.go-stat{background:#0a0000;border:0.5px solid #220000;border-radius:2px;padding:10px 6px;text-align:center;}
.go-stat-l{font-size:9px;color:#550000;letter-spacing:2px;margin-bottom:4px;}
.go-stat-v{font-size:20px;color:#ff3333;font-weight:bold;}
.go-stat-v.hi{color:#ff8800;}.go-stat-v.ok{color:#22ff44;}.go-stat-v.warn{color:#ffcc00;}
.go-rank{font-size:12px;letter-spacing:3px;padding:8px 20px;border-radius:2px;}
.go-achiev{width:100%;background:#0a0000;border:0.5px solid #220000;border-radius:2px;padding:10px 14px;}
.go-ach-title{font-size:9px;color:#440000;letter-spacing:2px;margin-bottom:6px;}
.go-ach-list{display:flex;flex-wrap:wrap;gap:6px;}
.ach-badge{font-size:10px;padding:3px 8px;border-radius:2px;letter-spacing:1px;}
.ach-gold{background:#221100;color:#ffaa00;border:0.5px solid #884400;}
.ach-silver{background:#111122;color:#8888ff;border:0.5px solid #333388;}
.ach-bronze{background:#110800;color:#cc6622;border:0.5px solid #662200;}
.go-btns{display:flex;gap:8px;}
.scanlines{position:absolute;inset:0;pointer-events:none;background:repeating-linear-gradient(0deg,transparent,transparent 2px,rgba(200,0,0,.012) 2px,rgba(200,0,0,.012) 4px);border-radius:2px;}
</style>
</head>
<body>
<div class="wrap">
<div class="terminal">
  <div class="topbar">
    <div class="dot d1"></div><div class="dot d2"></div><div class="dot d3"></div>
    <div class="topbar-title" id="topbar-title">SHADOWNET // IDENTITY REQUIRED</div>
  </div>

  <!-- LOGIN -->
  <div class="login-screen" id="login-screen">
    <div class="login-skull">&#128128;</div>
    <div class="login-title">SHADOWNET ACCESS</div>
    <div class="login-sub">OPERATIVE REGISTRATION REQUIRED</div>
    <div class="login-field">
      <div class="login-label">OPERATIVE NAME:</div>
      <input class="login-input" id="name-input" placeholder="ENTER YOUR NAME" maxlength="16" autocomplete="off" spellcheck="false"/>
      <div class="login-alias" id="alias-display"></div>
    </div>
    <div class="login-score-box" id="prev-score-box">
      <div class="lsb-title">PREVIOUS SESSION DETECTED:</div>
      <div class="lsb-row"><span>Best Score</span><span id="prev-best">—</span></div>
      <div class="lsb-row"><span>Best Level</span><span id="prev-lvl">—</span></div>
      <div class="lsb-row"><span>Sessions Played</span><span id="prev-sessions">—</span></div>
    </div>
    <button class="login-btn" id="login-btn" onclick="doLogin()" disabled>AUTHENTICATE</button>
  </div>

  <!-- GAME -->
  <div class="game-screen" id="game-screen">
    <div class="player-bar">
      <div class="player-info">
        <div class="player-avatar" id="p-avatar">??</div>
        <div>
          <div class="player-name" id="p-name">—</div>
          <div class="player-alias" id="p-alias">—</div>
        </div>
      </div>
      <div class="player-best">BEST: <span id="p-best">0</span></div>
    </div>
    <div class="stats-row">
      <div class="stat"><div class="stat-l">SCORE</div><div class="stat-v" id="s-score">0</div></div>
      <div class="stat"><div class="stat-l">COMBO</div><div class="stat-v hi" id="s-combo">0</div></div>
      <div class="stat"><div class="stat-l">LEVEL</div><div class="stat-v warn" id="s-lvl">1</div></div>
      <div class="stat"><div class="stat-l">ERRORS</div><div class="stat-v" id="s-err">0</div></div>
      <div class="stat"><div class="stat-l">TIME</div><div class="stat-v ok" id="s-time">5:00</div></div>
    </div>
    <div class="target-area">
      <div class="target-label">TARGET:</div>
      <div class="target-ip" id="t-ip">---.---.---.---</div>
      <div class="target-label" style="margin-left:6px;">BREACH:</div>
      <div class="breach-bar-wrap"><div class="breach-bar" id="breach-bar"></div></div>
      <div class="breach-pct" id="breach-pct">0%</div>
    </div>
    <div class="trace-wrap">
      <div class="trace-label">TRACE:</div>
      <div class="trace-bar-bg"><div class="trace-fill" id="trace-fill"></div></div>
      <div class="trace-val" id="trace-val">UNDETECTED</div>
    </div>
    <div class="wpm-bar">
      <div class="wpm-label">WPM:</div>
      <div class="wpm-val" id="wpm-val">0</div>
      <div class="acc-label">ACCURACY:</div>
      <div class="acc-val" id="acc-val">—</div>
      <div class="streak-label">STREAK:</div>
      <div class="streak-dots" id="streak-dots"></div>
    </div>
    <div class="cmd-screen">
      <div class="scanlines"></div>
      <div class="mission-tag" id="mission-tag"></div>
      <div class="cmd-prompt" id="c-prompt">SELECT DIFFICULTY — PRESS EXECUTE</div>
      <div class="cmd-text" id="c-cmd"></div>
      <div class="cmd-sub" id="c-sub"></div>
      <div class="mode-badge mode-normal" id="c-mode">STANDBY</div>
    </div>
    <div class="log-area" id="log-area">
      <div class="log-line"><span class="log-ts">[BOOT]</span><span class="log-sys">Exploit framework v9.1 initialised</span></div>
    </div>
    <div class="ctrl-row">
      <select id="diff-sel">
        <option value="script">SCRIPT KIDDIE</option>
        <option value="hacker" selected>HACKER</option>
        <option value="elite">ELITE OPERATOR</option>
        <option value="ghost">GHOST PROTOCOL</option>
      </select>
      <button class="hbtn" id="startbtn" onclick="startGame()">EXECUTE</button>
      <button class="hbtn" onclick="showLogin()" style="border-color:#440000;color:#440000;">LOGOUT</button>
    </div>
    <div class="input-row">
      <input class="hack-input" id="hack-in" placeholder="ENTER EXPLOIT COMMAND..." disabled autocomplete="off" spellcheck="false"/>
    </div>
  </div>

  <!-- GAMEOVER -->
  <div class="gameover-screen" id="go-screen">
    <div class="go-title">OPERATION COMPLETE</div>
    <div class="go-name" id="go-name"></div>
    <div class="go-grid">
      <div class="go-stat"><div class="go-stat-l">SCORE</div><div class="go-stat-v" id="go-score">0</div></div>
      <div class="go-stat"><div class="go-stat-l">LEVEL</div><div class="go-stat-v warn" id="go-lvl">1</div></div>
      <div class="go-stat"><div class="go-stat-l">ACCURACY</div><div class="go-stat-v ok" id="go-acc">0%</div></div>
      <div class="go-stat"><div class="go-stat-l">BEST WPM</div><div class="go-stat-v hi" id="go-wpm">0</div></div>
      <div class="go-stat"><div class="go-stat-l">BREACHES</div><div class="go-stat-v" id="go-breach">0</div></div>
      <div class="go-stat"><div class="go-stat-l">BEST COMBO</div><div class="go-stat-v hi" id="go-combo">0</div></div>
    </div>
    <div class="go-rank" id="go-rank"></div>
    <div class="go-achiev">
      <div class="go-ach-title">ACHIEVEMENTS UNLOCKED:</div>
      <div class="go-ach-list" id="go-ach-list"></div>
    </div>
    <div class="go-btns">
      <button class="hbtn" onclick="retryGame()">RETRY MISSION</button>
      <button class="hbtn" onclick="showLogin()" style="border-color:#440000;color:#550000;">SWITCH OPERATIVE</button>
    </div>
  </div>

</div>
</div>
<script>
const POOLS={
  script:["hack","ping","scan","grep","sudo","kill","ssh","wget","curl","bash","root","dump","nmap","chmod"],
  hacker:["decrypt","inject","bypass","spoof","proxy","shell","forge","sniff","crack","pivot","trojan","exfil","phish","brute"],
  elite:["exploit","escalate","obfuscate","rootkit","backdoor","payload","keylogger","polymorphic","zerotrust","persistence","privilege","darknet"],
  ghost:["ghostprotocol","kernelexploit","cryptovault","supplychain","covertchannel","phantomexec","shadownode","memoryforensic","zerodaychain","darkwebproxy"]
};
const SYSTEMS=["192.168.0.1","10.0.0.254","172.16.31.100","203.0.113.45","198.51.100.7","51.104.15.253","91.198.174.192","104.21.67.32","10.10.99.7","172.31.255.254"];
const EVENTS=["FIREWALL SURGE","INTRUSION ALERT","PACKET FLOOD","HONEYPOT ACTIVE","IDS TRIGGERED","DARKWEB BOUNTY"];
const MISSIONS=["GHOST-7","PHANTOM-X","ZERO-DAY","SHADOW-9","ECLIPSE","REDLINE","BLACKOUT","CIPHER"];
const ALIASES=["PHANTOM","VECTOR","CIPHER","SPECTER","BINARY","GLITCH","DAEMON","NEXUS","VORTEX","WRAITH","SIGNAL","AXIOM","REAPER","HELIX"];
let playerName="",playerAlias="";
let score=0,combo=0,errors=0,lvl=1,running=false,time=300;
let trace=0,breach=0,current="",timer=null,eventTimer=null,surging=false;
let totalCmds=0,correctCmds=0,bestWpm=0,breachCount=0,bestCombo=0;
const logEl=document.getElementById("log-area");
const inp=document.getElementById("hack-in");
function fmt(t){let m=Math.floor(t/60),s=t%60;return m+":"+(s<10?"0":"")+s;}
function rnd(a){return a[Math.floor(Math.random()*a.length)];}
function getPool(){return POOLS[document.getElementById("diff-sel").value];}
function genAlias(name){return ALIASES[name.split("").reduce((a,c)=>a+c.charCodeAt(0),0)%ALIASES.length];}
function saveSession(){
  const key="hkr_"+playerName.toLowerCase().replace(/\s/g,"");
  const prev=loadSession();
  const data={bestScore:Math.max(score,prev.bestScore||0),bestLvl:Math.max(lvl,prev.bestLvl||0),sessions:(prev.sessions||0)+1,alias:playerAlias};
  try{localStorage.setItem(key,JSON.stringify(data));}catch(e){}
  return data;
}
function loadSession(){
  const key="hkr_"+playerName.toLowerCase().replace(/\s/g,"");
  try{const d=localStorage.getItem(key);return d?JSON.parse(d):{};}catch(e){return{};}
}
document.getElementById("name-input").addEventListener("input",function(){
  const v=this.value.trim();
  const btn=document.getElementById("login-btn");
  if(v.length>=2){
    document.getElementById("alias-display").textContent="ALIAS ASSIGNED: //"+genAlias(v)+"//";
    btn.disabled=false;
    const tmp=playerName;playerName=v;
    const prev=loadSession();playerName=tmp;
    if(prev.bestScore){
      document.getElementById("prev-score-box").classList.add("show");
      document.getElementById("prev-best").textContent=prev.bestScore;
      document.getElementById("prev-lvl").textContent=prev.bestLvl||1;
      document.getElementById("prev-sessions").textContent=prev.sessions||1;
    } else document.getElementById("prev-score-box").classList.remove("show");
  } else {
    document.getElementById("alias-display").textContent="";
    btn.disabled=true;
    document.getElementById("prev-score-box").classList.remove("show");
  }
});
document.getElementById("name-input").addEventListener("keydown",function(e){
  if(e.key==="Enter"&&!document.getElementById("login-btn").disabled)doLogin();
});
function doLogin(){
  const v=document.getElementById("name-input").value.trim();
  if(v.length<2)return;
  playerName=v.toUpperCase();
  playerAlias=genAlias(v);
  document.getElementById("p-name").textContent=playerName;
  document.getElementById("p-alias").textContent="//"+playerAlias+"//";
  document.getElementById("p-avatar").textContent=playerName.slice(0,2);
  document.getElementById("topbar-title").textContent="ROOT@SHADOWNET // "+playerAlias+" // ACTIVE";
  document.getElementById("p-best").textContent=loadSession().bestScore||0;
  showGame();
  addLog("OPERATIVE ["+playerAlias+"] AUTHENTICATED","log-sys");
  addLog("Welcome, "+playerName+". Mission ready.","log-info");
}
function showLogin(){
  document.getElementById("login-screen").style.cssText="display:flex;flex-direction:column;";
  document.getElementById("game-screen").style.display="none";
  document.getElementById("go-screen").style.display="none";
  if(timer)clearInterval(timer);if(eventTimer)clearInterval(eventTimer);
  running=false;inp.disabled=true;
}
function showGame(){
  document.getElementById("login-screen").style.display="none";
  document.getElementById("game-screen").style.display="block";
  document.getElementById("go-screen").style.display="none";
}
function showGameover(){
  document.getElementById("game-screen").style.display="none";
  document.getElementById("go-screen").style.cssText="display:flex;flex-direction:column;";
}
function setIP(){document.getElementById("t-ip").textContent=rnd(SYSTEMS);}
function addLog(msg,cls){
  const l=document.createElement("div");l.className="log-line";
  l.innerHTML='<span class="log-ts">['+fmt(300-time)+']</span><span class="'+cls+'">'+msg+'</span>';
  logEl.appendChild(l);
  while(logEl.children.length>5)logEl.removeChild(logEl.firstChild);
}
function updateBreach(){
  const pct=Math.min(100,Math.round(breach));
  document.getElementById("breach-bar").style.width=pct+"%";
  document.getElementById("breach-pct").textContent=pct+"%";
  if(pct>=100){breachCount++;breach=0;addLog(playerAlias+" BREACHED SYSTEM "+breachCount+" — TARGET ROTATED","log-sys");setIP();}
}
function updateTrace(){
  const pct=Math.min(100,Math.round(trace));
  document.getElementById("trace-fill").style.width=pct+"%";
  let label="UNDETECTED";
  if(pct>80)label="CRITICAL";else if(pct>60)label="DETECTED";else if(pct>35)label="SCANNING";else if(pct>15)label="SUSPICIOUS";
  document.getElementById("trace-fill").style.background=pct>60?"#ff0000":pct>35?"#ff6600":"#cc2200";
  document.getElementById("trace-val").textContent=label+" ("+pct+"%)";
  if(pct>=100){addLog(playerAlias+" TRACED — SCORE -20","log-err");trace=0;score=Math.max(0,score-20);document.getElementById("s-score").textContent=score;}
}
function updateStreakDots(){
  const el=document.getElementById("streak-dots");el.innerHTML="";
  for(let i=0;i<5;i++){const d=document.createElement("div");d.className="sdot"+(i<Math.min(combo,5)?" active":"");el.appendChild(d);}
}
function updateWpm(){
  const elapsed=Math.max(1,(300-time)/60);
  const wpm=Math.round(correctCmds/elapsed);
  bestWpm=Math.max(bestWpm,wpm);
  document.getElementById("wpm-val").textContent=wpm;
  document.getElementById("acc-val").textContent=(totalCmds>0?Math.round((correctCmds/totalCmds)*100):100)+"%";
}
function setMode(m){
  const el=document.getElementById("c-mode");el.textContent=m;
  const isAlert=["SURGE","ALERT","FLOOD","HONEY","IDS","BOUNTY"].some(k=>m.includes(k));
  el.className="mode-badge "+(m==="STANDBY"?"mode-normal":isAlert?"mode-alert":"mode-surge");
}
function nextCmd(){
  current=rnd(getPool());
  document.getElementById("c-cmd").textContent=current.toUpperCase();
  document.getElementById("c-prompt").textContent=playerName+" — EXECUTE:";
  if(!surging)setMode("ACTIVE");
}
function triggerEvent(){
  if(!running)return;
  const evt=rnd(EVENTS);surging=true;setMode(evt);
  addLog(evt+" — SURGE BONUS ACTIVE 10s","log-warn");
  setTimeout(()=>{surging=false;if(running)setMode("ACTIVE");},10000);
}
function levelUp(){
  lvl++;document.getElementById("s-lvl").textContent=lvl;
  addLog(playerAlias+" LEVEL "+lvl+" — DEFENSES HARDENING","log-sys");
  setMode("// LEVEL "+lvl+" //");
  setTimeout(()=>{if(running)setMode("ACTIVE");},1500);
}
function startGame(){
  if(timer)clearInterval(timer);if(eventTimer)clearInterval(eventTimer);
  score=0;combo=0;errors=0;lvl=1;time=300;trace=0;breach=0;surging=false;running=true;
  totalCmds=0;correctCmds=0;bestWpm=0;breachCount=0;bestCombo=0;
  document.getElementById("s-score").textContent=0;document.getElementById("s-combo").textContent=0;
  document.getElementById("s-lvl").textContent=1;document.getElementById("s-err").textContent=0;
  document.getElementById("s-time").textContent="5:00";
  document.getElementById("trace-fill").style.width="0%";document.getElementById("trace-val").textContent="UNDETECTED";
  document.getElementById("breach-bar").style.width="0%";document.getElementById("breach-pct").textContent="0%";
  document.getElementById("wpm-val").textContent="0";document.getElementById("acc-val").textContent="—";
  document.getElementById("c-sub").textContent="";
  document.getElementById("mission-tag").textContent=rnd(MISSIONS);
  inp.disabled=false;inp.value="";inp.focus();
  document.getElementById("startbtn").textContent="ABORT";
  updateStreakDots();setIP();
  addLog(playerAlias+" — MISSION "+document.getElementById("mission-tag").textContent+" STARTED","log-warn");
  nextCmd();
  timer=setInterval(()=>{
    time--;
    document.getElementById("s-time").textContent=fmt(time);
    document.getElementById("s-time").className="stat-v "+(time<60?"":"ok");
    if(time%60===0&&time>0){setIP();addLog("TARGET ROTATED — PIVOTING NETWORK","log-info");}
    if(time<=0){clearInterval(timer);clearInterval(eventTimer);endGame();}
    trace=Math.max(0,trace-0.3);updateTrace();updateWpm();
  },1000);
  eventTimer=setInterval(()=>{if(running)triggerEvent();},18000);
}
inp.addEventListener("keydown",function(e){
  if(e.key!=="Enter"||!running)return;
  const val=inp.value.trim().toLowerCase();inp.value="";totalCmds++;
  if(val===current){
    combo++;correctCmds++;bestCombo=Math.max(bestCombo,combo);
    let pts=1,extra="";
    if(surging){pts+=3;extra=" +SURGE x4";}
    if(combo>=10){pts+=5;extra+=" +CHAIN x10";}else if(combo>=5){pts+=2;extra+=" +CHAIN x5";}else if(combo>=3){pts+=1;extra+=" +CHAIN x3";}
    score+=pts;breach=Math.min(100,breach+8);trace=Math.max(0,trace-5);
    if(combo>0&&combo%10===0)levelUp();
    document.getElementById("s-score").textContent=score;
    document.getElementById("s-combo").textContent=combo;
    document.getElementById("c-sub").textContent=playerAlias+" — GRANTED +"+pts+extra;
    addLog("["+current.toUpperCase()+"] OK +"+pts+"pts"+extra,"log-ok");
    updateBreach();updateTrace();updateStreakDots();updateWpm();
  } else {
    combo=0;errors++;trace=Math.min(100,trace+12);
    document.getElementById("s-combo").textContent=0;document.getElementById("s-err").textContent=errors;
    document.getElementById("c-sub").textContent="DENIED — TRACE +12%";
    addLog("["+val.toUpperCase()+"] REJECTED — TRACE RISING","log-err");
    updateTrace();updateStreakDots();
    if(errors%5===0)addLog(errors+" FAILURES — COUNTERMEASURES ACTIVE","log-warn");
  }
  nextCmd();
});
function getRank(s){
  if(s>=300)return{label:"// S-RANK: GHOST //",style:"background:#221100;color:#ffcc00;border:0.5px solid #886600;"};
  if(s>=200)return{label:"// A-RANK: ELITE //",style:"background:#110022;color:#cc66ff;border:0.5px solid #660088;"};
  if(s>=120)return{label:"// B-RANK: OPERATOR //",style:"background:#001122;color:#4488ff;border:0.5px solid #224488;"};
  if(s>=60)return{label:"// C-RANK: HACKER //",style:"background:#001100;color:#44cc44;border:0.5px solid #226622;"};
  return{label:"// D-RANK: SCRIPT KIDDIE //",style:"background:#110000;color:#cc4422;border:0.5px solid #661100;"};
}
function getAchievements(){
  const ach=[];
  const acc=totalCmds>0?Math.round((correctCmds/totalCmds)*100):0;
  if(score>=300)ach.push({label:"GHOST OPERATOR",cls:"ach-gold"});
  if(bestCombo>=15)ach.push({label:"CHAIN MASTER",cls:"ach-gold"});
  if(breachCount>=5)ach.push({label:"SYSTEM CRUSHER",cls:"ach-gold"});
  if(acc>=95&&totalCmds>=20)ach.push({label:"PRECISION",cls:"ach-silver"});
  if(bestWpm>=60)ach.push({label:"SPEED DEMON",cls:"ach-silver"});
  if(lvl>=5)ach.push({label:"ASCENDED",cls:"ach-silver"});
  if(errors===0&&totalCmds>=10)ach.push({label:"NO ERRORS",cls:"ach-gold"});
  if(ach.length===0)ach.push({label:"FIRST RUN",cls:"ach-bronze"});
  return ach;
}
function endGame(){
  running=false;inp.disabled=true;
  const saved=saveSession();
  document.getElementById("p-best").textContent=saved.bestScore;
  const acc=totalCmds>0?Math.round((correctCmds/totalCmds)*100):0;
  const rank=getRank(score);
  document.getElementById("go-name").textContent="OPERATIVE: "+playerAlias+" ("+playerName+")";
  document.getElementById("go-score").textContent=score;
  document.getElementById("go-lvl").textContent=lvl;
  document.getElementById("go-acc").textContent=acc+"%";
  document.getElementById("go-wpm").textContent=bestWpm;
  document.getElementById("go-breach").textContent=breachCount;
  document.getElementById("go-combo").textContent=bestCombo;
  const rankEl=document.getElementById("go-rank");
  rankEl.textContent=rank.label;rankEl.style.cssText=rank.style;
  const achList=document.getElementById("go-ach-list");achList.innerHTML="";
  getAchievements().forEach(a=>{const b=document.createElement("span");b.className="ach-badge "+a.cls;b.textContent=a.label;achList.appendChild(b);});
  document.getElementById("startbtn").textContent="RETRY";
  showGameover();
}
function retryGame(){showGame();startGame();}
</script>
</body>
</html>
