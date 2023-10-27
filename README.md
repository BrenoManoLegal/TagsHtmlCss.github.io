# Tags_HTML-CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dados Pessoais</title>
    <link rel="stylesheet" href="pagpessoal.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Sometype+Mono&display=swap" rel="stylesheet">
<script defer src="pagpessoal.js"></script>
</head>
<body>
    <div class="lgl">
    <h1>DADOS PESSOAIS</h1>
    <div class="img">
    <img src="papai cris_preview_rev_1.png" width="300"><br>
    </div>
</div>

<div class="legal">
        <p1>NOME</p1><br> 
    </div>
    <div class="mic">
        <p2>Breno Lima Costa</p2><br>
    </div>
    <div class="legal">
        <p3>IDADE</p3><br>
    </div>
    <div class="mic">
        <p4>17</p4><br>
    </div>
    <div class="lok">
        <p5>Desenvolvedor web em treinamento</p5><br>
    </div>
    <div class="legal">
        <p6>SOBRE MIM</p6><br>
    </div>
    <div class="mic">
        <p7>Meu nome é Breno, nasci no dia 05/09/2066, em Santo André, entrei no SESI em 2013, no primeiro ano,<br> estou nesse escola até hoje, atualmente estou no segundo ano do ensino médio, e cursando desenvolvimento de sistema no SENAI Almirante Tamandaré</p7><br>
    </div>
    <button onclick="esconde('bob')">EsconderHab</button>
    <button onclick="mostrar('bob')">MostrarHab</button>
    <button onclick="toggle('bob')">AlternarHab</button>
    <div class="legal">
        <p8>HABILIDADES</p8><br>
    </div>
    <div id="bob">
        <div class="mic">
            <p9>Atualmente estou no meio do curso sobre desenvolvimento web, porém tenho alguns conhecimentos em:<br>
            HTML<br>
            CSS<br>
            JAVASCRIPT(Básico)<br>
        </div>
    </div>
    </p9>
</div>
<div class="link">
    <a href="https://github.com/BrenoManoLegal"><img src="GitHub-Mark-removebg-preview.png" alt="github" width="100"></a>
    <div class="formulario">
    <section>
        <h2>Informações de contato</h2>


    <form method="post" action="">
        <label for="nome">Nome: </label>
        <input id="nome" type=text required name=nome/>
    <br /> 
        <label for="email">Email: </label>
        <input id="email" type=text required name=email/>
        <br />
        <label for="email">Número de telefone: </label> 
        <input id="email" type=text required name=email/>
        <br />

    <input type=submit value="Enviar contato"/>
</div>

</div>

</body>
</html>
