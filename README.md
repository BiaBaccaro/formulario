<h1><font color="blue"> Formulário de interação </font></h1>

<form action = "https://api.sheetmonkey.io/form/oujEo2B7xgoTgJfoEEvphd" method="post">
<p>
    <label> Digite o seu nome: </label>
    <input placeholder="Digite aqui" type="text" required="required" value= "Nome" name="Nome">
</p>
<p>
    <label> Digite o seu endereço: </label>
    <input placeholder="Digite aqui" type="text" required="required" value="Rua e número" name="Rua">
</p>
<p>
    <label> Digite o Bairro: </label>
    <input placeholder="Digite aqui" type="text" required="required" value="Bairro" name="Bairro">
</p>
<p> 
    <label> Digite a Cidade: </label>
    <input placeholder="Digite aqui" type="text" required="required" value="Santo André" name="Cidade">
</p>
<p>
    <label><font color="blue"> Deixe um comentário: </font></label><br>
    <textarea rows="15" cols="70" name="mensagem inserida pelo usuário" required="required" placeholder="Digite até 700 caracteres" maxlength="700"></textarea>
</p>
<p>
    <!--checkbox-->
    <label>Escolha o(s) modelos de trabalho:</label><br>
    <ol>
        <li><input type="checkbox" value="op1" name="vlr_presencial">Presencial</li>
        <li><input type="checkbox" value="op2" name="vlr_remoto">Remoto</li>
        <li><input type="checkbox" checked="checkbox" value="op3" name="vlr_híbrido">Híbrido</li>
    </ol>
</p>
    <button type= "submit">Enviar</button>
</form>
