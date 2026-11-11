<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>massege to menna ❤️</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&family=Playfair+Display:ital,wght@1,700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Cairo',sans-serif}
body{background:#fff5f6;color:#7a1f3a;overflow-x:hidden;text-align:center}
section{min-height:100vh;padding:50px 20px;display:flex;flex-direction:column;align-items:center;justify-content:center}
h1{font-family:'Playfair Display',serif;font-size:42px;line-height:1.2}
h2{font-size:32px;margin-bottom:15px}
p{max-width:600px;line-height:1.9;font-size:18px}
.pink-btn{background:#e84a7a;color:#fff;border:none;padding:14px 30px;border-radius:50px;font-size:18px;font-weight:900;cursor:pointer;box-shadow:0 10px 25px rgba(232,74,122,.4)}
input{font-size:28px;letter-spacing:10px;text-align:center;border:2px solid #ffc2d1;padding:10px;border-radius:15px;width:200px;outline:none;margin:15px 0}
.card{background:#fff;border-radius:25px;padding:25px;box-shadow:0 15px 40px rgba(0,0,0,.08);margin:20px 0;max-width:600px;width:100%}
.card img{width:100%;border-radius:18px;object-fit:cover;height:300px}
.memory{display:flex;gap:20px;align-items:center;max-width:800px;margin:25px auto;text-align:right;flex-wrap:wrap;justify-content:center}
.memory img{width:280px;height:280px;object-fit:cover;border-radius:25px}
.memory div{max-width:400px}
.scratch-wrap{display:flex;gap:15px;flex-wrap:wrap;justify-content:center;margin-top:20px}
.scratch-box{position:relative;width:180px;height:130px;background:#ffd6e0;border-radius:15px;overflow:hidden;display:flex;align-items:center;justify-content:center;font-weight:900;padding:10px}
.scratch-box canvas{position:absolute;inset:0;cursor:pointer}
.envelope{width:320px;height:210px;background:#ff8fab;position:relative;border-radius:15px;cursor:pointer;margin:30px auto;overflow:hidden;transition:.6s}
.envelope.open{height:360px}
.envelope .flap{position:absolute;top:0;left:0;width:100%;height:110px;background:#ff5d8f;clip-path:polygon(0 0,100% 0,50% 100%);transition:.6s;z-index:2}
.envelope.open .flap{transform:rotateX(180deg);opacity:0}
.letter{background:#fff;margin:15px;padding:18px;border-radius:10px;font-size:16px;line-height:1.9;position:relative;z-index:1}
.cake{font-size:110px;cursor:pointer;position:relative}
.hidden{display:none!important}
.heart{position:fixed;bottom:-20px;animation:fly 4s linear forwards;pointer-events:none;z-index:999}
@keyframes fly{to{transform:translateY(-110vh) rotate(360deg);opacity:0}}
#lock{position:fixed;inset:0;background:#fff5f6;z-index:1000;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:20px}
.keypad{display:grid;grid-template-columns:repeat(3,70px);gap:10px;margin-top:10px}
.keypad button{height:60px;border-radius:50%;border:1px solid #ffc2d1;background:#fff;font-size:22px;cursor:pointer}
#dots{font-size:30px;letter-spacing:8px;height:40px}
</style>
</head>
<body>

<!-- ===== شاشة القفل ===== -->
<div id="lock">
  <div style="font-size:60px">💌</div>
  <h2>A Special Delivery</h2>
  <p>11/11</p>
  <div id="dots">○ ○ ○ ○</div>
  <div class="keypad" id="keypad"></div>
  <p id="lockMsg" style="color:red"></p>
  <small>الباسورد هو تاريخ اليوم اللي عرفنا بعض فيه</small>
</div>

<!-- ===== البداية ===== -->
<section>
  <h1 id="mainTitle">Happy Birthday,<br>menna ❤️</h1>
  <p style="margin-top:15px">انزلي تحت عشان تشوفي المفاجأة</p>
  <div style="font-size:40px;margin-top:20px">↓</div>
</section>

<!-- ===== ذكرياتنا ===== -->
<section>
  <h2>Our Story 💕</h2>
  <p>كل لحظة معاكي بقت ذكرى مش بتتنسي</p>
  <div class="memory card">
    <img src="https://i.postimg.cc/3JRwGZQ5/IMG-9a7a6a16-62f5-45ab-9fc7-77665c9cf620.jpg">
    <div><h3>أول يوم</h3><p>اليوم اللي عرفتك فيه كان أفضل يوم بالنسبالي واتمني نفضل مع بعض لآخر العمر</p></div>
  </div>
  <div class="memory card">
    <div><h3>reading</h3><p>i love you my heart & i hope stay you with me to other day on my life</p></div>
    <img src="https://i.postimg.cc/MZs6zjfn/IMG-6b6cb2c5-2981-484a-9e63-1f4da908c39c.jpg">
  </div>
  <div class="memory card">
    <img src="https://i.postimg.cc/XY54KHHM/IMG-5c7c4071-a0ea-4a21-8e6b-4622d4e1064c.jpg">
    <div><h3>لسه اللي جاي أحلى</h3><p>‏بمـناسـبه يـوم الحـب العـالمي11/11
كل عام وانتِ بخير كل عام وانتِ  معايا ومنتفرقش عن بعض ابداً</p></div>
  </div>
</section>

<!-- ===== خربش ===== -->
<section>
  <h2>Things I Love About You</h2>
  <p>خربشي الكروت بصباعك عشان تشوف بحب فيكي ايه</p>
  <div class="scratch-wrap">
    <div class="scratch-box"><span>ضحكتك بتنور يومي ✨</span><canvas width="180" height="130"></canvas></div>
    <div class="scratch-box"><span>قلبك أطيب قلب شُفته ❤️</span><canvas width="180" height="130"></canvas></div>
    <div class="scratch-box"><span>انتي أحلى حاجة حصلتلي 🥹</span><canvas width="180" height="130"></canvas></div>
  </div>
</section>

<!-- ===== الجواب ===== -->
<section>
  <h2>A Letter From My Heart 💌</h2>
  <p>دوسي على الظرف عشان تفتحيه</p>
  <div class="envelope" id="envelope">
    <div class="flap"></div>
    <div class="letter" id="letterText">💗💗<br><br>انا حبيت اعملك الموقع ده عشان انت تستاهلي كل حاجة حلوة. كل سنة وانت طيبة يا أحلى حد في حياتي ❤️<br><br><b>With all my love.</b></div>
  </div>
</section>

<!-- ===== التورتة ===== -->
<section>
  <div class="cake" id="cake">🎂<div id="flame" style="position:absolute;top:-10px;left:50%;transform:translateX(-50%);font-size:30px">🔥</div></div>
  <h2 style="margin-top:20px">دوسي على التورتة واطفي الشمعة بتاعتك</h2>
  <button class="pink-btn" onclick="celebrate()">Make a wish ✨</button>
  <p id="wishMsg" class="hidden" style="font-size:24px;font-weight:900;margin-top:20px">Happy Birthday menna! 🎉🎂<br>يارب كل سنينك تبقى حلوة زيك</p>
</section>

<script>
// ===== 🔴🔴 عدل من هنا بس 🔴🔴 =====
const CONFIG = {
  password: "2405", // <-- غير الرقم السري هنا
  name: "menna", // <-- اسمها
};
// ===================================

let entered = "";
const dots = document.getElementById('dots');
const keypad = document.getElementById('keypad');
for(let i=1;i<=9;i++){let b=document.createElement('button');b.textContent=i;b.onclick=()=>press(i);keypad.appendChild(b)}
let b0=document.createElement('button');b0.textContent='C';b0.onclick=()=>{entered='';updateDots()};keypad.appendChild(b0);
let b10=document.createElement('button');b10.textContent=0;b10.onclick=()=>press(0);keypad.appendChild(b10);
let b11=document.createElement('button');b11.textContent='⌫';b11.onclick=()=>{entered=entered.slice(0,-1);updateDots()};keypad.appendChild(b11);

function updateDots(){dots.textContent = entered.split('').map(()=> '●').join(' ') + ' ○'.repeat(4-entered.length)}
function press(n){
  if(entered.length>=4) return;
  entered+=n; updateDots();
  if(entered.length===4){
    if(entered===CONFIG.password){
      document.getElementById('lock').style.display='none';
      startHearts();
    } else {
      document.getElementById('lockMsg').textContent='الرقم غلط، حاولي تاني 🥺';
      entered=''; setTimeout(updateDots,300);
    }
  }
}
function startHearts(){setInterval(()=>{let h=document.createElement('div');h.className='heart';h.textContent=['❤️','💖','💕','✨'][Math.floor(Math.random()*4)];h.style.left=Math.random()*100+'vw';h.style.fontSize=(16+Math.random()*20)+'px';document.body.appendChild(h);setTimeout(()=>h.remove(),4000)},600)}

// خربشة
document.querySelectorAll('.scratch-box canvas').forEach(cv=>{
  let ctx=cv.getContext('2d'); ctx.fillStyle='#f7a8b8'; ctx.fillRect(0,0,180,130);
  ctx.fillStyle='#fff'; ctx.font='bold 16px Cairo'; ctx.fillText('Scratch Me',45,70);
  let drawing=false;
  function scratch(e){if(!drawing)return;let r=cv.getBoundingClientRect();let x=(e.touches?e.touches[0].clientX:e.clientX)-r.left;let y=(e.touches?e.touches[0].clientY:e.clientY)-r.top;ctx.globalCompositeOperation='destination-out';ctx.beginPath();ctx.arc(x,y,20,0,Math.PI*2);ctx.fill()}
  cv.addEventListener('mousedown',()=>drawing=true); cv.addEventListener('mouseup',()=>drawing=false); cv.addEventListener('mousemove',scratch);
  cv.addEventListener('touchstart',()=>drawing=true); cv.addEventListener('touchend',()=>drawing=false); cv.addEventListener('touchmove',scratch);
});

// جواب
document.getElementById('envelope').onclick=function(){this.classList.toggle('open')}

// تورتة
document.getElementById('cake').onclick=function(){document.getElementById('flame').textContent='💨';celebrate()}
function celebrate(){
  document.getElementById('flame').textContent='💨';
  document.getElementById('wishMsg').classList.remove('hidden');
  for(let i=0;i<50;i++){setTimeout(()=>{let h=document.createElement('div');h.className='heart';h.textContent='🎉';h.style.left=Math.random()*100+'vw';document.body.appendChild(h);setTimeout(()=>h.remove(),3000)},i*50)}
}
</script>
</body>
</html>
