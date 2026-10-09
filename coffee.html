<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Кава UA — Демо-лендінг · WebUa</title>
<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:Georgia,serif;}
  html{scroll-behavior:smooth;}
  body{background:#1a0f08;color:#f5e6d3;line-height:1.6;overflow-x:hidden;}

  /* ФОН */
  .bg-orb{position:fixed;border-radius:50%;filter:blur(100px);opacity:0.4;z-index:-1;pointer-events:none;}
  .bg-orb.o1{width:500px;height:500px;background:#d4a15a;top:-150px;left:-150px;animation:float 14s ease-in-out infinite;}
  .bg-orb.o2{width:400px;height:400px;background:#6b3f1d;bottom:-150px;right:-150px;animation:float 14s ease-in-out infinite reverse;}
  @keyframes float{0%,100%{transform:translate(0,0);}50%{transform:translate(60px,-60px);}}

  .particles{position:fixed;inset:0;z-index:-1;pointer-events:none;overflow:hidden;}
  .particle{
    position:absolute;width:3px;height:3px;border-radius:50%;
    background:#d4a15a;opacity:0.5;
    animation:rise linear infinite;
    box-shadow:0 0 8px #d4a15a;
  }
  @keyframes rise{
    0%{transform:translateY(100vh) scale(0);opacity:0;}
    10%{opacity:1;}
    90%{opacity:1;}
    100%{transform:translateY(-100px) scale(1.5);opacity:0;}
  }

  /* HERO */
  header{padding:120px 30px;text-align:center;background:linear-gradient(135deg,#2a1810,#4a2518,#6b3f1d);position:relative;overflow:hidden;}
  header::before{content:"";position:absolute;inset:0;background:radial-gradient(circle at 30% 50%,rgba(212,161,90,0.3),transparent 60%);animation:pulse 6s ease-in-out infinite;}
  @keyframes pulse{0%,100%{opacity:0.6;}50%{opacity:1;}}

  h1{font-size:clamp(2.5rem,6vw,4.5rem);color:#d4a15a;margin-bottom:16px;position:relative;animation:fadeUp 1.1s both;letter-spacing:-0.02em;text-shadow:0 0 30px rgba(212,161,90,0.5);}
  header p{opacity:0.9;font-size:1.25rem;position:relative;animation:fadeUp 1.1s .3s both;}

  .cta{
    display:inline-block;margin-top:36px;padding:16px 38px;
    background:#d4a15a;color:#1a0f08;text-decoration:none;border-radius:10px;font-weight:700;
    position:relative;animation:fadeUp 1.1s .5s both, pulseCta 2.5s ease-in-out infinite 2s;
    transition:transform .3s,box-shadow .3s;
  }
  @keyframes pulseCta{
    0%,100%{box-shadow:0 0 0 0 rgba(212,161,90,0.5);}
    50%{box-shadow:0 0 0 20px rgba(212,161,90,0);}
  }
  .cta:hover{transform:translateY(-4px);box-shadow:0 15px 30px rgba(212,161,90,0.5);}

  @keyframes fadeUp{from{opacity:0;transform:translateY(40px);}to{opacity:1;transform:translateY(0);}}

  /* СЕКЦИИ */
  section{padding:80px 30px;max-width:1000px;margin:0 auto;position:relative;z-index:1;}
  h2{font-size:clamp(1.8rem,4vw,2.6rem);color:#d4a15a;margin-bottom:16px;text-align:center;}
  .sub{text-align:center;opacity:0.7;margin-bottom:44px;}

  /* REVEAL */
  .reveal{opacity:0;transform:translateY(60px);transition:opacity 1s cubic-bezier(.2,.8,.2,1),transform 1s cubic-bezier(.2,.8,.2,1);}
  .reveal.visible{opacity:1;transform:translateY(0);}
  .reveal.d1{transition-delay:.1s;}
  .reveal.d2{transition-delay:.2s;}
  .reveal.d3{transition-delay:.3s;}

  /* ПЕРЕВАГИ */
  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:22px;}
  .card{background:rgba(212,161,90,0.08);border:1px solid rgba(212,161,90,0.2);border-radius:16px;padding:28px;text-align:center;transition:transform .4s cubic-bezier(.2,.8,.2,1),background .35s,box-shadow .35s;}
  .card:hover{transform:translateY(-10px) scale(1.03);background:rgba(212,161,90,0.15);box-shadow:0 20px 40px rgba(212,161,90,0.2);}
  .card .ico{font-size:2.8rem;margin-bottom:14px;display:inline-block;transition:transform .4s;}
  .card:hover .ico{transform:scale(1.2) rotate(-10deg);}
  .card h3{margin-bottom:8px;color:#d4a15a;font-size:1.15rem;}
  .card p{opacity:0.75;font-size:0.95rem;}

  /* МЕНЮ */
  .menu{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px;margin-top:20px;}
  .menu-item{display:flex;justify-content:space-between;padding:18px 22px;background:rgba(212,161,90,0.06);border:1px solid rgba(212,161,90,0.15);border-radius:12px;transition:transform .35s,background .35s,border-color .35s;font-size:1.05rem;}
  .menu-item:hover{transform:translateX(8px);background:rgba(212,161,90,0.12);border-color:rgba(212,161,90,0.4);}
  .menu-item span:last-child{color:#d4a15a;font-weight:700;}

  /* ГАЛЕРЕЯ */
  .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:20px;}
  .gallery div{aspect-ratio:1;background:linear-gradient(135deg,#4a2518,#6b3f1d);border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:2.4rem;transition:transform .4s cubic-bezier(.2,.8,.2,1),box-shadow .35s;cursor:pointer;}
  .gallery div:hover{transform:scale(1.08) rotate(3deg);box-shadow:0 15px 30px rgba(212,161,90,0.3);}

  /* МАРКИ */
  .marquee{overflow:hidden;white-space:nowrap;padding:26px 0;border-top:1px solid rgba(212,161,90,0.2);border-bottom:1px solid rgba(212,161,90,0.2);margin:40px 0;}
  .marquee-track{display:inline-block;animation:scroll 30s linear infinite;font-size:1.3rem;font-weight:700;letter-spacing:0.1em;color:rgba(212,161,90,0.5);}
  .marquee-track span{margin:0 26px;}
  @keyframes scroll{to{transform:translateX(-50%);}}

  footer{padding:60px 30px;text-align:center;border-top:1px solid rgba(212,161,90,0.2);opacity:0.7;}
  footer a{color:#d4a15a;text-decoration:none;}
</style>
</head>
<body>

<div class="bg-orb o1"></div>
<div class="bg-orb o2"></div>
<div class="particles" id="particles"></div>

<header>
  <h1>☕ Кава UA</h1>
  <p>Затишок, аромат і смак у кожній чашці</p>
  <a href="#" class="cta">Забронювати столик</a>
</header>

<div class="marquee">
  <div class="marquee-track">
    <span>☕ СВІЖА КАВА</span><span>🥐 ДОМАШНЯ ВИПІЧКА</span><span>✨ ЗАТИШОК</span><span>🎵 LIVE МУЗИКА</span>
    <span>☕ СВІЖА КАВА</span><span>🥐 ДОМАШНЯ ВИПІЧКА</span><span>✨ ЗАТИШОК</span><span>🎵 LIVE МУЗИКА</span>
  </div>
</div>

<section>
  <h2 class="reveal">Чому ми</h2>
  <p class="sub reveal d1">Три причини завітати саме до нас</p>
  <div class="grid">
    <div class="card reveal d1"><div class="ico">🌱</div><h3>Свіжообсмажені зерна</h3><p>Оновлюємо запаси кожного дня</p></div>
    <div class="card reveal d2"><div class="ico">👨‍🍳</div><h3>Досвідчені баристи</h3><p>Понад 5 років практики</p></div>
    <div class="card reveal d3"><div class="ico">🎨</div><h3>Затишна атмосфера</h3><p>Ідеально для роботи й зустрічей</p></div>
  </div>
</section>

<section>
  <h2 class="reveal">Наше меню</h2>
  <p class="sub reveal d1">Тільки свіжі напої та десерти</p>
  <div class="menu">
    <div class="menu-item reveal d1"><span>Еспресо</span><span>45 грн</span></div>
    <div class="menu-item reveal d1"><span>Американо</span><span>55 грн</span></div>
    <div class="menu-item reveal d1"><span>Капучино</span><span>65 грн</span></div>
    <div class="menu-item reveal d2"><span>Лате</span><span>70 грн</span></div>
    <div class="menu-item reveal d2"><span>Раф</span><span>80 грн</span></div>
    <div class="menu-item reveal d2"><span>Чізкейк</span><span>90 грн</span></div>
    <div class="menu-item reveal d3"><span>Круасан</span><span>60 грн</span></div>
    <div class="menu-item reveal d3"><span>Макарон</span><span>50 грн</span></div>
  </div>
</section>

<section>
  <h2 class="reveal">Галерея</h2>
  <p class="sub reveal d1">Атмосфера нашого закладу</p>
  <div class="gallery reveal d2">
    <div>☕</div><div>🍰</div><div>🥐</div>
  </div>
</section>

<footer>
  © Кава UA · вул. Центральна 1 · 099 123 45 67 · <a href="index.html">← Назад до WebUa</a>
</footer>

<script>
(function(){
  var wrap = document.getElementById('particles');
  for(var i=0;i<30;i++){
    var p = document.createElement('div');
    p.className = 'particle';
    p.style.left = Math.random()*100 + '%';
    p.style.animationDuration = (8 + Math.random()*10) + 's';
    p.style.animationDelay = (Math.random()*8) + 's';
    var size = (1 + Math.random()*3);
    p.style.width = size + 'px';
    p.style.height = size + 'px';
    wrap.appendChild(p);
  }
})();

var observer = new IntersectionObserver(function(entries){
  entries.forEach(function(entry){
    if(entry.isIntersecting){
      entry.target.classList.add('visible');
      observer.unobserve(entry.target);
    }
  });
}, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });
document.querySelectorAll('.reveal').forEach(function(el){ observer.observe(el); });
</script>
</body>
</html>
