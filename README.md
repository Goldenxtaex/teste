<!DOCTYPE html>
<html lang="pt-br">
<head>   	
    <meta charset="UTF-8">
    <title>Barbearia Alura</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            background: #CCCCCC;
            margin: 0;
            padding: 0;
            position: relative;
        }

        #banner {
            width: 100%;
            height: auto;
            display: block;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: rgba(255, 255, 255, 0.8);
        }

        h1 {
            text-align: center;
        }

        p {
            text-align: justify;
        }

        #missao {
            font-size: 20px;
        }

        em strong {
            color: red;
        }

        .beneficios {  
            background: #FFFFFF;
            padding: 10px;
        }
    </style>
</head>

<body>
    <img id="banner" src="Capturar.PNG">
    <div class="container">
        <h1>Sobre a Barbearia Alura</h1>

        <p>Localizada no coracao da cidade, a <strong>Barbearia Alura</strong> traz para o mercado o que ha de melhor para o seu cabelo e barba. Fundada em 2019, a Barbearia Alura ja e destaque na cidade e conquista novos clientes a cada dia.</p>

        <p id="missao"><em>Nossa missao e: <strong>"Proporcionar autoestima e qualidade de vida aos clientes"</strong>.</em></p>

        <p>Oferecemos profissionais experientes e antenados as mudancas no mundo da moda. O atendimento possui padrao de excelencia e agilidade, garantindo qualidade e satisfacao dos nossos clientes.</p>
    </div>

    <div class="beneficios">
        <h2>Beneficios</h2>
        
        <ul>
            <li>Atendimento aos Clientes</li>
            <li>Espaco diferenciado</li>
            <li>Localizacao</li>
            <li>Profissionais Qualificados</li>
        </ul>
    </div>
</body>
</html>
