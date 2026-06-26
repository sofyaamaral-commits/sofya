<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agro Forte, Futuro Sustentável</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<h1>🌱 Agro Forte, Futuro Sustentável</h1>
<p>Produzir com responsabilidade é garantir o amanhã.</p>
<a href="#sobre" class="botao">Saiba Mais</a>
</header>

<nav>
<a href="#sobre">Sobre</a>
<a href="#tecnologia">Tecnologia</a>
<a href="#sustentabilidade">Sustentabilidade</a>
<a href="#contato">Contato</a>
</nav>

<section id="sobre">
<h2>🌾 Sobre</h2>
<p>
O agronegócio é essencial para alimentar o mundo e movimentar a economia.
Com práticas sustentáveis é possível aumentar a produção preservando a natureza.
</p>
<button onclick="mensagem()">Clique Aqui</button>
</section>

<section id="tecnologia">
<h2>🚜 Tecnologia no Campo</h2>
<p>
Máquinas modernas, drones e inteligência artificial ajudam os produtores
a reduzir desperdícios e aumentar a produtividade.
</p>
</section>

<section id="sustentabilidade">
<h2>🌳 Sustentabilidade</h2>
<p>
Preservar rios, matas e o solo garante um futuro melhor para as próximas gerações.
</p>
</section>

<section id="contato">
<h2>📩 Contato</h2>
<form>
<input type="text" placeholder="Nome" required>
<input type="email" placeholder="Email" required>
<textarea placeholder="Mensagem"></textarea>
<button type="submit">Enviar</button>
</form>
</section>

<footer>
<p>© 2026 - Agro Forte, Futuro Sustentável</p>
</footer>

<script src="script.js"></script>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#eef7e7;
color:#333;
}

header{
background:linear-gradient(green,#3cb371);
color:white;
padding:80px 20px;
text-align:center;
}

header h1{
font-size:45px;
}

header p{
margin:20px 0;
font-size:20px;
}

.botao{
background:white;
color:green;
padding:12px 25px;
text-decoration:none;
border-radius:30px;
font-weight:bold;
}

nav{
display:flex;
justify-content:center;
background:#2e7d32;
}

nav a{
color:white;
padding:15px;
text-decoration:none;
}

nav a:hover{
background:#1b5e20;
}

section{
padding:50px;
text-align:center;
}

section h2{
margin-bottom:20px;
color:green;
}

button{
background:green;
color:white;
padding:12px 20px;
border:none;
border-radius:20px;
cursor:pointer;
margin-top:15px;
}

button:hover{
background:#1b5e20;
}

form{
display:flex;
flex-direction:column;
max-width:500px;
margin:auto;
}

input, textarea{
margin:10px;
padding:12px;
}

footer{
background:#2e7d32;
color:white;
text-align:center;
padding:20px;
margin-top:30px;
}
function mensagem(){
alert("🌱 O futuro sustentável começa com atitudes conscientes no campo!");
}

</body>
</html>
