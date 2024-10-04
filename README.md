<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gestão da Jornada de Trabalho e Folha de Pagamento</title>
    <link rel="stylesheet" href="src/[RH no Quadro] Como calcular a Folha de Pagamento_ _ Convenia.mp4">
    <link rel="stylesheet" href="src/WhatsApp Image 2024-10-03 at 21.54.57.jpeg">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .content {
            max-width: 800px;
            margin: 20px auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .topic-box {
            background-color: #f5f5dc;
            /* Cor bege */
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .topic-box:hover {
            background-color: #e3e3b9;
            /* Alteração na cor ao passar o mouse */
        }

        h2 {
            color: #34495e;
            margin: 0;
        }

        p {
            color: #333;
            line-height: 1.6;
        }

        #final-quote {
            font-style: italic;
            margin: 20px 0;
            text-align: center;
        }

        #participants {
            margin: 20px 0;
        }

        img {
            display: block;
            margin: 20px auto;
            max-width: 100%;
            height: auto;
        }
    </style>
</head>

<body>

    <header>
        <h1>Gestão da Jornada de Trabalho e Folha de Pagamento</h1>
    </header>

    <div class="content">
        <div class="topic-box" onclick="document.getElementById('suspensao').scrollIntoView()">
            <h2>1. Suspensão: O que é isso?</h2>
            <p>Imagine que você tenha que parar de trabalhar por algum motivo, como uma licença não remunerada...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('suspensao-saude').scrollIntoView()">
            <h2>2. Suspensão por motivos de saúde</h2>
            <p>Quando um funcionário se afasta por motivo de saúde a partir do 16º dia, o contrato também entra em
                suspensão...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('interrupcao').scrollIntoView()">
            <h2>3. Interrupção do contrato de trabalho</h2>
            <p>Diferente da suspensão, na interrupção você continua recebendo os seus direitos normalmente...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('jornada').scrollIntoView()">
            <h2>4. Jornada de Trabalho: De Segunda a Sexta</h2>
            <p>Aqui a regra é clara! A jornada de trabalho geralmente é de 8 horas diárias...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('horas-extras').scrollIntoView()">
            <h2>5. Horas Extras: Trabalhou mais? Recebe mais!</h2>
            <p>Se você fez horas extras, não se preocupe. Existe uma regrinha básica aqui...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('banco-horas').scrollIntoView()">
            <h2>6. Banco de Horas: Compensar as horas extras</h2>
            <p>Uma alternativa legal às horas extras é o famoso banco de horas...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('trabalho-noturno').scrollIntoView()">
            <h2>7. Trabalho Noturno: Trabalhar à noite tem bônus</h2>
            <p>Se você trabalha entre 22h e 5h da manhã, saiba que tem direito a um adicional de 20%...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('intervalos').scrollIntoView()">
            <h2>8. Intervalos são importantes!</h2>
            <p>Durante o trabalho, você precisa de uma pausa, certo? Isso é chamado de intervalo intrajornada...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('descanso').scrollIntoView()">
            <h2>9. Descanso Semanal Remunerado (DSR)</h2>
            <p>Aqui vai uma boa notícia: você tem direito a um dia de descanso por semana...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('ferias').scrollIntoView()">
            <h2>10. Férias: Todo mundo precisa!</h2>
            <p>Após 12 meses de trabalho, você tem direito a 30 dias de férias...</p>
        </div>

        <div class="topic-box" onclick="document.getElementById('seguranca').scrollIntoView()">
            <h2>11. Segurança e Saúde no Trabalho: Cuide-se!</h2>
            <p>Nada mais importante do que trabalhar num ambiente seguro, né? Por isso, a empresa precisa garantir...
            </p>
        </div>

        <div class="topic-box" onclick="document.getElementById('fgts').scrollIntoView()">
            <h2>12. FGTS e Seguro-Desemprego</h2>
            <p>O Fundo de Garantia do Tempo de Serviço (FGTS) é aquele dinheirinho que a empresa deposita todo mês...
            </p>
        </div>

        <div class="topic-box" onclick="document.getElementById('importancia-folha').scrollIntoView()">
            <h2>13. A Importância da Folha de Pagamento</h2>
            <p>A folha de pagamento é um documento essencial que registra todos os pagamentos realizados pela empresa...
            </p>
        </div>

        <div class="topic-box" onclick="document.getElementById('calculos').scrollIntoView()">
            <h2>14. Cálculos Simples que fazem a diferença</h2>
            <p>Por fim, vamos falar dos cálculos que fazem a diferença na hora de pagar o salário...</p>
        </div>

        <div id="suspensao">
            <h2>1. Suspensão: O que é isso?</h2>
            <p>Imagine que você tenha que parar de trabalhar por algum motivo, como uma licença não remunerada... A
                suspensão do contrato de trabalho ocorre quando o empregado deixa de exercer suas atividades, mas mantém
                o vínculo empregatício. Isso pode acontecer em várias situações, como licença maternidade, entre outros.
            </p>
        </div>

        <div id="suspensao-saude">
            <h2>2. Suspensão por motivos de saúde</h2>
            <p>Quando um funcionário se afasta por motivo de saúde a partir do 16º dia, o contrato também entra em
                suspensão. Isso significa que, durante esse período, a empresa não precisa pagar o salário, mas o
                funcionário mantém o direito de retornar ao trabalho após a recuperação.</p>
        </div>

        <div id="interrupcao">
            <h2>3. Interrupção do contrato de trabalho</h2>
            <p>Diferente da suspensão, na interrupção você continua recebendo os seus direitos normalmente. O contrato
                de trabalho é interrompido, mas não extinto. Isso pode ocorrer, por exemplo, durante uma licença
                remunerada.</p>
        </div>

        <div id="jornada">
            <h2>4. Jornada de Trabalho: De Segunda a Sexta</h2>
            <p>Aqui a regra é clara! A jornada de trabalho geralmente é de 8 horas diárias, totalizando 44 horas
                semanais. Isso varia conforme as convenções coletivas e acordos individuais. As empresas devem respeitar
                esse limite para garantir a saúde e o bem-estar dos funcionários.</p>
        </div>

        <div id="horas-extras">
            <h2>5. Horas Extras: Trabalhou mais? Recebe mais!</h2>
            <p>Se você fez horas extras, não se preocupe. Existe uma regrinha básica aqui: as horas trabalhadas além da
                jornada normal devem ser pagas com um adicional de 50% ou 100%, dependendo do dia e do horário. É
                fundamental que as empresas controlarem essas horas para garantir os direitos dos trabalhadores.</p>
        </div>

        <div id="banco-horas">
            <h2>6. Banco de Horas: Compensar as horas extras</h2>
            <p>Uma alternativa legal às horas extras é o famoso banco de horas. Nele, as horas excedentes podem ser
                compensadas com folgas em outros dias, permitindo uma maior flexibilidade para os colaboradores e as
                empresas. O banco de horas deve ser registrado e acordado entre empregado e empregador.</p>
        </div>

        <div id="trabalho-noturno">
            <h2>7. Trabalho Noturno: Trabalhar à noite tem bônus</h2>
            <p>Se você trabalha entre 22h e 5h da manhã, saiba que tem direito a um adicional de 20% sobre o seu
                salário. Isso é um reconhecimento pelo esforço e pelas particularidades de trabalhar em horário noturno.
                A empresa deve ficar atenta a essa obrigação para garantir os direitos dos seus funcionários.</p>
        </div>

        <div id="intervalos">
            <h2>8. Intervalos são importantes!</h2>
            <p>Durante o trabalho, você precisa de uma pausa, certo? Isso é chamado de intervalo intrajornada. Para
                jornadas superiores a 6 horas, o intervalo deve ser de no mínimo 1 hora, e para jornadas de até 6 horas,
                de 15 minutos. É fundamental para a saúde e produtividade do trabalhador.</p>
        </div>

        <div id="descanso">
            <h2>9. Descanso Semanal Remunerado (DSR)</h2>
            <p>Aqui vai uma boa notícia: você tem direito a um dia de descanso por semana, que pode ser pago ao final do
                mês. Isso significa que, se você trabalhou durante toda a semana, deve receber uma remuneração
                correspondente ao seu dia de folga. A legislação garante esse direito para todos os trabalhadores.</p>
        </div>

        <div id="ferias">
            <h2>10. Férias: Todo mundo precisa!</h2>
            <p>Após 12 meses de trabalho, você tem direito a 30 dias de férias. Esse é um momento importante para
                descansar e recuperar as energias. Durante as férias, você recebe o salário normalmente, e a empresa
                deve programar esse período para garantir que as atividades não sejam prejudicadas.</p>
        </div>

        <div id="seguranca">
            <h2>11. Segurança e Saúde no Trabalho: Cuide-se!</h2>
            <p>Nada mais importante do que trabalhar num ambiente seguro, né? Por isso, a empresa precisa garantir
                condições adequadas para seus colaboradores. Isso inclui equipamentos de proteção, treinamentos e ações
                que visem à saúde mental e física dos funcionários.</p>
        </div>

        <div id="fgts">
            <h2>12. FGTS e Seguro-Desemprego</h2>
            <p>O Fundo de Garantia do Tempo de Serviço (FGTS) é aquele dinheirinho que a empresa deposita todo mês para
                você. Em caso de demissão sem justa causa, você pode sacar esse valor. Além disso, o seguro-desemprego é
                um direito que ajuda a manter a estabilidade financeira do trabalhador após a perda do emprego.</p>
        </div>

        <div id="importancia-folha">
            <h2>13. A Importância da Folha de Pagamento</h2>
            <p>A folha de pagamento é um documento essencial que registra todos os pagamentos realizados pela empresa a
                seus funcionários. Ela deve ser feita com atenção para garantir que todos os direitos trabalhistas sejam
                respeitados e que os funcionários recebam o que lhes é devido.</p>
        </div>

        <div id="calculos">
            <h2>14. Cálculos Simples que fazem a diferença</h2>
            <p>Por fim, vamos falar dos cálculos que fazem a diferença na hora de pagar o salário. É importante que a
                empresa tenha um sistema claro para calcular salários, descontos e benefícios, garantindo que não haja
                erros que possam prejudicar o trabalhador.</p>
        </div>

        <html lang="en">

        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Smaller Video Example</title>
        </head>

        <body>

            <h1>Como calcular uma folha de pagamento</h1>


            <video width="480" height="220" controls>
                <source src="video.mp4" type="video/mp4"> <!-- Coloque o caminho do seu vídeo aqui -->
                Seu navegador não suporta o elemento de vídeo.
            </video>

        </body>

        </html>





        <div id="final-quote">
            <p>"A gestão eficiente da jornada de trabalho e da folha de pagamento é essencial para o bem-estar dos
                colaboradores e a saúde financeira da empresa."</p>
        </div>


        <div id="participants">
            <p>Participantes:</p>
            <ul>
                <li>Filipe Lacerda de Oliveira</li>
                <li>Jéssica Santos Oliveira</li>
                <li>Fernanda Silva Oliveira</li>
                <li>Sara dos Santos Araújo</li>
            </ul>

            <img src="lipe.jpeg" style="display: flex;" alt="Imagem relacionada ao tema do blog">

        </div>

</body>

</html>
