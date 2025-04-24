<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haja Álcool - O seu site de futebol</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        
        header {
            background-color: #006341;
            color: white;
            padding: 20px;
            text-align: center;
        }
        
        nav {
            background-color: #003366;
            padding: 10px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-around;
        }
        
        nav li {
            display: inline;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
        }
        
        nav a:hover {
            background-color: #006341;
            border-radius: 5px;
        }
        
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        
        .destaque {
            display: flex;
            margin-bottom: 30px;
        }
        
        .destaque img {
            width: 60%;
            border-radius: 8px;
        }
        
        .destaque-texto {
            padding: 20px;
            width: 40%;
        }
        
        .noticias {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        
        .noticia {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .noticia img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        
        .noticia-conteudo {
            padding: 15px;
        }
        
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
        
        @media (max-width: 768px) {
            .destaque {
                flex-direction: column;
            }
            
            .destaque img, .destaque-texto {
                width: 100%;
            }
            
            .noticias {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Haja Álcool Futebol</h1>
        <p>Tudo sobre o mundo da bola com a irreverência que você merece</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Notícias</a></li>
            <li><a href="#">Campeonatos</a></li>
            <li><a href="#">Times</a></li>
            <li><a href="#">Jogadores</a></li>
            <li><a href="#">Contato</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <section class="destaque">
            <img src="https://images.unsplash.com/photo-1574629810360-7efbbe195018?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Jogadores comemorando gol">
            <div class="destaque-texto">
                <h2>Flamengo vence clássico com gol nos acréscimos</h2>
                <p>Em partida emocionante, o Flamengo venceu o rival por 2x1 com gol de Gabigol aos 47 do segundo tempo. A torcida enlouqueceu e a festa foi grande no Maracanã.</p>
                <p>Confira os melhores lances e a análise completa do jogo que movimentou as redes sociais.</p>
                <button>Leia mais</button>
            </div>
        </section>
        
        <h2>Últimas Notícias</h2>
        <section class="noticias">
            <article class="noticia">
                <img src="https://images.unsplash.com/photo-1540747913346-19e32dc3e97e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Técnico dando instruções">
                <div class="noticia-conteudo">
                    <h3>Técnico é demitido após sequência ruim</h3>
                    <p>Após quatro derrotas consecutivas, o clube anunciou a saída do treinador. Quem será o substituto?</p>
                </div>
            </article>
            
            <article class="noticia">
                <img src="https://images.unsplash.com/photo-1522778119026-d647f0596c20?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Jogador se preparando para cobrar falta">
                <div class="noticia-conteudo">
                    <h3>Artilheiro do campeonato se machuca</h3>
                    <p>O atacante sofreu lesão no treino e deve ficar fora dos gramados por pelo menos um mês.</p>
                </div>
            </article>
            
            <article class="noticia">
                <img src="https://images.unsplash.com/photo-1579952363873-27f3bade9f55?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Torcida comemorando">
                <div class="noticia-conteudo">
                    <h3>Time surpreende e avança na copa</h3>
                    <p>O underdog do campeonato eliminou o favorito e agora sonha com o título inédito.</p>
                </div>
            </article>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2023 Haja Álcool Futebol - Todos os direitos reservados</p>
        <p>Este site é apenas para diversão e não deve ser levado a sério (mas o futebol sim!)</p>
    </footer>
</body>
</html>