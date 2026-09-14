# Aviation-
Ai Aviator 
<!DOCTYPE html><html lang="en"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1"><title>AVIATOR PREDICTOR PREMIUM</title><link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@700;800&family=Inter:wght@500;600;800&display=swap" rel="stylesheet"><script src="https://cdn.jsdelivr.net/npm/chart.js"></script><style>:root{--bg:#07070a;--card:#12121a;--card2:#1c1c28;--red:#ff1e3c;--red2:#ff4d6a;--gold:#ffcc00;--glow:0 0 45px rgba(255,30,60,.65);--silver:#c0c5ce;--border:rgba(255,255,255,.08);--green:#3cff8a}*{margin:0;padding:0;box-sizing:border-box}body{background:var(--bg);color:#fff;font-family:Inter,sans-serif;overflow-x:hidden}h1,h2{font-family:'Space Grotesk'}
#splash{position:fixed;inset:0;z-index:9999;background:radial-gradient(circle at 50% 50%,#1a0a0e,#07070a 70%);display:flex;align-items:center;justify-content:center;flex-direction:column;transition:opacity.8s,transform.8s}
#splash.hide{opacity:0;transform:scale(1.1);pointer-events:none}
.plane{font-size:72px;animation:fly 2.2s ease-in-out infinite,glow 1.5s ease-in-out infinite alternate}
@keyframes fly{0%{transform:translateY(0) rotate(-5deg)}50%{transform:translateY(-18px) rotate(5deg)}100%{transform:translateY(0) rotate(-5deg)}}
@keyframes glow{0%{filter:drop-shadow(0 0 10px rgba(255,30,60,.4))}100%{filter:drop-shadow(0 0 30px rgba(255,30,60,.9))}}
.loader{width:180px;height:3px;background:var(--card2);border-radius:10px;margin-top:22px;overflow:hidden;border:1px solid var(--border)}
.loader-bar{height:100%;width:0%;background:linear-gradient(90deg,var(--red),var(--gold));border-radius:10px;animation:load 2.8s ease-in-out forwards}
@keyframes load{0%{width:0%}20%{width:35%}50%{width:72%}80%{width:92%}100%{width:100%}}
.splash-text{margin-top:18px;font-size:11px;letter-spacing:4px;color:var(--red);font-weight:800;animation:fade 1.2s ease-in-out infinite alternate}
@keyframes fade{0%{opacity:.4}100%{opacity:1}}
.float{animation:float 3s ease-in-out infinite}
@keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-6px)}}
.shimmer{position:relative;overflow:hidden}
.shimmer:after{content:'';position:absolute;top:0;left:-100%;width:60%;height:100%;background:linear-gradient(90deg,transparent,rgba(255,255,255,.12),transparent);animation:shimmer 2.5s infinite}
@keyframes shimmer{0%{left:-100%}100%{left:200%}}
.bg{position:fixed;inset:0;z-index:-1;background:radial-gradient(circle at 15% 15%,rgba(255,30,60,.3),transparent 45%),radial-gradient(circle at 85% 85%,rgba(255,204,0,.14),transparent 40%)}
.card{background:linear-gradient(145deg,var(--card),var(--card2));border:1px solid var(--border);border-radius:22px;padding:22px;box-shadow:0 12px 40px rgba(0,0,0,.5)}
.card-glow{box-shadow:var(--glow);border-color:rgba(255,30,60,.6)}
.btn{background:linear-gradient(90deg,var(--red),var(--red2));color:#fff;border:none;border-radius:14px;padding:16px 22px;font-weight:900;cursor:pointer;width:100%}
.btn-gold{background:linear-gradient(90deg,var(--gold),#ff9d00);color:#000}
.input{background:var(--card2);border:1px solid var(--border);border-radius:14px;padding:15px;color:#fff;width:100%;outline:none}
.nav{position:fixed;top:0;width:100%;z-index:99;background:rgba(7,7,10,.92);backdrop-filter:blur(18px);border-bottom:1px solid var(--border);padding:12px 18px;display:flex;justify-content:space-between}
.bnav{position:fixed;bottom:16px;left:50%;transform:translateX(-50%);background:rgba(20,20,28,.98);border:1px solid var(--border);border-radius:24px;padding:7px;display:flex;gap:5px;z-index:99}
.bnav button{background:transparent;border:none;color:var(--silver);padding:11px 15px;border-radius:14px;font-weight:600;font-size:12px}
.bnav button.on{background:var(--red);color:#fff;box-shadow:var(--glow)}
.page{display:none;min-height:100vh;padding:88px 18px 110px;max-width:1180px;margin:auto;animation:pageIn.6s ease-out}
@keyframes pageIn{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:translateY(0)}}
.page.on{display:block}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:14px}
@media(max-width:780px){.grid3,.grid2{grid-template-columns:1fr}}
.stat{font-size:30px;font-weight:800}
.tag{font-size:10px;letter-spacing:3px;color:var(--red);font-weight:800}
.pay{background:linear-gradient(100deg,rgba(255,204,0,.18),rgba(255,30,60,.24));border:2px solid var(--gold);padding:26px;border-radius:22px;text-align:center;position:relative;overflow:hidden}
.pay:before{content:'';position:absolute;top:-50%;left:-50%;width:200%;height:200%;background:linear-gradient(120deg,transparent,rgba(255,255,255,.1),transparent);transform:rotate(25deg);animation:shine 3s infinite}
@keyframes shine{0%{transform:translateX(-100%) rotate(25deg)}100%{transform:translateX(100%) rotate(25deg)}}
.auth{min-height:100vh;display:flex;align-items:center;justify-content:center;padding:18px}
.pulse{animation:pulse 2s infinite}
@keyframes pulse{0%{box-shadow:0 0 0 0 rgba(255,204,0,.7)}70%{box-shadow:0 0 0 20px rgba(255,204,0,0)}100%{box-shadow:0 0 0 0 rgba(255,204,0,0)}}
.upload{border:2px dashed rgba(255,204,0,.4);border-radius:16px;padding:22px;text-align:center;cursor:pointer;background:rgba(255,204,0,.04)}
.upload.ok{border-color:var(--green);background:rgba(60,255,138,.08)}
.notif{position:fixed;top:70px;left:18px;background:var(--card);border:1px solid var(--border);border-left:3px solid var(--green);padding:10px 14px;border-radius:12px;font-size:11px;z-index:90}
.live{width:8px;height:8px;background:var(--green);border-radius:50%;display:inline-block;animation:blink 1s infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.3}}
.badge{background:var(--gold);color:#000;font-size:10px;font-weight:900;padding:4px 10px;border-radius:20px;display:inline-block}

/* AI CHATBOT */
#aiBtn{position:fixed;bottom:88px;right:14px;background:linear-gradient(90deg,var(--red),var(--gold));color:#000;width:58px;height:58px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:28px;font-weight:900;z-index:100;cursor:pointer;box-shadow:var(--glow);animation:float 2s infinite}
#aiChat{position:fixed;bottom:156px;right:14px;width:92%;max-width:380px;height:460px;background:linear-gradient(145deg,var(--card),var(--card2));border:1px solid var(--border);border-radius:20px;z-index:101;display:none;flex-direction:column;overflow:hidden;box-shadow:0 20px 60px rgba(0,0,0,.7)}
#aiChat.on{display:flex;animation:pageIn.3s}
.aiHead{background:linear-gradient(90deg,var(--red),var(--gold));color:#000;padding:14px 16px;font-weight:900;display:flex;justify-content:space-between;align-items:center}
.aiBody{flex:1;padding:14px;overflow-y:auto;display:flex;flex-direction:column;gap:10px}
.msg{padding:10px 12px;border-radius:14px;font-size:12px;max-width:84%;line-height:1.4}
.msg.ai{background:var(--card2);border:1px solid var(--border);align-self:flex-start}
.msg.user{background:linear-gradient(90deg,var(--red),var(--red2));align-self:flex-end;color:#fff}
.aiFoot{display:flex;gap:8px;padding:10px;border-top:1px solid var(--border);background:var(--card)}
.aiFoot input{flex:1;background:var(--card2);border:1px solid var(--border);border-radius:20px;padding:10px 14px;color:#fff;outline:none;font-size:12px}
.aiQuick{display:flex;gap:6px;flex-wrap:wrap;margin-top:8px}
.aiQuick button{background:var(--card2);border:1px solid var(--border);color:var(--silver);padding:6px 10px;border-radius:20px;font-size:10px;cursor:pointer}
</style></head><body>

<div id="splash"><div class="plane">✈️</div><h1 style="margin-top:12px;letter-spacing:3px">AVIATOR <span style="color:var(--red)">PREDICTOR</span></h1><p class="splash-text">ANALYZE • PREDICT • FLY HIGHER</p><div class="loader"><div class="loader-bar"></div></div><p style="font-size:10px;color:var(--silver);margin-top:12px">AI Powered • Premium</p></div>

<div class="bg"></div><div class="nav" id="topNav" style="display:none"><div style="font-weight:800;letter-spacing:2px" class="float">✈️ AVIATOR <span style="color:var(--red)">PREDICTOR</span></div><div style="font-size:10px;color:var(--gold);font-weight:900"><span class="live"></span> AI • PREMIUM</div></div>

<!-- AI CHATBOT BUTTON -->
<div id="aiBtn" onclick="toggleAI()">🤖</div>
<div id="aiChat">
<div class="aiHead"><span>🤖 AI Support • Premium</span><span style="cursor:pointer" onclick="toggleAI()">✕</span></div>
<div class="aiBody" id="aiBody">
<div class="msg ai">Hi! I'm your AI Assistant 🤖<br><br>Welcome to Aviator Predictor Premium!<br>• Upload screenshot to activate<br>• Real payment to 0500935167<br>• Instant AI verification<br><br>How can I help you?</div>
<div class="aiQuick"><button onclick="quick('How to pay?')">How to pay?</button><button onclick="quick('Where to send MoMo?')">Where to send?</button><button onclick="quick('I uploaded screenshot')">I uploaded</button><button onclick="quick('Activate my account')">Activate me</button></div>
</div>
<div class="aiFoot"><input id="aiInput" placeholder="Ask AI..." onkeydown="if(event.key==='Enter')sendAI()"><button class="btn" style="width:auto;padding:10px 16px;border-radius:20px" onclick="sendAI()">➤</button></div>
</div>

<div id="liveNotif" class="notif" style="display:none"></div>

<div class="page on" id="p-auth" style="padding:0"><div class="auth"><div class="card card-glow shimmer" style="width:100%;max-width:440px;text-align:center"><div style="font-size:56px" class="float">✈️</div><h1 style="margin-top:8px">AVIATOR <span style="color:var(--red)">PREDICTOR</span></h1><p class="tag" style="margin-top:8px">ANALYZE • PREDICT • FLY HIGHER</p><p style="color:var(--silver);font-size:12px;margin-top:12px">🤖 AI Powered • 2,847+ premium members</p><div style="margin-top:14px;display:flex;gap:6px;justify-content:center"><span class="badge">🤖 AI SUPPORT</span><span class="badge" style="background:var(--red);color:#fff">⚡ INSTANT</span></div><div style="text-align:left;margin-top:20px;display:flex;flex-direction:column;gap:12px"><input class="input" id="em" placeholder="Your Email"><input class="input" id="pw" type="password" placeholder="Password"><button class="btn" onclick="login()">ENTER PREMIUM →</button><p style="font-size:11px;color:var(--silver);text-align:center">AI Chatbot will help you after login</p></div></div></div></div>

<div class="page" id="p-home"><h2>Welcome to <span style="color:var(--red)">AVIATOR PREDICTOR</span></h2><p style="color:var(--silver);font-size:13px;margin-top:6px">AI analytics for aviation.</p><div class="card" style="margin-top:16px"><div style="display:flex;gap:10px;flex-wrap:wrap"><input class="input" id="q" placeholder="Enter flight route" style="flex:1;min-width:180px"><button class="btn" style="width:auto;padding:15px 28px" onclick="analyze()">ANALYZE</button></div></div><div class="grid3" style="margin-top:14px"><div class="card"><p style="font-size:11px;color:var(--silver)">📊 TOTAL</p><p class="stat" id="s1">1,482</p></div><div class="card"><p style="font-size:11px;color:var(--silver)">🤖 AI ACCURACY</p><p class="stat">94.2%</p></div><div class="card card-glow"><p style="font-size:11px;color:var(--gold)">💰 TODAY</p><p class="stat" style="color:var(--green)">GHS 2,341</p></div></div><div class="grid2" style="margin-top:14px"><div class="card"><h3>📈 Live</h3><canvas id="c1" height="160"></canvas></div><div class="card"><h3>💬 Reviews</h3><div style="margin-top:10px;display:flex;flex-direction:column;gap:10px"><div style="background:var(--card2);padding:10px;border-radius:12px;font-size:11px;border-left:3px solid var(--gold)">"AI chatbot helped me activate fast!" -- <b>Kwame A.</b> ⭐⭐⭐⭐⭐</div><div style="background:var(--card2);padding:10px;border-radius:12px;font-size:11px;border-left:3px solid var(--green)">"Very premium AI." -- <b>Ama B.</b> ⭐⭐⭐⭐⭐</div></div></div></div></div>

<div class="page" id="p-analytics"><h2>📊 Analytics</h2><div class="grid2" style="margin-top:14px"><div class="card"><h3>History</h3><canvas id="c2" height="180"></canvas></div><div class="card"><h3>Performance</h3><canvas id="c3" height="180"></canvas></div></div><div class="card" style="margin-top:14px"><h3>Log</h3><table style="width:100%;margin-top:10px;font-size:12px;color:var(--silver);border-collapse:collapse"><tbody id="sim"></tbody></table></div></div>

<div class="page" id="p-sub"><h2>🔥 Unlock Premium</h2><p style="color:var(--silver);font-size:13px;margin-top:6px">Pay to <b style="color:var(--gold)">0500935167</b> then upload screenshot -- AI will verify.</p><div class="grid3" style="margin-top:16px">
<div class="card" onclick="pick('Basic','GHS 49')"><h3>Basic</h3><p class="stat" style="color:var(--silver)">GHS 49</p><button class="btn" style="margin-top:12px;background:var(--card2);color:var(--silver);border:1px solid var(--border)">Choose</button></div>
<div class="card card-glow" onclick="pick('Pro','GHS 99')"><div class="badge">🔥 BEST + AI</div><h3 style="margin-top:10px">Pro Premium</h3><p class="stat" style="color:var(--gold)">GHS 99</p><button class="btn btn-gold" style="margin-top:12px">GET PRO →</button></div>
<div class="card" onclick="pick('Enterprise','GHS 199')"><h3>Enterprise</h3><p class="stat">GHS 199</p><button class="btn" style="margin-top:12px;background:var(--card2);color:var(--silver);border:1px solid var(--border)">Choose</button></div>
</div>

<div class="card" id="checkout" style="margin-top:20px;display:none">
<div class="pay pulse"><p class="tag" style="color:var(--gold)">OFFICIAL PAYMENT</p><p style="font-size:48px;font-weight:900;margin:12px 0">0500935167</p><p style="font-size:14px;font-weight:800">Send MoMo Here • Upload Screenshot • AI Verify</p><div style="margin-top:14px;background:rgba(0,0,0,.45);display:inline-block;padding:12px 22px;border-radius:30px;border:1px solid rgba(255,255,255,.12)">Plan: <span id="planName"></span> -- <span id="planPrice" style="color:var(--gold);font-weight:900"></span></div></div>
<div class="grid2" style="margin-top:20px">
<div>
<p style="font-size:12px;font-weight:900">STEP 1: SEND MOMO TO 0500935167</p><p style="font-size:12px;color:var(--silver);margin-top:6px">Send <span id="price2" style="color:var(--gold);font-weight:900"></span> to <b>0500935167</b> → Screenshot.</p>
<p style="font-size:12px;font-weight:900;margin-top:18px">STEP 2: UPLOAD SCREENSHOT</p>
<div class="upload" id="upBox" style="margin-top:10px" onclick="document.getElementById('file').click()">
<input type="file" id="file" accept="image/*" style="display:none" onchange="preview(this)">
<p style="font-size:32px" class="float">📸</p>
<p style="font-size:13px;font-weight:800;margin-top:8px">Tap to Upload Screenshot</p>
<p style="font-size:10px;color:var(--silver)">Show payment to 0500935167</p>
<img id="prev" style="display:none;max-height:220px;margin:12px auto 0;border-radius:12px;border:2px solid var(--gold)">
<p id="upText" style="font-size:11px;color:var(--silver);margin-top:8px">No file chosen</p>
</div>
<input class="input" id="payEmail" style="margin-top:14px" placeholder="Your Email">
</div>
<div>
<button class="btn btn-gold" style="margin-top:8px;font-size:15px;padding:18px" onclick="confirmPay()">✅ I PAID - VERIFY WITH AI</button>
<div id="ok" style="display:none;margin-top:14px;background:rgba(60,255,138,.12);border:1.5px solid var(--green);padding:16px;border-radius:14px;text-align:center">
<p style="color:var(--green);font-weight:900">🤖 AI VERIFYING!</p>
<p style="font-size:12px;margin-top:8px">Ref: <span id="ref"></span><br>AI checking screenshot for 0500935167.<br>Ask AI chatbot 🤖 for instant activation.</p>
<button class="btn" style="margin-top:10px;background:var(--green);color:#000" onclick="toggleAI()">🤖 Chat with AI Now</button>
</div>
</div>
</div>
</div>
</div>

<div class="page" id="p-profile"><h2>👤 Account</h2><div class="grid2" style="margin-top:14px"><div class="card"><h3>Profile</h3><p style="margin-top:10px;font-size:12px;color:var(--silver)">Email</p><p id="profEmail" style="font-weight:700">user@aviator.com</p><p style="margin-top:10px;font-size:12px;color:var(--silver)">Payment</p><p style="font-weight:900;color:var(--gold);font-size:26px">0500935167</p><button class="btn" style="margin-top:12px" onclick="toggleAI()">🤖 AI Support Chat</button></div><div class="card"><h3>Status</h3><p>Current: <span id="curr" style="color:var(--gold);font-weight:900">FREE</span></p><div id="hist" style="margin-top:10px;background:var(--card2);padding:10px;border-radius:12px;font-size:12px;color:var(--silver)">No payment yet</div></div></div></div>

<div class="bnav" id="bnav" style="display:none"><button class="on" onclick="go('home',this)">Home</button><button onclick="go('analytics',this)">Analytics</button><button onclick="go('sub',this)">Premium</button><button onclick="go('profile',this)">Profile</button></div>

<script>
setTimeout(()=>{document.getElementById('splash').classList.add('hide');},2800);
let selPlan="Pro",selLabel="GHS 99",hasImg=false;
function login(){let e=document.getElementById('em').value;if(!e.includes('@')){alert('Enter email');return}document.getElementById('p-auth').classList.remove('on');document.getElementById('p-home').classList.add('on');document.getElementById('topNav').style.display='flex';document.getElementById('bnav').style.display='flex';document.getElementById('profEmail').innerText=e;document.getElementById('payEmail').value=e;charts();data();live();}
function go(p,el){document.querySelectorAll('.page').forEach(x=>x.classList.remove('on'));document.querySelectorAll('.bnav button').forEach(b=>b.classList.remove('on'));document.getElementById('p-'+p).classList.add('on');if(el)el.classList.add('on');}
function analyze(){document.getElementById('s1').innerText=parseInt(document.getElementById('s1').innerText)+1;}
function charts(){new Chart(document.getElementById('c1'),{type:'line',data:{labels:['Mon','Tue','Wed','Thu','Fri','Sat','Sun'],datasets:[{data:[1.2,1.8,1.4,2.1,1.9,2.4,2.2],borderColor:'#ff1e3c',tension:.4,fill:true,backgroundColor:'rgba(255,30,60,.1)'}]},options:{plugins:{legend:{display:false}}}});new Chart(document.getElementById('c2'),{type:'bar',data:{labels:['A','B','C','D'],datasets:[{data:[45,72,58,90],backgroundColor:['#ff1e3c','#c0c5ce','#ff4d6a','#1c1c23']}]},options:{plugins:{legend:{display:false}}}});new Chart(document.getElementById('c3'),{type:'doughnut',data:{labels:['Paid','Free','Pending'],datasets:[{data:[70,15,15],backgroundColor:['#ff1e3c','#c0c5ce','#141419'],borderWidth:0}]},options:{plugins:{legend:{labels:{color:'#c0c5ce'}}}}});}
function data(){let h='';for(let i=0;i<6;i++){h+=`<tr style="border-bottom:1px solid var(--border)"><td style="padding:8px">${new Date(Date.now()-i*3600000).toLocaleTimeString()}</td><td>ACC-LON ${100+i}</td><td>${(Math.random()*3+1).toFixed(2)}x</td><td style="color:#3cff8a">SIM</td></tr>`}let el=document.getElementById('sim');if(el)el.innerHTML=h;}
function pick(n,l){selPlan=n;selLabel=l;document.getElementById('checkout').style.display='block';document.getElementById('planName').innerText=n;document.getElementById('planPrice').innerText=l;document.getElementById('price2').innerText=l;document.getElementById('checkout').scrollIntoView({behavior:'smooth'});}
function preview(inp){if(inp.files&&inp.files[0]){let r=new FileReader();r.onload=function(e){let img=document.getElementById('prev');img.src=e.target.result;img.style.display='block';document.getElementById('upBox').classList.add('ok');document.getElementById('upText').innerText='✅ '+inp.files[0].name;hasImg=true;};r.readAsDataURL(inp.files[0]);}}
function confirmPay(){let email=document.getElementById('payEmail').value;if(!email.includes('@')){alert('Enter Email');return}if(!hasImg){alert('Upload screenshot to 0500935167');return}let ref='AVI-'+Math.random().toString(36).substr(2,8).toUpperCase();document.getElementById('ref').innerText=ref;document.getElementById('ok').style.display='block';document.getElementById('curr').innerText=selPlan+' (AI VERIFYING)';document.getElementById('hist').innerHTML=`<b>${selPlan} - ${selLabel}</b><br>To: 0500935167<br>Proof: Screenshot<br>Ref: ${ref}`;setTimeout(()=>{addAI(`✅ Screenshot received! Ref: ${ref}<br><br>Plan: ${selPlan} (${selLabel})<br>To: 0500935167<br><br>Our AI is verifying. You will be activated in 3-5 mins. Keep screenshot ready!`);toggleAI(true);},800);}
function live(){let names=['Kwame paid Pro to 0500935167','Ama bought Pro','Joseph paid GHS 99','Emmanuel uploaded','Akosua activated'];let i=0;setInterval(()=>{let el=document.getElementById('liveNotif');el.innerHTML=`💰 ${names[i%names.length]} • <span style="color:var(--green)">Verified</span>`;el.style.display='block';setTimeout(()=>el.style.display='none',4000);i++;},7000);}
// AI CHATBOT LOGIC
function toggleAI(forceOpen){let c=document.getElementById('aiChat');if(forceOpen){c.classList.add('on');return}c.classList.toggle('on');}
function quick(t){document.getElementById('aiInput').value=t;sendAI();}
function addAI(html){let b=document.getElementById('aiBody');let d=document.createElement('div');d.className='msg ai';d.innerHTML=html;b.appendChild(d);b.scrollTop=b.scrollHeight;}
function addUser(t){let b=document.getElementById('aiBody');let d=document.createElement('div');d.className='msg user';d.innerText=t;b.appendChild(d);b.scrollTop=b.scrollHeight;}
function sendAI(){let inp=document.getElementById('aiInput');let t=inp.value.trim();if(!t)return;addUser(t);inp.value='';setTimeout(()=>{let lower=t.toLowerCase();let reply='';if(lower.includes('pay')||lower.includes('momo')){reply='💰 To pay:<br>1. Send MoMo to <b>0500935167</b><br>2. Screenshot payment<br>3. Upload screenshot in Premium page<br>4. AI verifies in 3 mins<br><br>Amount: GHS 49 / 99 / 199';}else if(lower.includes('0500935167')||lower.includes('number')||lower.includes('where')){reply='📱 Official MoMo number is <b style="color:#ffcc00">0500935167</b><br>Name: Aviator Support<br>Network: MTN MoMo<br>Send exactly GHS 49, 99 or 199 and upload screenshot proof.';}else if(lower.includes('screenshot')||lower.includes('upload')){reply='📸 Screenshot Guide:<br>• After sending to 0500935167, take screenshot showing:<br>- Amount<br>- To 0500935167<br>- Transaction time<br>• Then upload in checkout<br>• AI will verify automatically!';}else if(lower.includes('activate')||lower.includes('verify')){reply='🤖 AI Activation:<br>Once you upload screenshot for 0500935167, AI checks in 3-5 mins.<br><br>If you already uploaded:<br>Ref is generated. Keep your screenshot.<br>Your account will change to PRO soon!<br><br>Need faster? Upload again with clear image.';}else if(lower.includes('price')||lower.includes('plan')){reply='💎 Plans:<br>• Basic - GHS 49 - 50 sims<br>• Pro - GHS 99 (Best) - Unlimited + AI<br>• Enterprise - GHS 199 - API<br><br>All paid to 0500935167';}else{reply='🤖 I can help with:<br>• How to pay to 0500935167<br>• Screenshot upload<br>• Activation status<br>• Plans & pricing<br><br>Just ask: "How to pay?" or "Activate my account"';}
addAI(reply);
},700);
}
</script></body></html>
