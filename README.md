# Portfólio de Débora Laís

## Descrição
Este projeto alem de ser o meu primeiro é um portfólio pessoal criado para apresentar minhas habilidades, projetos e um pouco da minha trajetória. Utilizei HTML e CSS para construir a estrutura e o design do site, 
com a inclusão de algumas bibliotecas externas para ícones e fontes.

## Estrutura do Projeto
O projeto é composto pelos seguintes arquivos:

- `index.html`: Contém a estrutura básica da página web.
- `style.css`: Contém os estilos utilizados para formatar a página.
- `images/`: Diretório que contém as imagens utilizadas no site.

## Funcionalidades
- **Header**: Inclui o logotipo e a navegação do site.
- **Seção Topo**: Uma breve introdução sobre mim e minha história.
- **Habilidades**: Lista das minhas principais habilidades com ícones.
- **Sobre**: Uma descrição mais detalhada sobre quem sou e minha trajetória.
- **Atividades Realizadas**: Galeria de imagens dos projetos e atividades realizadas.
- **Formulário de Contato**: Um formulário para que visitantes possam entrar em contato comigo.
- **Footer**: Inclui links para minhas redes sociais e e-mail de contato.

# Codigos

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- GOOGLE FONTES -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <!-- FIM GOOGLE FONTES -->
    <!-- BOOTSTRAP -->
    <!-- Bootstrap Font Icon CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css">
    <!-- Font Awesome CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <!-- FIM BOOTSTRAP -->
    <link rel="stylesheet" href="style.css">
    <title>Portifolio</title>
