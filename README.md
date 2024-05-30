# receita-de-bolo
Exercício HTML de uma receita de bolo
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bolo de Chocolate</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <header>
        <h1>Bolo de Chocolate</h1>
        <p>O bolo mais amado pelos brasileiros numa receita simples e rápida</p>
    </header>
    <section class="sessaoFoto">
        <img src="bolo.jpg" alt="Bolo de Chocolate">
    </section>
    <section class="sessaoIngredientes">
        <h2>Ingredientes</h2>
        <ol>
            <li>2 xícaras de farinha de trigo</li>
            <li>1 e 1/2 xícara de açúcar</li>
            <li>1 xícara de chocolate em pó</li>
            <li>1 xícara de leite</li>
            <li>1/2 xícara de óleo</li>
            <li>3 ovos</li>
            <li>1 colher de sopa de fermento em pó</li>
        </ol>
    </section>
    <section class="sessaoPreparo">
        <h3>Modo de Preparo</h3>
        <ol>
            <li>Preaqueça o forno a 180°C.</li>
            <li>Em uma tigela, misture a farinha, o açúcar e o chocolate em pó.</li>
            <li>Adicione o leite, o óleo e os ovos e misture bem até obter uma massa homogênea.</li>
            <li>Acrescente o fermento em pó e misture delicadamente.</li>
            <li>Despeje a massa em uma forma untada e enfarinhada.</li>
            <li>Leve ao forno preaquecido por aproximadamente 35-40 minutos, ou até que um palito inserido no centro do bolo saia limpo.</li>
            <li>Retire do forno, deixe esfriar um pouco antes de desenformar e servir.</li>
        </ol>
    </section>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    background-color: #fff; /* Fundo branco claro */
    color: #333;
    text-align: center;
    margin: 0;
    padding: 0;
}

header {
    background-color: #d5d5d5;
    padding: 20px;
}

h1 {
    margin: 0;
    color: #444;
    font-weight: bold; /* Negrito para o título */
}

.sessaoFoto img {
    width: 300px;
    height: auto;
    border: 1px solid #333; /* Borda sólida de 1px */
    margin-top: 20px;
}

.sessaoIngredientes,
.sessaoPreparo {
    border: 1px solid #333; /* Borda sólida de 1px */
    padding: 10px;
    margin-top: 20px;
}


