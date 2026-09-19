<html lang="da">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>...</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{--paper:#f7f5ef;--ink:#111}
body{
  font-family:Arial,Helvetica,sans-serif;
  background:var(--paper);
  color:var(--ink);
}
.wrap{max-width:1100px;margin:auto;padding:28px}
header{display:flex;justify-content:space-between;align-items:center;padding-bottom:18px;border-bottom:1px solid #111}
.logo{border:1.5px solid #111;padding:8px 18px;font-size:28px;letter-spacing:-1px}
nav a{margin-left:24px;text-decoration:none;color:#111;text-transform:uppercase;font-size:12px;letter-spacing:.15em}
.hero{display:grid;grid-template-columns:1.1fr .9fr;gap:56px;padding:72px 0}
h1{font-size:74px;line-height:.92;font-weight:500;letter-spacing:-3px}
.sub{margin:22px 0 36px;max-width:470px;font-size:18px;line-height:1.7}
.btn{display:inline-block;border:1px solid #111;padding:14px 20px;text-decoration:none;color:#111;text-transform:uppercase;font-size:12px;letter-spacing:.12em}
.label{background:white;border:1px solid #111;padding:18px}
.label img{width:100%;display:block}
section{border-top:1px solid #111;padding:80px 0}
.title{font-size:12px;text-transform:uppercase;letter-spacing:.18em;margin-bottom:16px}
h2{font-size:48px;letter-spacing:-2px;margin-bottom:30px;font-weight:500}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:50px}
.card{border:1px solid #111;padding:28px;background:white}
.card h3{font-size:15px;text-transform:uppercase;letter-spacing:.15em;margin-bottom:20px}
.card2{border:1px solid #111;padding:28px;background:white}
.card2 img{width:100%;display:block}
section{border-top:1px solid #111;padding:80px 0}
.fact{display:flex;justify-content:space-between;padding:12px 0;border-bottom:1px solid #ddd;font-size:14px}
.quote{font-size:34px;line-height:1.25;max-width:600px;letter-spacing:-1px}
footer{border-top:1px solid #111;padding:24px 0;font-size:11px;text-transform:uppercase;letter-spacing:.14em;display:flex;justify-content:space-between;flex-wrap:wrap;gap:10px}
@media(max-width:800px){
.hero,.grid{grid-template-columns:1fr}
h1{font-size:52px}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<div class="logo">EMILER</div>
<nav>
<a href="#beer">Øl</a>
<a href="#about">Om</a>
</nav>
</header>

<div class="hero">
  
<div>
<div class="title"> Øl, cider og portvin</div>
<h1>Hjemmebrygget i<br>Aarhus.</h1>
<p class="sub">
Brygget af <br>Emil Wiis Ravn og Emil Casper Rasmussen
</p>
  
<a class="btn" href="#batch01">Se batch 01 - Raspberry Sour</a><br><br>
<a class="btn" href="#batch02">Se batch 02 - Blonde Ale</a><br><br>
<a class="btn" href="#batch03">Se batch 03 - Mørk juleøl</a><br><br>
<a class="btn" href="#batch04">Se batch 04 - Engelsk Cider</a>
</div>

<div class="label">
<img src="IMG_2229.jpg" alt="EMILER Raspberry Sour etikette">
</div>

</div>

<section id="batch01">
<div class="title">Batch 01</div>
<h2>Raspberry Sour</h2>

<div class="grid">
  
<div>
<p style="font-size:17px;line-height:1.8;margin-bottom:26px">
Den første øl brygget af EMILER. En frisk, syrlig og frugtig sour,
hvor hindbær er i centrum. Tilsat laktose, for bedre fylde.
</p>
<div class="quote">
“Brygget med rigtige hindbær.”
</div>

</div>
<div class="card">
<h3>Specifikationer</h3>
<div class="fact"><span>Stil</span><strong>Sour Beer</strong></div>
<div class="fact"><span>Alkohol</span><strong>5,5 vol. %</strong></div>
<div class="fact"><span>Foreløbig bryggemængde</span><strong>110 L</strong></div>
<div class="fact"><span>Gærtype</span><strong>Philly Sour</strong></div>
<div class="fact"><span>Ingredienser</span><strong>Malt · Vand · Humle · Gær · Hindbær · Laktose</strong></div>

<div class="card2">
<img src="B1.jpg" alt="Raspberry Sour billede">
</div>

</div>

</section>

<section id="batch02">
<div class="title">Batch 02</div>
<h2>Blonde Ale</h2>

<div class="grid">
<div>
<p style="font-size:17px;line-height:1.8;margin-bottom:26px">
En belgisk inspireret hvedeøl, brygget med variationer af malt.
Frisk og sprød, med en gylden farve .
</p>

<div class="quote">
“Gylden blonde.”
</div>
</div>

<div class="card">
<h3>Specifikationer</h3>
<div class="fact"><span>Stil</span><strong>Blonde Ale</strong></div>
<div class="fact"><span>Alkohol</span><strong>5,5 vol. %</strong></div>
<div class="fact"><span>Foreløbig bryggemængde</span><strong>25 L</strong></div>
<div class="fact"><span>Gærtype</span><strong>Safale US-05</strong></div>
<div class="fact"><span>Ingredienser</span><strong>Malt · Vand · Humle · Gær</strong></div>
</div>
</div>

<div class="card">
<img src="B2.jpg" alt="Blonde Ale billede">
</div>
</div>
</section>

<section id="about">
<div class="title">OM</div>
<h2>Et lille bryggeri.</h2>
<div class="grid">
<div>
<p style="font-size:16px;line-height:1.8">
EMILER er et hobbybryggeri skabt af nysgerrighed og gode idéer.
Vi laver øl, vi selv har lyst til at drikke, og hver batch får sit eget udtryk.
</p>
</div>
<div class="label">
<img src="IMG_9098.jpg" alt="EMILER flasker">
</div>
</div>
</section>

<footer>
<span>TAK FORDI DU KIGGEDE MED</span>
<span>AARHUS 2026</span>
</footer>
</div>
</body>
</html>
