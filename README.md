<!DOCTYPE html>  <html lang="vi">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<meta name="theme-color" content="#100b20">  
<title>20/10 gửi Yến Nhi 💗</title>  
<style>  
*{box-sizing:border-box}  
body{  
  margin:0;min-height:100vh;padding:24px 16px;  
  display:flex;align-items:center;justify-content:center;  
  font-family:Arial,sans-serif;color:#fff3fa;text-align:center;  
  background:radial-gradient(ellipse at top,#482454,#171027 50%,#090815);  
  overflow-x:hidden  
}  
.card{  
  width:min(100%,470px);padding:30px 22px;  
  border:1px solid #754263;border-radius:28px;  
  background:#181027dd;box-shadow:0 0 35px #ff4ba326;  
  position:relative;z-index:2  
}  
.eyebrow{color:#ffd3e8;letter-spacing:3px;font-size:12px}  
.moon{font-size:32px;margin:12px}  
h1{font-size:clamp(32px,8vw,48px);color:#ffe0f0;  
  text-shadow:0 0 16px #ff69b4;margin:10px}  
.recipient{color:#ffe4a3;font-size:18px;font-weight:bold}  
.intro{color:#ead8e8;line-height:1.7}  
.envelope-wrap{perspective:900px;margin:24px auto;width:min(100%,290px)}  
.envelope{position:relative;width:100%;height:176px;border:0;  
  background:transparent;cursor:pointer}  
.env-back{position:absolute;inset:18px 8px 0;  
  background:#a52f70;border-radius:9px}  
.letter{  
  position:absolute;left:16px;right:16px;bottom:8px;height:128px;  
  padding:12px;background:linear-gradient(145deg,#fff4fa,#ffd7e9);  
  color:#6f2450;border-radius:7px;display:flex;  
  flex-direction:column;justify-content:center;align-items:center;  
  z-index:2;transition:transform .85s  
}  
.letter span{font-size:13px;margin-top:8px}  
.env-front{  
  position:absolute;inset:18px 8px 0;z-index:3;  
  background:linear-gradient(145deg,#e95a9d,#a72d70);  
  clip-path:polygon(0 0,50% 58%,100% 0,100% 100%,0 100%)  
}  
.env-flap{  
  position:absolute;top:18px;left:8px;right:8px;height:98px;  
  z-index:4;background:#ff9ecb;  
  clip-path:polygon(0 0,100% 0,50% 100%);  
  transform-origin:top;transition:transform .7s  
}  
.seal{  
  position:absolute;z-index:5;top:76px;left:50%;  
  transform:translateX(-50%);width:38px;height:38px;  
  display:grid;place-items:center;border-radius:50%;  
  background:#ffe9a9;color:#8c315a;font-size:22px  
}  
.envelope.open .env-flap{transform:rotateX(180deg);z-index:1}  
.envelope.open .letter{transform:translateY(-78px)}  
.envelope.open .seal{opacity:0}  
.tap-note{color:#f7bddb;font-size:13px}  
.wish{  
  max-height:0;opacity:0;overflow:hidden;  
  transform:translateY(8px);color:#fff0f8;  
  line-height:1.8;transition:all .8s  
}  
.wish.show{max-height:220px;opacity:1;transform:translateY(0);margin:18px 0}  
.highlight{color:#ffd6a1;font-weight:bold}  
.btn{  
  border:1px solid #754263;border-radius:999px;padding:12px 20px;  
  color:white;background:linear-gradient(110deg,#e94e9a,#a948bd);  
  font-size:15px;cursor:pointer;margin-top:15px  
}  
.footer{color:#bfaac7;font-size:12px;margin-top:20px}  
#effects{position:fixed;inset:0;overflow:hidden;pointer-events:none}  
.particle{position:absolute;bottom:-40px;animation:rise linear forwards}  
.petal{position:absolute;top:-35px;animation:fall linear forwards}  
@keyframes rise{  
  0%{transform:translateY(0) scale(.6);opacity:0}  
  12%{opacity:.9}  
  100%{transform:translateY(-110vh) scale(1.2) rotate(35deg);opacity:0}  
}  
@keyframes fall{  
  0%{transform:translateY(-30px) rotate(0);opacity:0}  
  10%{opacity:.9}  
  100%{transform:translateY(110vh) rotate(540deg);opacity:0}  
}  
</style>  
</head>  
<body>  
<div id="effects"></div>  <main class="card">  
  <div class="eyebrow">ĐÔI LỜI GỬI ĐẾN NGƯỜI ĐẸP</div>  
  <div class="moon">🌙 ✨</div>  
  <h1>Chúc mừng<br>20/10</h1>  
  <p class="recipient">Nguyễn Thị Yến Nhi 💗</p>  
  <p class="intro">Cục cức màu hồng, gửi đến chị iuuuuu thật nhiều điều dịu dàng trong ngày đặc biệt này.</p>    <div class="envelope-wrap">  
    <button class="envelope" id="envelope" aria-label="Mở phong thư">  
      <div class="env-back"></div>  
      <div class="letter">  
        <strong>Gửi Yến Nhi 💌</strong>  
      </div>  
      <div class="env-front"></div>  
      <div class="env-flap"></div>  
      <div class="seal">♥</div>  
    </button>  
  </div>    <p class="wish" id="wish">  
     Chúc chị một ngày 20/10 thật vui vẻ và hạnh phúc nhé! 🌷 Mong rằng những điều tốt đẹp nhất sẽ luôn đến với chị, nụ cười sẽ luôn nở trên môi và những muộn phiền sẽ dần nhường chỗ cho niềm vui. Chúc chị luôn tự tin, bình an, gặp được thật nhiều người tử tế và nhận được thật nhiều yêu thương. Mong rằng không chỉ hôm nay mà cả những ngày bình thường khác,chị vẫn luôn là một người đặc biệt và xứng đáng với những điều tuyệt vời nhất. 💗  
    <br><span class="highlight">Mong mọi điều tốt đẹp sẽ luôn ở bên bạn. 🌷</span>  
  </p>  <button class="btn" id="openBtn">💌 Mở lời chúc</button>

  <div class="footer">Made with love </div>  
  <div class="footer">Mãiii iuuuu💗</div>  
</main>  
<script>  
const envelope=document.getElementById("envelope");  
const wish=document.getElementById("wish");  
const tapNote=document.getElementById("tapNote");  
const openBtn=document.getElementById("openBtn");  
const effects=document.getElementById("effects");  
function openLetter(){  
  const opened=envelope.classList.toggle("open");  
  wish.classList.toggle("show",opened);  
  tapNote.textContent=opened  
    ?"Một lời chúc dành riêng cho bạn 💖"  
    :"Chạm vào phong thư để mở lời chúc";  
  openBtn.textContent=opened?"💌 Gấp phong thư":"💌 Mở lời chúc";  
  if(opened)burstHearts(16);  
}  
envelope.addEventListener("click",openLetter);  
openBtn.addEventListener("click",openLetter);  
function makeHeart(){  
  const el=document.createElement("span");  
  el.className="particle";  
  el.textContent=["♥","♡","💗","✦"][Math.floor(Math.random()*4)];  
  el.style.left=Math.random()*100+"%";  
  el.style.fontSize=(14+Math.random()*20)+"px";  
  el.style.color=["#ff7eb6","#ffc5e0","#ffe6a6","#e6b8ff"][Math.floor(Math.random()*4)];  
  el.style.animationDuration=(5+Math.random()*5)+"s";  
  effects.appendChild(el);  
  setTimeout(()=>el.remove(),10500);  
}  
function burstHearts(n=8){  
  for(let i=0;i<n;i++)setTimeout(makeHeart,i*100);  
}  
function makePetal(){  
  const el=document.createElement("span");  
  el.className="petal";  
  el.textContent=["🌸","🌺","✿","❀"][Math.floor(Math.random()*4)];  
  el.style.left=Math.random()*100+"%";  
  el.style.fontSize=(13+Math.random()*13)+"px";  
  el.style.animationDuration=(7+Math.random()*7)+"s";  
  effects.appendChild(el);  
  setTimeout(()=>el.remove(),15000);  
}  
for(let i=0;i<12;i++)setTimeout(makePetal,i*500);  
setInterval(makePetal,1100);  
setInterval(makeHeart,1500);  // Nhạc nền tự phát sau lần chạm đầu tiên.
// Android thường chặn âm thanh khi chưa có tương tác.
let audioCtx=null,masterGain=null,musicTimer=null,noteIndex=0;
const melody=[523.25,659.25,783.99,659.25,587.33,698.46,
880,698.46,523.25,659.25,783.99,1046.5];
function playNote(){
if(!audioCtx||!masterGain)return;
const now=audioCtx.currentTime;
const osc=audioCtx.createOscillator();
const gain=audioCtx.createGain();
osc.type="sine";
osc.frequency.value=melody[noteIndex%melody.length];
gain.gain.setValueAtTime(0.0001,now);
gain.gain.exponentialRampToValueAtTime(0.045,now+0.04);
gain.gain.exponentialRampToValueAtTime(0.0001,now+0.48);
osc.connect(gain);
gain.connect(masterGain);
osc.start(now);
osc.stop(now+0.5);
noteIndex++;
}
async function startMusicOnce(){
if(musicTimer)return;
try{
const AudioContextClass=window.AudioContext||window.webkitAudioContext;
if(!AudioContextClass)return;
audioCtx=audioCtx||new AudioContextClass();
await audioCtx.resume();
masterGain=masterGain||audioCtx.createGain();
masterGain.gain.value=0.45;
masterGain.connect(audioCtx.destination);
playNote();
musicTimer=setInterval(playNote,520);
}catch(e){}
}
document.addEventListener("pointerdown",startMusicOnce,{once:true});
</script>

</body>  
</html>  