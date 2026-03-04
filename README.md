# DadosGerais.html
<!-- O básico de um site com requerimento de dados gerais-->
<form action="/pagina-processa-dados-do-form" method="post">

<fieldset>
<legend>Dados Gerais</legend>
<label for="Nome">Nome:</label>
<input type="text" minlength="3"
id:"nome" />
<label for="data_nascimento">Data de Nascimento:</label>
<input type="date"
id="data_nascimento"required />
<label for="cpf">CPF:</label>
<input type="cpf" minlength="11" 
id:"cpf" />

</fieldset>

<br>
<br>
<br>

<fieldset>

<label for="email">Email:
</label>
<input type="email" name="email"required>
<label for="tel">Telefone:
</label> <input type="tel"
name="telefone" required> 

</fieldset>

<br>
<br>
<br>

<fieldset>
<legend><i>Endereço</i></legend>

<label
for="tipo_endereco">Tipo:</label>
<select id="tipo_endereco">
<option
value="">Selecione</option>
<option value="">Rua</option>
<option value="">Estrada</option>
<option value="">Rodovia<ption>
<option value="">Outros</option>

</select>
<label
for="logradouro_endereco">Logradouro:</label>

<input type:"text"
id:"logradouro_endereco" />
<label
for="numero_endereco">Número:</label>

<input type="text" id:"numero endereco" />
<label
for="complemento_endereco">Complemento:</label>

<input type="text"
id="complemento_endereco" />
</fieldset>

<br>
<br>
<br>

<fieldset>

<legend>Fale Conosco</legend>
<label
for="msg">Mensagem:</label>
<textarea type="text" id:"msg">
</textarea>

</fieldset>

<fieldset>

<button type="submit">Enviar sua Mensagem</button>
<button type="reset">Limpar Formulário</button>

</fieldset>
</form>
