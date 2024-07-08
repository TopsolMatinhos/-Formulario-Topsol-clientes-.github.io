# -Formulario-Topsol-clientes-.github.io
Formulário de Satisfação clientes Topsol Energia Solar
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Pesquisa e Satisfação ao Cliente - TOPSOL</title>
</head>
<body>

<form action="processar_formulario.php" method="post">
    <h2>FORMULÁRIO DE PESQUISA E SATISFAÇÃO AO CLIENTE</h2>
    <h3>EMPRESA TOPSOL</h3>
    <p>Obrigado por escolher nossos serviços de energia solar! Seu feedback é essencial para melhorarmos continuamente. Por favor, dedique alguns minutos para nos fornecer suas opiniões.</p>

    <h4>Informações do Cliente:</h4>
    <p>
        <label for="nome">Nome:</label><br>
        <input type="text" id="nome" name="nome" required>
    </p>
    <p>
        <label for="localizacao">Localização (Cidade/Estado):</label><br>
        <input type="text" id="localizacao" name="localizacao" required>
    </p>

    <h4>Experiência de Compra:</h4>
    <p>
        Como conheceu nossa empresa TOPSOL?<br>
        <input type="checkbox" id="indicação" name="como_conheceu" value="Indicação de Amigos/Família">
        <label for="indicação">Indicação de Amigos/Família</label><br>

        <input type="checkbox" id="pesquisa_online" name="como_conheceu" value="Pesquisa Online">
        <label for="pesquisa_online">Pesquisa Online</label><br>

        <input type="checkbox" id="redes_sociais" name="como_conheceu" value="Redes Sociais">
        <label for="redes_sociais">Redes Sociais</label><br>

        <input type="checkbox" id="publicidades" name="como_conheceu" value="Publicidades">
        <label for="publicidades">Publicidades</label><br>

        <input type="checkbox" id="outro" name="como_conheceu" value="Outro">
        <label for="outro">Outro (Especificar):</label>
        <input type="text" id="outro_especificar" name="como_conheceu_outro">
    </p>
    <p>
        Qual foi o principal motivo que o(a) levou a escolher nossa empresa?<br>
        <textarea id="motivo_escolha" name="motivo_escolha" rows="4" cols="50"></textarea>
    </p>

    <h4>Instalação:</h4>
    <p>
        a) Como você avaliaria a pontualidade da equipe de instalação?<br>
        <input type="radio" id="pontualidade_excelente" name="pontualidade_instalacao" value="Excelente">
        <label for="pontualidade_excelente">Excelente</label><br>

        <input type="radio" id="pontualidade_aceitavel" name="pontualidade_instalacao" value="Aceitável">
        <label for="pontualidade_aceitavel">Aceitável</label><br>

        <input type="radio" id="pontualidade_melhorias" name="pontualidade_instalacao" value="Precisa de Melhorias">
        <label for="pontualidade_melhorias">Precisa de Melhorias</label><br>

        <input type="radio" id="pontualidade_insatisfatorio" name="pontualidade_instalacao" value="Insatisfatório">
        <label for="pontualidade_insatisfatorio">Insatisfatório</label><br>
    </p>
    <p>
        b) A qualidade dos equipamentos e sistema atendeu às suas expectativas?<br>
        <input type="radio" id="qualidade_atende_expectativas_sim" name="qualidade_equipamentos" value="Sim">
        <label for="qualidade_atende_expectativas_sim">Sim</label><br>

        <input type="radio" id="qualidade_atende_expectativas_nao" name="qualidade_equipamentos" value="Não">
        <label for="qualidade_atende_expectativas_nao">Não</label><br>

        <input type="radio" id="qualidade_atende_expectativas_parcialmente" name="qualidade_equipamentos" value="Parcialmente">
        <label for="qualidade_atende_expectativas_parcialmente">Parcialmente</label><br>
    </p>

    <h4>Desempenho do Sistema:</h4>
    <p>
        Você está satisfeito com a quantidade de energia gerada pelo sistema?<br>
        <input type="radio" id="satisfeito_totalmente" name="satisfacao_energia" value="Sim, totalmente">
        <label for="satisfeito_totalmente">Sim, totalmente</label><br>

        <input type="radio" id="satisfeito_parcialmente" name="satisfacao_energia" value="Sim, parcialmente">
        <label for="satisfeito_parcialmente">Sim, parcialmente</label><br>

        <input type="radio" id="insatisfeito_porque" name="satisfacao_energia" value="Não, porque?">
        <label for="insatisfeito_porque">Não, porque?</label><br>
        <textarea id="insatisfeito_motivo" name="satisfacao_energia_motivo" rows="2" cols="50"></textarea>
    </p>
    <p>
        Como você classificaria o desempenho do sistema solar desde a instalação?<br>
        <input type="radio" id="desempenho_bom" name="desempenho_sistema" value="Bom">
        <label for="desempenho_bom">Bom</label><br>

        <input type="radio" id="desempenho_aceitavel" name="desempenho_sistema" value="Aceitável">
        <label for="desempenho_aceitavel">Aceitável</label><br>

        <input type="radio" id="desempenho_melhorias" name="desempenho_sistema" value="Precisa de Melhorias">
        <label for="desempenho_melhorias">Precisa de Melhorias</label><br>

        <input type="radio" id="desempenho_insatisfatorio" name="desempenho_sistema" value="Insatisfatório">
        <label for="desempenho_insatisfatorio">Insatisfatório</label><br>
    </p>
    <p>
        Você teve algum problema durante ou após a instalação? Se sim, como foi resolvido?<br>
        <input type="radio" id="problema_sim" name="problema_instalacao" value="Sim">
        <label for="problema_sim">Sim</label>
        <input type="text" id="problema_resolucao" name="problema_resolucao"><br>

        <input type="radio" id="problema_nao" name="problema_instalacao" value="Não">
        <label for="problema_nao">Não, porque?</label><br>
    </p>

    <h4>Suporte ao Cliente:</h4>
    <p>
        Como você avalia o suporte e atendimento de nossa empresa?<br>
        <input type="radio" id="suporte_bom" name="suporte_atendimento" value="Bom">
        <label for="suporte_bom">Bom</label><br>

        <input type="radio" id="suporte_aceitavel" name="suporte_atendimento" value="Aceitável">
        <label for="suporte_aceitavel">Aceitável</label><br>

        <input type="radio" id="suporte_melhorias" name="suporte_atendimento" value="Precisa de Melhorias">
        <label for="suporte_melhorias">Precisa de Melhorias</label><br>

        <input type="radio" id="suporte_insatisfatorio" name="suporte_atendimento" value="Insatisfatório">
        <label for="suporte_insatisfatorio">Insatisfatório</label><br>
    </p>
    <p>
        Você gostaria que entrássemos em contato para discutir mais detalhes sobre suas respostas?<br>
        <input type="radio" id="contato_sim" name="contato_futuro" value="Sim">
        <label for="contato_sim">Sim</label><br>

        <input type="radio" id="contato_nao" name="contato_futuro" value="Não">
        <label for="contato_nao">Não</label><br>
    </p>

    <h4>Comentários Adicionais:</h4>
    <p>
        <textarea id="comentarios_adicionais" name="comentarios_adicionais" rows="4" cols="50"></textarea>
    </p>

    <p>
        <button type="submit">Enviar</button>
    </p>
</form>

<p>Obrigado por dedicar seu tempo para nos fornecer seu feedback valioso! Se você optou por ser contatado, entraremos em contato em breve.</p>

</body>
</html>
