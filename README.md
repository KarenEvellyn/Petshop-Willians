# Petshop-Willians
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mary e & Gabi</title>
    <link rel="stylesheet" href="css/index.css">
</head>

<body>
    <header>
        <h1 title="Mary & Gabi Petshop">
            <img src="img/logo-mari-e-gabi-petshop.svg" alt="Mary & Gabi Pet shop">
        </h1>
    </header>
    <nav class="menu">
        <ul>
            <li><a href="#">Sobre</a></li>
            <li><a href="#">Produto</a></li>
            <li><a href="#">Serviço</a></li>
            <li id="itemcontato"><a href="#">Contato</a></li>
        </ul>
    </nav>
    <article class="fundo-verde">
        <div class="conteiner flex-conteiner">
            <div class="col">

                <h2>Sobre nós</h2>
                <p>Lorem ipsum, dolor sit
                    amet consectetur adipisicing
                    elit. Dolorum culpa quo est ab fugiat animi
                    delectus tempora
                    incidunt quia mollitia? Nisi atque culpa porro
                    quis sequi. Eveniet eaque maiores optio!
                </p>
                <p>Lorem ipsum dolor sit, amet consectetur
                    adipisicing elit. Repellat modi,
                    dicta at voluptas amet architecto
                    pariatur ducimus dignissimos accusantium
                    necessitatibus perferendis magni sit alias
                    doloribus commodi quo autem reiciendis
                    consectetur.</p>
            </div>
            <div class="col">
                <img src="img/WhatsApp Image 2021-11-10 at 19.13.15.jpeg" alt="">
            </div>
        </div>

    </article>
    <article>
        <div class="conteiner">
            <h2 class="texto-centralizado">Produtos</h2>
            <P class="texto-centralizado">Lorem ipsum dolor sit amet,
                consectetur adipisicing elit. Voluptas consectetur
                aliquid ducimus saepe tenetur, fugit vel, cupiditate
                exercitationem delectus sunt aspernatur ipsum eum qui
                culpa deleniti
                quis rerum neque placeat!</P>
            <div class="flex-conteiner">
                <article class="produto">
                    <figure>
                        <img src="img/WhatsApp Image 2021-11-10 at 19.13.15 (1).jpeg" alt="Produto pet 1">
                    </figure>
                    <h3>Pet produto #1</h3>
                    <p>R$50,00,00</p>
                    <a href="#" class="btn_patinha">
                   
                    <img src="img/WhatsApp Image 2021-11-10 at 19.13.16.jpeg" alt="patinha preta">
                    comprar
                </a>
                </article>
                <article class="produto">
                    <figure>
                        <img src="img/WhatsApp Image 2021-11-10 at 19.13.15 (2).jpeg" alt="Produto pet 2">
                    </figure>
                    <h3>Pet produto #1</h3>
                    <p>R$160,00</p>
                    <a href="#" class="btn_patinha">
                   
                    <img src="img/WhatsApp Image 2021-11-10 at 19.13.16.jpeg" alt="patinha preta">
                    comprar
                </a>
                </article>
                <article class="produto">
                    <figure>
                        <img src="img/WhatsApp Image 2021-11-10 at 19.13.17.jpeg" alt="Produto pet 3">
                    </figure>
                    <h3>Pet produto #1</h3>
                    <p>R$35,00</p>
                    <a href="#" class="btn_patinha">
                   
                    <img src="img/WhatsApp Image 2021-11-10 at 19.13.16.jpeg" alt="patinha preta">
                    comprar
                </a>
                </article>
            </div>
    </article> 
    <article class="fundo-verde">
        <div class="conteiner flex-conteiner">
            <div class="col">

                <h2>Serviços</h2>
                <p>Lorem ipsum, dolor sit
                    amet consectetur adipisicing
                    elit. Dolorum culpa quo est ab fugiat animi
                    delectus tempora
                    incidunt quia mollitia? Nisi atque culpa porro
                    quis sequi. Eveniet eaque maiores optio!
                </p>
                <p>Lorem ipsum dolor sit, amet consectetur
                    adipisicing elit. Repellat modi,
                    dicta at voluptas amet architecto
                    pariatur ducimus dignissimos accusantium
                    necessitatibus perferendis magni sit alias
                    doloribus commodi quo autem reiciendis
                    consectetur.</p>
            </div>
            <div class="col">
                <img src="img/WhatsApp Image 2021-11-10 at 19.13.13 (1).jpeg" alt="cachorro">
                <img src="img/WhatsApp Image 2021-11-10 at 19.13.13.jpeg" alt="comercio">
                <img src="img/WhatsApp Image 2021-11-10 at 19.13.13 (2).jpeg" alt="cachorro">
                <img src="img/WhatsApp Image 2021-11-10 at 19.13.14.jpeg" alt="cachorro">
            </div>           
        </div>

    </article>

    <article>
      <div class="conteiner">
        <h2 class="texto-centralizado">Contato</h2>
        <P class="texto-centralizado">Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Voluptas consectetur
            aliquid ducimus saepe tenetur, fugit vel, cupiditate
            exercitationem delectus sunt aspernatur ipsum eum qui
            culpa deleniti
            quis rerum neque placeat!Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Voluptas consectetur
            aliquid ducimus saepe tenetur, fugit vel, cupiditate
            exercitationem delectus sunt aspernatur ipsum eum qui
            culpa deleniti
            quis rerum neque placeat!</P>
   
    <div class="flex-conteiner">
        <div class="col">
            <form action="">
                <label for="nome">
                    <strong>Nome:</strong>
                    <input type="text"  id="nome"
                    placeholder="Insira o seu nome completo"/>                   
                </label>
                <label for="email">
                    <strong>E-mail:</strong>
                    <input type="email" id="email"
                    placeholder="exemplo@teste.com.br"/>
                </label>
                <label for="fone">
                <strong>Telefone</strong>
                <input type="tel" id="tel" placeholder="(11)0000-0000 ou (11)90000-0000">
            </label>
            <label for="assunto">
                <strong>assunto</strong>
                <input type="text" placeholder="Insira aqui o assunto da sua mensagem" id="assunto">    
            </label>
            <label for="msg">
                <strong>mensagem:</strong>
                <textarea name="msg" id="msg"
                rows="10" placeholder="Insira aqui a sua mensagem"></textarea>
            </label>
            <div>
                <button class="btn-patinh">
                    <img src="img/WhatsApp Image 2021-11-10 at 19.13.16.jpeg" alt="Patinha preta">
                    Enviar
                </button>
            </div>
            </form>
        </div>
     
     <div class="col">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3
        653.399832484626!2d-46.7663508!3d-23.697411700000004!2m3!1f0!2f0!3f0
        !3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce5212f9627de5%3A0x1c5ccd29c1
        a3e96a!2sEtec%20Jardim%20%C3%82ngela!5e0!3m2!1spt-BR!2sbr!4v1637630796176!5m2!1spt-BR!2sbr"
         width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
         <p>Endereço: Almeida Canoism 237 - Vila 
            Mariana, São Paulo /SP <br>
            <strong>CEP:</strong> 04101-300 <br><br>
            
        </p>
     </div>
     </div>
    </div>
</article>

<footer id="rodape">
<div class="conteiner texto-centralizado">
    <p>Copyright &copy; 2021 <strong>petshop Mary & Gabi | Todos os direitos
         reservados

    </strong></p>
</div>
</footer>


   
</body>

</html>
