O projeto lecionado pelo professor Marcio, na matéria de Desenvolvimento Web 1 no curso de DSM - FATEC Franca - 1ºsemestre. Foi pensando em termos nosso currículo em uma versão web page, nos colocando a por em prática os conhecimentos adquiridos em HTML e CSS.

💻 Link do site
No site foi utilizado:

HTML
CSS
Cógido-fonte:

HTML
Home Page

```
    <header class="container-cabecalho">
        <a href="index.html">
            <img src="assets/images/logo_empresa.png" alt="Logo da empresa" title="ViniciusdevCorp">
        </a>
        <h3>ViniciusdevCV</h3>
    </header>

    
    <nav class="container-navegacao">
        <a href="index.html">Quem sou</a>
        <a href="servicos.html">Nossos Serviços</a>
        <a href="contactos.html">Contatos</a>
    </nav>

    
    <section class="container-quem-somos">

        <article class="servico">
            <img src="assets/images/icon_ai.png" class="icone" alt="ViniciusdevCorp">
            <p class="servico-texto">
                Sou Vinicius de Araújo Silva especialista e desenvolvedor fullstack,
                Trabalhamos para encontrar soluções tecnologicamente inteligentes para todas as áreas empresariais.
            </p>
        </article>

        <article class="servico">
            <img src="assets/images/icon_lab.png" class="icone" alt="Laboratório moderno">
            <p class="servico-texto">
                Os nossos metodos são os mais modernos da atualidade.
            </p>
        </article>

        <article class="servico">
            <img src="assets/images/icon_computer.png" class="icone" alt="Programadores experientes">
            <p class="servico-texto">
                Programador Fullstack com proeficiência em javascript e python
            </p>
        </article>

    </section>


    
    <section class="container-servicos-contactos">

        <h1>Obtenha mais informações na área de serviços e contate-nos.</h3>

            <div class="botoes-servicos-contactos">
                <a href="servicos.html">Ver serviços</a>
                <a href="contactos.html">Contatos</a>
            </div>

    </section>

    <footer>
        ViniciusdevCorp &copy; 2024| &reg; Todos os direitos reservados.
    </footer>





</body>

</html>
    <header class="container-cabecalho">
        <a href="index.html">
            <img src="assets/images/logo_empresa.png" alt="Logo da empresa" title="ViniciusdevCorp">
        </a>
        <h3>ViniciusdevCV</h3>
    </header>

    
    <nav class="container-navegacao">
        <a href="index.html">Quem sou</a>
        <a href="servicos.html">Nossos Serviços</a>
        <a href="contactos.html">Contatos</a>
    </nav>

    
    <section class="container-quem-somos">

        <article class="servico">
            <img src="assets/images/icon_ai.png" class="icone" alt="ViniciusdevCorp">
            <p class="servico-texto">
                Sou Vinicius de Araújo Silva especialista e desenvolvedor fullstack,
                Trabalhamos para encontrar soluções tecnologicamente inteligentes para todas as áreas empresariais.
            </p>
        </article>

        <article class="servico">
            <img src="assets/images/icon_lab.png" class="icone" alt="Laboratório moderno">
            <p class="servico-texto">
                Os nossos metodos são os mais modernos da atualidade.
            </p>
        </article>

        <article class="servico">
            <img src="assets/images/icon_computer.png" class="icone" alt="Programadores experientes">
            <p class="servico-texto">
                Programador Fullstack com proeficiência em javascript e python
            </p>
        </article>

    </section>


    
    <section class="container-servicos-contactos">

        <h1>Obtenha mais informações na área de serviços e contate-nos.</h3>

            <div class="botoes-servicos-contactos">
                <a href="servicos.html">Ver serviços</a>
                <a href="contactos.html">Contatos</a>
            </div>

    </section>

    <footer>
        ViniciusdevCorp &copy; 2024| &reg; Todos os direitos reservados.
    </footer>





</body>

</html>

Pagina de Contatos
<!DOCTYPE html>
<html lang="pt">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ViniciusdevCorp</title>

    
    <link rel="stylesheet" href="assets/css/estilos.css">

    
    <link rel="shortcut icon" href="assets/images/logo_empresa.png" type="image/png">

</head>

<body>

    
    <header class="container-cabecalho">
        <a href="index.html">
            <img src="assets/images/logo_empresa.png" alt="Logo da empresa" title="ViniciusdevCorp">
        </a>
        <h3>ViniciusdevCV</h3>
    </header>

   
    <nav class="container-navegacao">
        <a href="index.html">Quem sou</a>
        <a href="servicos.html">Nossos Serviços</a>
        <a href="contactos.html">Contatos</a>
    </nav>

   
    <section class="container-contactos">
        
        <h1 class="text-center">Contate-nos</h1>
        <h3 class="text-center">Estou disponível 24/7 para o esclarecer</h3>

        <article class="text-center">
            <img src="assets/images/icon_phone.png" alt="Telefone">
            <a href="tel:16992747927" class="contactos">16992747927</a>
            <small>Entre as 09:00h e as 19:00h</small>
        </article>

        <article class="text-center margin-top-40">
            <img src="assets/images/icon_email.png" alt="Email">
            <a href="mailto:viniciuswkaraujo@gmail.com" class="contactos">Viniciuswkaraujo@gmail.com</a>
            <small>Respondo a todos os emails no prazo de 12 horas.</small>
        </article>

    </section>


    
    <section class="container-servicos-contactos">

        <h1>Conheça os nossos servicos.</h3>

            <div class="botoes-servicos-contactos">
                <a href="servicos.html" class="botao">Os nossos serviços</a>
            </div>

    </section>

    <footer>
        ViniciusdevCorp &copy; 2024| &reg; Todos os direitos reservados.
    </footer>





</body>

</html>

Pagina de serviços

<!DOCTYPE html>
<html lang="pt">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ViniciusdevCorp</title>

    
    <link rel="stylesheet" href="assets/css/estilos.css">

    
    <link rel="shortcut icon" href="assets/images/logo_empresa.png" type="image/png">

</head>

<body>

    
    <header class="container-cabecalho">
        <a href="index.html">
            <img src="assets/images/logo_empresa.png" alt="Logo da empresa" title="ViniciusdevCorp">
        </a>
        <h3>ViniciusdevCV</h3>
    </header>

    
    <nav class="container-navegacao">
        <a href="index.html">Quem sou</a>
        <a href="servicos.html">Nossos Serviços</a>
        <a href="contactos.html">Contatos</a>
    </nav>

    
    <section class="container-servicos">
        
        <h1 class="text-center">Os nossos serviços</h1>

        <article>
            <h3>Soluções inovadoras para a sua empresa</h3>
            <ul>
                <li>Desenhamos novas soluções </li>
                <li>Aumentamos a performance e eficiência do seu codigo</li>
                <li>Incremento garantido de 20% nos lucros da empresa.</li>
            </ul>
        </article>

        <article>
            <h3>Projetamos o futuro do seu negócio</h3>
            <ol>
                <li>Pensamos na melhor solução</li>
                <li>Desenvolvemos o produto em parceria consigo</li>
                <li>Aplicamos a solução na empresa.</li>
                <li>Fazemos a monitorização do processo.</li>
            </ol>
        </article>

    </section>


    
    <section class="container-servicos-contactos">

        <h1>Obtenha mais informações.</h3>

            <div class="botoes-servicos-contactos">
                <a href="contactos.html" class="botao">Contate-me</a>
            </div>

    </section>

    <footer>
        ViniciusdevCorp &copy; 2024 | &reg; Todos os direitos reservados.
    </footer>





</body>

</html>
```