</head>
<body>
   
    <header>
        <div class="interface">
             <div class="logo">
                <a href="#">
                    <img src="images/logo_transparent.png" width="160px" height="100px" alt="Logo">
                </a>
            </div><!--logo-->

            <nav class="menu-desktop">
                <ul>
                    <li><a href="#">Início</a></li>
                    <li><a href="#">Habilidades</a></li>
                    <li><a href="#">Bio</a></li>
                    <li><a href="#">Atividades Realizadas</a></li>
                   
                </ul>
            </nav>
            
            <div class="Contato">
                <a href="#">
                    <button>Contato</button>
                </a>
            </div><!--contato-->>

        </div><!--interface-->
    </header>
    
    <main>
        <section class="topo-do-site">
            <div class="interface">
                <div class="flex">
                    <div class="txt-topo-site">
                        <h1>UM POUCO SOBRE A HISTORIA DA DÉBORA LAÍS<span>.</span></h1>
                        <p>Nunca imaginei que um dia trabalharia com algo que fazia por diversão. Este portfólio vai mostrar um pouco da minha trajetória, projetos e habilidades. Como um dia eu disse na minha primeira seleção de emprego: "Acredito que a tecnologia é o primeiro passo para um futuro que nossos antepassados sonharam e que hoje tentamos realizar." Como um dia Steve Jobs citou: "A tecnologia move o mundo." </p>

                        <div class="Contato">
                            <a href="#">
                                <button>Entre em Contato</button>
                            </a>
                        </div>
                    </div><!--txt-topo-site-->
                <div class="img-topo-site">
                    <img src="images/Imagem-do-topo-site.jpeg" width="550" height="450"  alt="">
                 </div><!--img-topo-site-->
                </div><!--flex-->
            </div><!--interface-->
        </section><!--topo-do-site-->

        <section class="habilidades">
            <div class="interface">
                <h2 class="titulo">MINHAS <span>HABILIDADES.</span></h2>

                <div class="flex">
                    <div class="habilidades-box">
                        <i class="bi bi-code-square"></i>
                        <h3>Website</h3>
                        <p>Conhecimentos em html e css .</p>
                    </div><!--habilidades-box-->

                    <div class="habilidades-box">
                        <i class="bi bi-translate"></i>
                        <h3>Ingles</h3>
                        <p>Conhecimentos na lingua inglesa com certificação do CCI como validação</p>
                    </div><!--habilidades-box-->

                    <div class="habilidades-box">
                        <i class="bi bi-people-fill"></i>
                        <h3>Trabalho em equipe</h3>
                        <p>Conhece os fundamentos e possui uma certificação do Linked como validação</p>
                    </div><!--habilidades-box-->

                    <div class="habilidades-box">
                        <i class="bi bi-display"></i>
                        <h3>Ciencia da Computação</h3>
                        <p>Estudante de Ciencia da Computação com previsão de graduação para 2025.</p>
                    </div><!--habilidades-box-->

                    <div class="habilidades-box">
                        <i class="bi bi-book-fill"></i>
                        <h3>Gosta de aprender</h3>
                        <p>Essa universitaria ama aprender coisas novas </p>
                    </div><!--habilidades-box-->

                    <div class="habilidades-box">
                        <i class="bi bi-box-arrow-in-right"></i>
                        <h3>AWS na prática</h3>
                        <p>Conhecimentos sobre Aws adquiridos na plataforma udemy com certificação para validação .</p>
                    </div><!--habilidades-box-->
                </div><!--flex-->
            </div><!--interface-->
        </section><!--habilidades-->

        <section class="sobre">
            <div class="interface">
                <div class="flex">
                    <div class="img-sobre">
                        <img src="images/Imagem-sobre.jpeg" width="600px" height="750px">
                    </div><!--img-sobre-->

                    <div class="txt-sobre">
                        <h2>MUITO PRAZER, <span>SOU DÉBORA LAÍS.</span></h2>
                        <p>Oi, sou a Debora Lais, uma universitária de 20 anos apaixonada por Ciência da Computação. Atualmente, estou cursando na  universidade estacio e mergulhando de cabeça em desafios e projetos tecnológicos. Além dos estudos, participo ativamente do "Programadores do Amanhã" e estou vivendo uma experiência incrível como estagiária na Compass UOL. Estou animada para crescer nesse mundo em constante evolução e contribuir de forma significativa para a área. É isso aí, sempre em busca de aprendizado e novas oportunidades!</p>
                        <p>Na minha jornada no "Programadores do Amanhã", tenho me dedicado não apenas ao aprendizado técnico em programação, mas também ao desenvolvimento de soft skills e ao aprimoramento do inglês. Essa experiência tem sido fundamental para a construção de uma base sólida de habilidades, preparando-me para os desafios futuros. Além disso, como estagiária na Compass UOL, estou imersa no universo prático, focando especificamente em aprimorar minhas habilidades em Linux e AWS. É incrível como cada dia traz novos conhecimentos e oportunidades de crescimento, e estou empolgada para continuar explorando e evoluindo nesse ambiente dinâmico.</p>
                        <div class="social">
                            <a href="https://www.instagram.com/lais__debora/" target="_blank" rel="noopener noreferrer"><button><i class="bi bi-instagram"></i></button></a>
                            <a href="http://www.linkedin.com/in/d%C3%A9bora-la%C3%ADs-506226229" target="_blank" rel="noopener noreferrer"><button><i class="bi bi-linkedin"></i></button></a>
                            <a href="https://github.com/Debora-Laiss" target="_blank" rel="noopener noreferrer"><button><i class="bi bi-github"></i></button></a>
                         </div><!--social-->                         
                    </div><!--txt-sobre-->
                </div><!--flex-->

            </div><!--interface-->

        </section><!--sobre-->
   
        <section class="atividades-realizadas">
            <div class="interface">
                <h2 class="titulo">ATIVIDADES <span>REALIZADAS.</span></h2>
                <div class="flex-container">
                    <div class="flex-item" id="projeto1">
                        <img src="images/1.png" width="400" height="200">
                        <img src="images/2.png" width="400" height="200">
                         <img src="images/3.png" width="400" height="200">
                        <img src="images/4.png" width="400" height="200">
                    </div>
                    <div class="flex-item" id="projeto2">
                        <img src="images/Home.jpg" width="400" height="200">
                        <img src="images/Background.jpg" width="400" height="200">
                        <img src="images/3.jpg" width="400" height="200">
                        <img src="images/Commissions.jpg" width="400" height="200">
                    </div>
                
                </div><!--flex-container-->
            </div><!--interface-->
        </section><!--atividades-realizadas-->

        <section class="formulario">
            <div class="interface">
                <h2 class="titulo">FALE <span>COMIGO.</span></h2>

                <form action="">
                    <input type="text" name="" id="" placeholder="Seu nome:" required>
                    <input type="text" name="" id="" placeholder="Seu e-mail:" required>
                    <input type="text" name="" id="" placeholder="Seu celular:" required>
                    <textarea name="" id="" placeholder="Sua mensagem" required></textarea>
                    <div class="enviar"><input type="submit" value="ENVIAR"></div>
                </form>
            </div>

        </section><!--Formulario-->
    </main>

    <footer>
        <div class="interface">
            <div class="line-footer">
                <div class="flex">
                    <div class="logo-footer">
                        <img src="images/logo_transparent.png" width="160" height="100" alt="Logo">
                    </div><!--logo-footer-->
                    <div class="social">
                        <a href="https://www.instagram.com/lais__debora/" target="_blank" rel="noopener noreferrer"><button><i class="bi bi-instagram"></i></button></a>
                        <a href="http://www.linkedin.com/in/d%C3%A9bora-la%C3%ADs-506226229" target="_blank" rel="noopener noreferrer"><button><i class="bi bi-linkedin"></i></button></a>
                        <a href="https://github.com/Debora-Laiss" target="_blank" rel="noopener noreferrer"><button><i class="bi bi-github"></i></button></a>
                    </div><!--social-->   
                </div>  
            </div>

            <div class="line-footer">
                <p><i class="bi bi-envelope"></i> <a href="mailto:deboralaisnm@gmail.com">deboralaisnm@gmail.com</a></p>
            </div><!--line-footer-->
        </div><!--interface-->
    </footer>

