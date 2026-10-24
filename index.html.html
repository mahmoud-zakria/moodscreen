<!doctype html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#07111f">
<title>MOODSCREEN</title>
<style>
:root{--bg:#07111f;--fg:#f5f7ff;--muted:#aab6cc;--accent:#a78bfa;--accent2:#60a5fa;--glass:rgba(9,18,34,.58);--line:rgba(255,255,255,.14)}
*{box-sizing:border-box}
html,body{margin:0;width:100%;height:100%;overflow:hidden;background:var(--bg);color:var(--fg);font-family:Arial,"Noto Sans Arabic",sans-serif}
body{min-height:100dvh}
.scene{position:fixed;inset:0;overflow:hidden;background:linear-gradient(125deg,#081426,#17264a 45%,#321f58)}
.scene:before,.scene:after{content:"";position:absolute;inset:-20%;pointer-events:none}
.scene:before{background:radial-gradient(ellipse at 18% 25%,rgba(64,162,255,.45),transparent 32%),radial-gradient(ellipse at 78% 70%,rgba(151,71,255,.4),transparent 34%),radial-gradient(ellipse at 48% 100%,rgba(15,118,110,.24),transparent 30%);filter:blur(10px);animation:drift 24s ease-in-out infinite alternate}
.scene:after{background:linear-gradient(115deg,transparent 20%,rgba(255,255,255,.045) 48%,transparent 64%);transform:translateX(-25%);animation:shimmer 18s linear infinite}
.orb{position:absolute;border-radius:50%;filter:blur(2px);opacity:.5;mix-blend-mode:screen;animation:float 19s ease-in-out infinite alternate}
.orb.one{width:38vw;height:38vw;min-width:320px;min-height:320px;top:-12%;left:-4%;background:radial-gradient(circle at 35% 35%,rgba(140,204,255,.65),rgba(59,130,246,.05) 65%,transparent 70%)}
.orb.two{width:45vw;height:45vw;min-width:350px;min-height:350px;bottom:-25%;right:-6%;background:radial-gradient(circle at 45% 35%,rgba(192,132,252,.55),rgba(124,58,237,.04) 67%,transparent 72%);animation-delay:-6s}
.orb.three{width:24vw;height:24vw;min-width:200px;min-height:200px;top:40%;left:45%;background:radial-gradient(circle,rgba(45,212,191,.18),transparent 68%);animation-delay:-10s}
.vignette{position:absolute;inset:0;background:linear-gradient(90deg,rgba(3,8,18,.18),transparent 45%,rgba(3,8,18,.18)),linear-gradient(0deg,rgba(2,7,16,.5),transparent 35%,rgba(2,7,16,.2))}
.app{position:relative;z-index:2;width:100%;height:100%;padding:4.2vh 5vw 3.5vh;display:flex;flex-direction:column;justify-content:space-between}
.top{display:flex;align-items:center;justify-content:space-between;gap:24px}
.brand{display:flex;align-items:center;gap:13px;direction:ltr}
.mark{width:42px;height:42px;border:1px solid rgba(255,255,255,.28);border-radius:14px;display:grid;place-items:center;background:rgba(255,255,255,.08);box-shadow:0 10px 35px #0002}
.mark span{width:17px;height:17px;border-radius:6px;background:linear-gradient(135deg,var(--accent2),var(--accent));transform:rotate(35deg);display:block}
.brandname{font-size:clamp(14px,1.4vw,22px);letter-spacing:.22em;font-weight:700}
.brandtag{font-size:11px;letter-spacing:.18em;color:#b7c3d8;margin-top:4px}
.topright{display:flex;align-items:center;gap:12px;color:var(--muted);font-size:clamp(12px,1vw,16px)}
.statusdot{width:7px;height:7px;border-radius:50%;background:#6ee7b7;box-shadow:0 0 14px #6ee7b7}
.center{max-width:1000px;margin:auto 0;position:relative}
.eyebrow{font-size:clamp(12px,1.15vw,18px);letter-spacing:.12em;color:#d4c7ff;margin-bottom:18px;display:flex;align-items:center;gap:12px}
.eyebrow:before{content:"";width:32px;height:1px;background:var(--accent)}
h1{font-size:clamp(54px,8.3vw,136px);line-height:.98;letter-spacing:-.055em;margin:0 0 24px;font-weight:600;max-width:1000px}
.subtitle{font-size:clamp(17px,1.7vw,26px);line-height:1.6;color:#d0d8e8;max-width:690px;margin:0}
.timeblock{position:absolute;left:0;top:4vh;text-align:left;direction:ltr}
.clock{font-size:clamp(34px,4vw,64px);font-weight:300;letter-spacing:-.04em;font-variant-numeric:tabular-nums}
.date{font-size:clamp(12px,1.1vw,17px);color:var(--muted);margin-top:6px}
.bottom{display:flex;align-items:flex-end;justify-content:space-between;gap:24px}
.moods{display:flex;gap:10px;flex-wrap:wrap}
.mood{appearance:none;border:1px solid var(--line);color:#e9edfa;background:rgba(8,16,31,.3);backdrop-filter:blur(16px);padding:13px 19px;border-radius:999px;font-size:clamp(13px,1.05vw,17px);cursor:pointer;transition:.25s;outline:none}
.mood:focus-visible,.mood.active{border-color:rgba(255,255,255,.65);background:rgba(255,255,255,.16);box-shadow:0 0 0 2px rgba(167,139,250,.25),0 8px 32px #0002}
.mood:hover{background:rgba(255,255,255,.13)}
.hint{font-size:12px;color:#aab6cc;white-space:nowrap}
.footer{position:absolute;bottom:1.2vh;left:5vw;right:5vw;display:flex;justify-content:space-between;direction:ltr;font-size:10px;letter-spacing:.12em;color:#8290a8;opacity:.8}
.toast{position:fixed;z-index:10;left:50%;bottom:7vh;transform:translate(-50%,20px);opacity:0;pointer-events:none;border:1px solid var(--line);border-radius:14px;padding:12px 18px;background:rgba(6,13,25,.86);color:#fff;transition:.25s;font-size:14px}
.toast.show{opacity:1;transform:translate(-50%,0)}
@keyframes drift{from{transform:translate(-2%,-1%) scale(1)}to{transform:translate(3%,2%) scale(1.12)}}
@keyframes shimmer{from{transform:translateX(-40%)}to{transform:translateX(40%)}}
@keyframes float{from{transform:translate3d(-2%,1%,0) scale(.96)}to{transform:translate3d(3%,-3%,0) scale(1.08)}}
body[data-mood="dawn"] .scene{background:linear-gradient(125deg,#1c3047,#b07864 58%,#f3bd8b)}
body[data-mood="dawn"] .scene:before{background:radial-gradient(ellipse at 18% 25%,rgba(255,226,170,.62),transparent 34%),radial-gradient(ellipse at 78% 70%,rgba(247,166,130,.42),transparent 35%),radial-gradient(ellipse at 48% 100%,rgba(66,140,153,.25),transparent 30%)}
body[data-mood="focus"] .scene{background:linear-gradient(125deg,#071c2c,#12475b 50%,#142b49)}
body[data-mood="focus"] .scene:before{background:radial-gradient(ellipse at 18% 25%,rgba(45,212,191,.32),transparent 32%),radial-gradient(ellipse at 78% 70%,rgba(96,165,250,.35),transparent 34%),radial-gradient(ellipse at 48% 100%,rgba(14,116,144,.25),transparent 30%)}
body[data-mood="relax"] .scene{background:linear-gradient(125deg,#102b35,#1e5361 48%,#527b78)}
body[data-mood="relax"] .scene:before{background:radial-gradient(ellipse at 18% 25%,rgba(167,243,208,.32),transparent 32%),radial-gradient(ellipse at 78% 70%,rgba(94,234,212,.25),transparent 34%),radial-gradient(ellipse at 48% 100%,rgba(34,197,94,.18),transparent 30%)}
body[data-mood="cinema"] .scene{background:linear-gradient(125deg,#080b19,#1c1640 48%,#451b53)}
body[data-mood="cinema"] .scene:before{background:radial-gradient(ellipse at 18% 25%,rgba(96,165,250,.3),transparent 32%),radial-gradient(ellipse at 78% 70%,rgba(217,70,239,.32),transparent 34%),radial-gradient(ellipse at 48% 100%,rgba(124,58,237,.25),transparent 30%)}
body[data-mood="night"] .scene{background:linear-gradient(125deg,#02040c,#080e2b 50%,#21163b)}
body[data-mood="night"] .scene:before{background:radial-gradient(ellipse at 18% 25%,rgba(59,130,246,.25),transparent 32%),radial-gradient(ellipse at 78% 70%,rgba(139,92,246,.3),transparent 34%),radial-gradient(ellipse at 48% 100%,rgba(14,116,144,.14),transparent 30%)}
@media (max-width:900px){.app{padding:3vh 4vw}.timeblock{position:static;text-align:right;margin-top:28px}.center{margin:35px 0}.bottom{align-items:flex-start;flex-direction:column}.footer{left:4vw;right:4vw}.hint{white-space:normal}}
@media (prefers-reduced-motion:reduce){*,*:before,*:after{animation:none!important;transition:none!important}}
</style>
</head>
<body data-mood="cinema">
<div class="scene" aria-hidden="true"><div class="orb one"></div><div class="orb two"></div><div class="orb three"></div><div class="vignette"></div></div>
<main class="app">
  <header class="top">
    <div class="brand"><div class="mark"><span></span></div><div><div class="brandname">MOODSCREEN</div><div class="brandtag">YOUR SPACE. YOUR STATE.</div></div></div>
    <div class="topright"><span class="statusdot"></span><span id="modeLabel">CINEMA MODE</span><span>·</span><span>4K DISPLAY EXPERIENCE</span></div>
  </header>
  <section class="center">
    <div class="eyebrow" id="eyebrow">YOUR EVENING, REIMAGINED</div>
    <h1 id="headline">Find your<br>own universe.</h1>
    <p class="subtitle" id="subtitle">A quiet cinematic atmosphere, designed to shift with the rhythm of your day.</p>
    <div class="timeblock"><div class="clock" id="clock">21:00</div><div class="date" id="date">SATURDAY · OCTOBER 24</div></div>
  </section>
  <section class="bottom">
    <nav class="moods" aria-label="اختيار المزاج">
      <button class="mood" data-mood="dawn">☀ الصباح</button>
      <button class="mood" data-mood="focus">◈ تركيز</button>
      <button class="mood" data-mood="relax">≈ استرخاء</button>
      <button class="mood active" data-mood="cinema">✦ سينما</button>
      <button class="mood" data-mood="night">☾ الليل</button>
    </nav>
    <div class="hint">استخدم الأسهم للتنقل · Enter للاختيار · A للتلقائي</div>
  </section>
  <footer class="footer"><span>MOODSCREEN / CONCEPT 01</span><span id="autoStatus">AUTO MOOD: ON</span><span>MADE FOR THE BIG SCREEN</span></footer>
</main>
<div class="toast" id="toast" role="status"></div>
<script>
(function(){
  const $ = s => document.querySelector(s);
  const buttons = Array.from(document.querySelectorAll('.mood'));
  const modes = {
    dawn:{label:'DAWN MODE',eyebrow:'A GENTLE BEGINNING',headline:'Wake up<br>to possibility.',subtitle:'Warm light, open skies, and a fresh start for the day.'},
    focus:{label:'FOCUS MODE',eyebrow:'CLEAR MIND. OPEN SPACE.',headline:'Make room<br>for ideas.',subtitle:'A cool, quiet visual atmosphere to help you think and create.'},
    relax:{label:'RELAX MODE',eyebrow:'SLOW DOWN. BREATHE.',headline:'Let the world<br>move softly.',subtitle:'Calm tones and slow-moving light. Nothing to chase, nowhere to rush.'},
    cinema:{label:'CINEMA MODE',eyebrow:'YOUR EVENING, REIMAGINED',headline:'Find your<br>own universe.',subtitle:'A quiet cinematic atmosphere, designed to shift with the rhythm of your day.'},
    night:{label:'NIGHT MODE',eyebrow:'THE WORLD, TURNED DOWN',headline:'Drift into<br>the unknown.',subtitle:'Deep blues, violet light, and a slower rhythm for late hours.'}
  };
  let current='cinema', auto=true, focusIndex=3, toastTimer;
  function setMood(m, manual){
    if(!modes[m]) return;
    current=m; document.body.dataset.mood=m;
    $('#modeLabel').textContent=modes[m].label;
    $('#eyebrow').textContent=modes[m].eyebrow;
    $('#headline').innerHTML=modes[m].headline;
    $('#subtitle').textContent=modes[m].subtitle;
    buttons.forEach((b,i)=>{b.classList.toggle('active',b.dataset.mood===m);b.setAttribute('aria-pressed',b.dataset.mood===m?'true':'false');if(b.dataset.mood===m)focusIndex=i;});
    if(manual){auto=false;$('#autoStatus').textContent='AUTO MOOD: OFF';showToast('تم اختيار الوضع يدويًا · اضغط A للتلقائي');}
  }
  function suggestedMode(h){if(h>=5&&h<10)return'dawn';if(h>=10&&h<16)return'focus';if(h>=16&&h<19)return'relax';if(h>=19&&h<23)return'cinema';return'night';}
  function updateClock(){
    const now=new Date();
    $('#clock').textContent=new Intl.DateTimeFormat('en-GB',{hour:'2-digit',minute:'2-digit',hour12:false}).format(now);
    const days=['SUNDAY','MONDAY','TUESDAY','WEDNESDAY','THURSDAY','FRIDAY','SATURDAY'];
    const months=['JANUARY','FEBRUARY','MARCH','APRIL','MAY','JUNE','JULY','AUGUST','SEPTEMBER','OCTOBER','NOVEMBER','DECEMBER'];
    $('#date').textContent=days[now.getDay()]+' · '+months[now.getMonth()]+' '+now.getDate();
    if(auto){const next=suggestedMode(now.getHours());if(next!==current)setMood(next,false);}
  }
  function showToast(msg){const t=$('#toast');t.textContent=msg;t.classList.add('show');clearTimeout(toastTimer);toastTimer=setTimeout(()=>t.classList.remove('show'),2200);}
  buttons.forEach(b=>b.addEventListener('click',()=>setMood(b.dataset.mood,true)));
  document.addEventListener('keydown',e=>{
    if(['ArrowLeft','ArrowRight','ArrowUp','ArrowDown'].includes(e.key)){
      e.preventDefault();
      const delta=(e.key==='ArrowLeft'||e.key==='ArrowUp')?-1:1;
      focusIndex=(focusIndex+delta+buttons.length)%buttons.length;buttons[focusIndex].focus();
    } else if(e.key==='Enter'||e.key===' '){
      if(document.activeElement&&document.activeElement.classList.contains('mood')){e.preventDefault();setMood(document.activeElement.dataset.mood,true);}
    } else if(e.key.toLowerCase()==='a'){
      auto=!auto;$('#autoStatus').textContent='AUTO MOOD: '+(auto?'ON':'OFF');
      if(auto)setMood(suggestedMode(new Date().getHours()),false);
      showToast(auto?'تم تفعيل التغيير التلقائي حسب الوقت':'تم إيقاف التغيير التلقائي');
    } else if(e.key==='Escape'){showToast('MOODSCREEN · اضغط A للتبديل بين التلقائي واليدوي');}
  });
  // Start in automatic mode using the device's local time.
  setMood(suggestedMode(new Date().getHours()),false);
  updateClock();setInterval(updateClock,15000);
})();
</script>
</body>
</html>
