# teste <!DOCTYPE html>
<html>
	<head>
		<title>Cadastro</title>
		<meta charset="utf-8">
		<link rel="stylesheet" href="style.css">
	</head>
	<body>
		<main>
			<section>
				<form>
					<fieldset class="quadro">
						<legend>
							<strong>Cadastro</strong>
						</legend>
						Nome:<br>
						<input type="text" name="nome"><br><br>
						Idade:<br>
						<input type="text" name="idade"><br><br>
						Endereço:<br>
						<label>
							<input type="text" name="cidade" placeholder="Cidade"> 
							<input type="text" name="bairro" placeholder="Bairro"> 
							<input type="text" name="rua" placeholder="Rua"> 
							<input type="text" name="cep" placeholder="CEP"><br> <br>
						</label>
						Telefone:<br>
						<input type="text" name="Telefone"><br><br>
						Filiação:<br>
						<label>
							<input type="text" name="mãe" placeholder="Nome da mãe">
							<input type="text" name="pai" placeholder="Nome do pai"><br><br>
						</label>
						Gênero<br>
						<input type="radio" name="gênero" value="masculino"> Masculino
						<input type="radio" name="gênero" value="feminino"> Feminino<br><br>
						Religião:<br>
						<input type="text" name="Religião"><br><br>
						Hobbie<br>
						<input type="checkbox" name="hobbie" value="jogar">Jogar
						<input type="checkbox" name="hobbie" value="ler">Ler
						<input type="checkbox" name="hobbie" value="correr">Correr
						<input type="checkbox" name="hobbie" value="dançar">Dançar
						<input type="checkbox" name="hobbie" value="cozinhar">Cozinhar
						<input type="checkbox" name="hobbie" value="fotografar">Fotografar
						<input type="checkbox" name="hobbie" value="estudar">Estudar<br><br>
						E-mail<br>
						<input type="email" name="e-mail"><br>
						Senha<br>
						<input type="password" name="senha"><br><br>
						<button name="Enviar">
							<strong>Enviar</strong>
						</button>
					</fieldset>
				</form>
			</section>
		</main>
	</body>
</html>


body {
	background:#ffffff;
	color:#000000;
}
.quadro {
	background:#F5F5F5;
} 
