<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tropicália: O Movimento da Revolução Cultural</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <button class="accessibility-toggle-btn" aria-label="Abrir menu de acessibilidade">
        <img src="naruto-icon.png" alt="Ícone do Naruto, representando o menu de acessibilidade">
    </button>

    <div id="accessibility-menu" class="accessibility-menu" role="dialog" aria-labelledby="accessibility-menu-title" aria-hidden="true">
        <h2 id="accessibility-menu-title">Menu de Acessibilidade</h2>
        <button id="close-accessibility-menu" aria-label="Fechar menu de acessibilidade">Fechar</button>
        <ul>
            <li>
                <button id="font-size-plus" class="btn btn-dark" aria-label="Aumentar tamanho da fonte">Aumentar Fonte (A+)</button>
            </li>
            <li>
                <button id="font-size-minus" class="btn btn-dark" aria-label="Diminuir tamanho da fonte">Diminuir Fonte (A-)</button>
            </li>
            <li>
                <button id="high-contrast" class="btn btn-dark" aria-label="Modo de alto contraste">Alto Contraste</button>
            </li>
        </ul>
    </div>

    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light" aria-label="Navegação principal">
            <div class="container-fluid">
                <a class="navbar-brand" href="#" tabindex="0">Tropicália</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Alternar navegação">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#inicio" tabindex="0">Início</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#artistas" tabindex="0">Artistas</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#obras" tabindex="0">Obras</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contato" tabindex="0">Contato</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <main>
        <section id="inicio" class="py-5" role="region" aria-label="Seção de introdução ao movimento Tropicália">
            <div class="container">
                <h1 class="text-center" tabindex="0">O Que Foi a Tropicália?</h1>
                <p tabindex="0">A Tropicália foi um movimento artístico... <img src="caetano-veloso.jpg" alt="Caetano Veloso com Gilberto Gil em uma foto antiga." class="img-fluid" tabindex="0"></p>
            </div>
        </section>

        <section id="artistas" class="py-5 bg-light" role="region" aria-label="Seção de principais artistas do movimento">
            <div class="container">
                <h2 class="text-center" tabindex="0">Principais Artistas</h2>
                <div class="row">
                    <div class="col-md-4">
                        <div class="card mb-4 shadow-sm" tabindex="0">
                            <img src="gilberto-gil.jpg" alt="Gilberto Gil tocando violão." class="bd-placeholder-img card-img-top" role="img" aria-label="Imagem de Gilberto Gil">
                            <div class="card-body">
                                <h3 class="card-title">Gilberto Gil</h3>
                                <p class="card-text">Descrição sobre a contribuição de Gilberto Gil.</p>
                            </div>
                        </div>
                    </div>
                    </div>
            </div>
        </section>

        </main>

    <footer class="text-center py-4" role="contentinfo">
        <p tabindex="0">© 2025 Projeto de Acessibilidade Web. Todos os direitos reservados.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://unpkg.com/scrollreveal"></script>
    <script src="main.js"></script>
</body>
</html>