Icones utilizados:

<img src="https://raw.githubusercontent.com/Viniciussinc/curriculo_sitetr01/main/cv/assets/images/logo_empresa.png"/>
<img src="https://github.com/Viniciussinc/curriculo_sitetr01/blob/main/cv/assets/images/icon_ai.png"/>
<img src="https://github.com/Viniciussinc/curriculo_sitetr01/blob/main/cv/assets/images/icon_computer.png "/>
<img src="https://github.com/Viniciussinc/curriculo_sitetr01/blob/main/cv/assets/images/icon_email.png "/>
<img src="https://github.com/Viniciussinc/curriculo_sitetr01/blob/main/cv/assets/images/icon_lab.png "/>
<img src="https://github.com/Viniciussinc/curriculo_sitetr01/blob/main/cv/assets/images/icon_phone%20copy.png "/>
<img src="https://github.com/Viniciussinc/curriculo_sitetr01/blob/main/cv/assets/images/icon_phone.png "/>

Prints do site:
<img src="[image_2024-03-22_144509147.png](https://raw.githubusercontent.com/Viniciussinc/curriculo_sitetr01/main/cv/assets/images/Print%201.png)https://raw.githubusercontent.com/Viniciussinc/curriculo_sitetr01/main/cv/assets/images/Print%201.png"/>
<img src="https://raw.githubusercontent.com/Viniciussinc/curriculo_sitetr01/main/cv/assets/images/PRint%202.png"/>
<img src="[https://raw.githubusercontent.com/Viniciussinc/curriculo_sitetr01/main/cv/assets/images/PRint%202.png](https://raw.githubusercontent.com/Viniciussinc/curriculo_sitetr01/main/cv/assets/images/Print%203.png)"/>

