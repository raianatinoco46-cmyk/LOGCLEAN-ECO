# LOGCLEAN-ECO
Empresa de limpeza sulstentavel
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LOGCLEAN ECO</title>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f4f4f4;
}
header {
    background: #1e7f3f;
    color: white;
    padding: 30px;
    text-align: center;
}
.logo {
    max-width: 200px;
}
section {
    padding: 40px;
    text-align: center;
}
.produtos {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}
.card {
    background: white;
    border-radius: 10px;
    padding: 20px;
    width: 300px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
.card img {
    width: 100%;
    border-radius: 10px;
}
button {
    background: #1e7f3f;
    color: white;
    border: none;
    padding: 12px;
    margin-top: 10px;
    border-radius: 5px;
    cursor: pointer;
    width: 100%;
}
button:hover {
    background: #145c2d;
}
.qr img {
    margin-top: 20px;
}
footer {
    background: #333;
    color: white;
    padding: 20px;
    text-align: center;
}
</style>
</head>

<body>

<header>
    <!-- COLOQUE AQUI O LOGO -->
    <img src="logo.png" class="logo">
    <h1>LOGCLEAN ECO</h1>
    <p>Logística Inteligente, Limpeza Sustentável</p>
</header>

<section>
    <h2>🌱 Nossos Produtos</h2>

    <div class="produtos">

        <div class="card">
            <!-- FOTO DO SABÃO LÍQUIDO -->
            <img src="sabao-liquido.jpg">
            <h3>Sabão Líquido</h3>
            <p>Limpeza eficiente com responsabilidade</p>
            <a href="https://wa.me/5592993059422">
                <button>Comprar com Raiana</button>
            </a>
        </div>

        <div class="card">
            <!-- FOTO DO SABÃO EM BARRA -->
            <img src="sabao-barra.jpg">
            <h3>Sabão em Barra</h3>
            <p>Produto sustentável e econômico</p>
            <a href="https://wa.me/5592999826583">
                <button>Comprar com Francisca</button>
            </a>
        </div>

    </div>
</section>

<section style="background:#e8f5e9">
    <h2>♻️ Doação de Óleo</h2>
    <p>Ajude o meio ambiente! Doe seu óleo usado.</p>

    <a href="https://wa.me/5592985337975">
        <button>Falar com Airton</button>
    </a>
</section>

<section>
    <h2>📲 QR Code</h2>
    <p>Escaneie para entrar em contato</p>

    <div class="qr">
        <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://wa.me/5592993059422">
    </div>
</section>

<section>
    <h2>📞 Contatos</h2>
    <p><strong>Raiana:</strong> 92 99305-9422</p>
    <p><strong>Francisca:</strong> 92 99982-6583</p>
    <p><strong>Doação (Airton):</strong> 92 98533-7975</p>
</section>

<footer>
    <p>© 2026 LOGCLEAN ECO</p>
</footer>

</body>
</html>
