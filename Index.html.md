<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
<meta charset="UTF-8">  
<title>Para você, meu amor 💛</title>  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
  
<style>  
body{margin:0;font-family:-apple-system,BlinkMacSystemFont,sans-serif;  
background:#0f0f0f;color:#f2f2f2}  
section{max-width:900px;margin:auto;padding:40px 20px}  
h1,h2{text-align:center}  
p{text-align:center;line-height:1.7;font-size:1.05rem;color:#ddd}  
.gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));  
gap:14px;margin-top:30px}  
.gallery img{width:100%;border-radius:16px}  
.divider{height:1px;background:#333;margin:60px 0}  
.final img{width:260px;display:block;margin:30px auto}  
button{padding:16px 38px;border:none;border-radius:40px;  
background:#c9a24d;font-size:1.1rem}  
</style>  
</head>  
  
<body>  
  
<section>  
<h1>Para você, minha loirinha 💛</h1>  
<p>  
Nossa história começou em 24/08/25.<br>  
Não foi planejado.<br>  
Só aconteceu.<br><br>  
E quando eu vi… já era você.  
</p>  
</section>  
  
<div class="divider"></div>  
  
<section>  
<p>Aqui estão todos os nossos momentos.</p>  
<div class="gallery" id="galeria"></div>  
</section>  
  
<div class="divider"></div>  
  
<section class="final">  
<img src="img/alianca.jpg">  
<p>  
Eu não quero algo passageiro.<br>  
Eu quero você comigo, de verdade.  
</p>  
<h2>Você aceita se casar comigo? 💍</h2>  
<button onclick="alert('Então agora é nós! 💛')">Sim, eu aceito</button>  
</section>  
  
<script>  
const total=50;  
const g=document.getElementById("galeria");  
for(let i=1;i<=total;i++){  
 let img=document.createElement("img");  
 img.src="img/img"+i+".jpg";  
 img.onerror=()=>img.remove();  
 g.appendChild(img);  
}  
</script>  
  
</body>  
</html>  
