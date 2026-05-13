# anime-rpg
index.html
style.css
script.js
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ascensão Traída</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="overlay"></div>

    <main class="menu">

        <h1 class="titulo">ASCENSÃO TRAÍDA</h1>

        <p class="subtitulo">
            “Quando o mundo me abandonou...
            eu me tornei algo pior.”
        </p>

        <div class="botoes">

            <button onclick="jogar()">
                Jogar
            </button>

            <button onclick="config()">
                Configurações
            </button>

            <button onclick="creditos()">
                Créditos
            </button>

        </div>

    </main>

    <script src="script.js"></script>
</body>
</html>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial;
}

body{
    width: 100%;
    height: 100vh;

    background:
    linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.9)),
    url("https://images.unsplash.com/photo-1511512578047-dfb367046420?q=80&w=1920");

    background-size: cover;
    background-position: center;

    display: flex;
    justify-content: center;
    align-items: center;

    overflow: hidden;
}

.menu{
    text-align: center;
    color: white;

    animation: aparecer 2s ease;
}

.titulo{
    font-size: 70px;
    margin-bottom: 20px;

    color: crimson;

    text-shadow:
    0 0 10px crimson,
    0 0 30px crimson;
}

.subtitulo{
    font-size: 20px;
    margin-bottom: 40px;

    opacity: 0.8;
}

.botoes{
    display: flex;
    flex-direction: column;
    gap: 15px;
}

button{
    width: 250px;
    padding: 15px;

    border: none;
    border-radius: 10px;

    background: crimson;
    color: white;

    font-size: 18px;
    cursor: pointer;

    transition: 0.3s;
}

button:hover{
    transform: scale(1.05);

    background: rgb(255, 30, 75);

    box-shadow:
    0 0 15px crimson;
}

@keyframes aparecer{
    from{
        opacity: 0;
        transform: translateY(30px);
    }

    to{
        opacity: 1;
        transform: translateY(0);
    }
}
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial;
}

body{
    width: 100%;
    height: 100vh;

    background:
    linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.9)),
    url("https://images.unsplash.com/photo-1511512578047-dfb367046420?q=80&w=1920");

    background-size: cover;
    background-position: center;

    display: flex;
    justify-content: center;
    align-items: center;

    overflow: hidden;
}

.menu{
    text-align: center;
    color: white;

    animation: aparecer 2s ease;
}

.titulo{
    font-size: 70px;
    margin-bottom: 20px;

    color: crimson;

    text-shadow:
    0 0 10px crimson,
    0 0 30px crimson;
}

.subtitulo{
    font-size: 20px;
    margin-bottom: 40px;

    opacity: 0.8;
}

.botoes{
    display: flex;
    flex-direction: column;
    gap: 15px;
}

button{
    width: 250px;
    padding: 15px;

    border: none;
    border-radius: 10px;

    background: crimson;
    color: white;

    font-size: 18px;
    cursor: pointer;

    transition: 0.3s;
}

button:hover{
    transform: scale(1.05);

    background: rgb(255, 30, 75);

    box-shadow:
    0 0 15px crimson;
}

@keyframes aparecer{
    from{
        opacity: 0;
        transform: translateY(30px);
    }

    to{
        opacity: 1;
        transform: translateY(0);
    }
}
function jogar(){
    alert("O jogo vai começar...");
}

function config(){
    alert("Menu de configurações em breve.");
}

function creditos(){
    alert("Jogo criado por Erick.");
}