</body>
</html>
```html
```css


/*ESTILO GERAL*/
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    background-color: black;
    height: 100vh;
}
.interface{
    max-width: 1280px;
    margin: 0 auto;
}

.flex{
    display:flex;
}

.Contato button{
    padding: 10px 40px;
    font-size: 18px;
    font-weight: 600;
    background-color: rgb(0, 141, 177);
    border: 0;
    border-radius: 30px;
    cursor: pointer;
    transition: .2s;
}

button:hover, form .enviar input:hover{
    box-shadow: 0px 0px 8px #80c4ebbd;
    transform: scale(0.90) ;
}

h2.titulo{
    color: aliceblue;
    font-size: 38px;
    text-align: center;
}

h2.titulo span{
    color: rgb(112, 181, 226);
}
/* ESTILO DO CABEÇALHO */   
header{
    padding: 40px 4%;
}

header > .interface{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

header a{
    color: rgba(250, 235, 215, 0.575);
    text-decoration: none;
    display: inline-block;
    transition: .2s;
}

header a:hover{
    color: rgb(112, 181, 226);
    transform: scale(1.30);
}


header nav ul{
    list-style-type: none;
}

header nav li{
    display: inline-block;
    padding: 0 40px;
}



/* ESTILO DO TOPO DO SITE*/
section.topo-do-site{
    padding: 80px 4%;
}
section.topo-do-site .flex{
    align-items: center;
    justify-content: center;
    gap: 90px;
}
.topo-do-site h1{
    color: aliceblue;
    font-size: 42px;
    line-height: 40px;
}
.topo-do-site .txt-topo-site h1 span{
    color: rgb(112, 181, 226);
    font-size: 40px;
}
.topo-do-site .txt-topo-site p{
    color: aliceblue;
    margin: 40px 0;
}

.topo-do-site .img-topo-site img{
    position: relative;
    animation: flutuar 2s ease-in-out infinite alternate;
    border-radius: 6%;
    box-shadow: 2px 2px 5px 0px #80c4eb;
}

@keyframes flutuar{
    0%{
        top: 0;
    }
    100%{
        top: 30px;
    }
}

/*ESTILO DAS HABILIDADES*/
section.habilidades{
    padding: 80px 4%;
   
}

section.habilidades .flex{
    gap: 60px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
 }
 

.habilidades .habilidades-box{
    color: aliceblue;
    padding: 40px;
    border: 2px solid aliceblue;
    border-radius: 25px;
    margin-top: 45px;
    transition: 1.2s;
    flex: 0 0 33.33%; /* Isso faz com que cada caixa ocupe 1/3 do espaço disponível */
    box-sizing: border-box; /* Isso inclui padding e border no tamanho total da caixa */
}

.habilidades .habilidades-box:hover{
    transform: scale(1.05);
    box-shadow: 0 0 20 px #e0d0d0f5;
}

habilidades .habilidades-box i{
    font-size: 70px;
    color: #0093e9;
}

habilidades .habilidades-box h3{
    font-size: 28px;
    margin: 15px 0;
}

/* ESTILO DO SOBRE */
section.sobre{
    padding: 40px 4%;
    box-shadow:  0 0 40px 10px #ffffff1d;
}

section.sobre .flex{
    align-items: center;
    gap: 60px;
}

.sobre .txt-sobre{
    color: aliceblue;
}

.sobre .txt-sobre h2{
    font-size: 40px;
    line-height: 40px;
    margin-bottom: 30px;
}
 
.sobre .txt-sobre h2 span{
    color: #80c4eb;
    display: block;
}
 
.sobre .txt-sobre p{
    margin: 20px 0;
    text-align: justify;
}

.social button{
    width: 60px;
    height: 60px;
    border-radius: 50%;
    border: 0;
    background-color: #80c4eb;
    font-size: 22px;
    cursor: pointer;
    margin: 0 8px;
    transition: .2s;
}

/* ESTILO MINHAS ATIVIDADES */
section.atividades-realizadas{
    padding: 80px 4%;
    box-shadow: 0 0 40px 10px #ffffff1d;
 }
 
 .flex-container {
    display: flex;
    justify-content: space-around;
    margin-top: 50px;
 }
 
 .flex-item {
    flex: 1 0 45%; /* Isso permite que cada item ocupe aproximadamente metade da largura do contêiner, com um pequeno espaço entre eles */
    margin: 5px;
 }
 
 .flex-item img{
    width: 100%;
    height: auto;
 }
 
 img {
    border-radius: 5px;
    box-shadow: 0 4px 8px 0 #80c4eb;
    transition: 0.3s;
    cursor: pointer;
 }
 
 img:hover {
    box-shadow: 0 8px 16px 0 #80c4eb;
 }
 
/* ESTILO DE FORMULARIO DE CONTATO */
section.formulario{
    padding: 80px 4%;
    box-shadow: 0 0 40px 10px #ffffff1d;
}

form{
    max-width: 500px;
    margin: 0 auto;
    display: flex;
    justify-content: center;
    flex-direction: column;
    gap: 10px;
    margin-top: 40px;
}

form input, form textarea{
    width: 100%;
    background-color: #6b6b6bce;
    border: 0;
    outline: 0;
    padding: 20px 15px;
    border-radius: 15px;
    color: #fff;
    font-size: 18px;
}

form input::placeholder{
    color: #bbbbbb;
}

form textarea::placeholder{
    color: #bbbbbb;
}


form textarea{
    resize: none;
    max-height: 200px;
}

form .enviar{
    margin-top: 20px;
}

form .enviar input{
    width: 120px;
    background-color: #80c4eb;
    color: #000000b4;
    font-weight: 700;
    cursor: pointer;
    transition: .2s;
}

/* ESTILO RODAPE */
footer{
    padding: 40px 4%;
    box-shadow: 0 0 40px 10px #ffffff1d;
}

footer .flex{
    justify-content: space-between;
}

footer .line-footer{
    padding: 20px 0;
    border-bottom: 2px solid #80c4eb;
}

footer .line-footer p i{
    color: #80c4eb;
    font-size: 22px;
}

footer .line-footer p a{
    color: #fff;
}

/**/
@media screen and (max-width: 1020px){
    /* CLASSES GERAIS */
    .flex{
    flex-direction:column ;
}

    .topo-do-site .flex{
        flex-direction: column-reverse;
    }

    h2.titulo{
        font-size: 38px;
        line-height: 34px;
    }
    /* CABEÇALHO */
    .menu-desktop, .Contato{
        display: none;
    }
    /* TOPO DO SITE */
    section.topo-do-site{
        padding: 20px 8%;
    }

    .topo-do-site h1{
        font-size: 30px;
    }

    .topo-do-site .img-topo-site img{
        width: 100%;
    }
    /*ESPECIALIDADES*/
    section.habilidades{
        padding: 80px 8%;
       
    }
    /*SOBRE*/
    section.sobre{
        padding: 40px 4%;
    }

    .sobre .txt-sobre h2{
        font-size: 34px;
        line-height: 35px;
        text-align: center;
    }

    .social{
        text-align: center;
    }

    .img-sobre img{
        width: 100%;
    }

    /*FORMULARIO*/
    section.formulario{
        padding: 40px 4%;
       
    }
    form .enviar{
        margin-top: 20px;
        text-align: center;
    }
    /* RODAPE */
    footer .flex{
        flex-direction: column;
        gap: 30px;
    }

    footer .line-footer{
        text-align: center;
       
    }
}
    ```css
