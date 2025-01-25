# Projeto

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header></header>
    <main class="center">
        <h1>Eleve seu negócio digital a outro nível<br>
            <strong>com um Front-End de qualidade!</strong>
        </h1>
        <p>Olá! Sou Lucas Mateus, desenvolvedor Front-End com especialidade em <strong>HTML, CSS e JAVASCRIPT</strong>.
            <br>
            Ajudo pequenos negócios e designers a colocarem em prática boas ideias. <br>
            Vamos conversar?
        </p>
        <div class="buttons">
            <a href="https://instagram.com/lucas_mateusbc" class="btn instagram">Instagram</a>
            <a href="https://github.com/mateusvvv" class="btn github">GitHub</a>
        </div>
        <img src="imagem.jpg" alt="Foto de Lucas na confraternização da sua empresa">
    </main>
    <footer></footer>
</body>

</html>


/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body, html { 
    height: 100%;
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
}

/* Centralização com Flexbox */
.center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    height: 100vh;
    padding: 20px;
}

/* Título e parágrafo */
h1 {
    font-size: 2.5rem;
    color: #222;
    margin-bottom: 1rem;
}

h1 strong {
    color: #0077cc; /* Destaque */
}

p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
    line-height: 1.5;
}

/* Botões */
.buttons {
    display: flex;
    gap: 10px;
    margin-bottom: 1.5rem;
}

.btn {
    text-decoration: none;
    color: #fff;
    padding: 10px 20px;
    border-radius: 8px;
    font-size: 1rem;
    font-weight: bold;
    transition: background 0.3s ease;
}

.btn.instagram {
    background-color: #E1306C;
}

.btn.instagram:hover {
    background-color: #c3225a;
}

.btn.github {
    background-color: #333;
}

.btn.github:hover {
    background-color: #555;
}

/* Imagem */
img {
    border-radius: 12px;
    width: 350px;
    height: auto;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}





