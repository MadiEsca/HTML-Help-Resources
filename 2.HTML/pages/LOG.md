# Resumo
Esse é o primeiro arquivo `LOG.md`, e nesse momento falaremos sobre:
1. Tags base de qualquer projeto HTML
2. Estrutura de um projeto HTML

# Estrutura de um projeto HTML
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Página de demonstração"> 
    <meta name="keywords" content="html, css, aprendendo, js"> 
    <link rel="stylesheet" href="../styles/style.css">
    <title>Document</title>
</head>
<body>

</body>
</html>
```

## Estrutura do nosso projeto
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8"> <!--Define a codificação do site-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!--Define como a página será carregada em cada dispositivo | Define o tamanho da página como o tamanho da tela do próprio dispositivo que a carrega-->
    <meta name="description" content="Página de demonstração"> <!--Descrição da página | Utilizado para otimizar o SEO do site-->
    <meta name="keywords" content="html, css, aprendendo, js"> <!--Palavras chave da página | Utilizado para otimizar o SEO do site-->
    <link rel="stylesheet" href="../styles/style.css"> <!-- Indica qual o arquivo CSS que rege essa página -->
    <title>MoX</title> <!-- Indica o título da página -->
</head>
<body>
    <header>
        <!-- Seção inicial do nosso site, onde 
        colocamos as tags e informações que devem
        ficar no topo, como o menu de navegação, 
        logo, menus suspensos, etc
        -->
        <nav> 
            <a href="#">home</a>
            <a href="#">interna01</a>
            <a href="#">interna02</a>
        </nav>
    </header>
    <main>
        <!-- Seção principal do nosso site, onde 
        colocamos as tags que estão no menu
        "principal"
        -->
    </main>
    <footer>
        <!-- Seção do rodapé do nosso site, as tags e informações
        que ficam na parte de baixo do nosso site, como o 
        copright, autor, contato, informações instituiconais, etc
        -->
    </footer>
</body>
</html>
```

### Conteúdo restante dentro do código
[Código e anotações](/2.HTML/pages/index.html)