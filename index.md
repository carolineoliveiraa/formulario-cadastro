<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Formulário de cadastro</title>
</head>
<body>
    <!--Div é divisão
    Id é único e Class pode ser múltiplos -->
    <div class="container">
        <div class="form-image">
           <img src="img/undraw_shopping_re_hdd9.svg">
        </div>
        <div class="form">
            <form action="#">
                <div class="form-header"> <!--Vai ter o titulo cadastre-se-->
                    <div class="title">
                        <h1>Cadastre-se</h1>
                        <div class="login-button">
                            <button><a href="#">Entrar</a></button>

                        </div>
                    </div>
                </div>
                <div class="input-group">
                    <div class="input-box">
                        <label for="firstname">Primeiro nome</label>
                        <input id="firstname" type="text" name="firstname" placeholder="Digite seu primeiro nome" required>
                        <!--Placeholder ajuda na experiencia do usuário pra entender como deve preencher ou onde preencher, como se fosse uma sombra dentro do formulário / o required quer dizer que essa parte do formulário é obrigatório o envio-->
                    </div>

                    <div class="input-box">
                        <label for="lastname">Sobrenome</label>
                        <input id="lastname" type="text" name="lastname" placeholder="Digite seu sobrenome" required>
                    </div>

                    <div class="input-box">
                        <label for="email">Email</label>
                        <input id="email" type="text" name="email" placeholder="Digite seu email" required>
                    </div>

                    <div class="input-box">
                        <label for="number">Celular</label>
                        <input id="number" type="tel" name="number" placeholder="(x) xxxx-xxxx" required>
                    </div>

                    <div class="input-box">
                        <label for="passowrd">Senha</label>
                        <input id="passowrd" type="password" name="password" placeholder="Digite sua senha" required>
                    </div>

                    <div class="input-box">
                        <label for="confirmpassword">Confirme sua senha</label>
                        <input id="confirmpassword" type="password" name="confirmpassword" placeholder="Digite sua senha" required>
                    </div>
                </div>

                <!--Aqui já se inicia outra div, para colocação no formulario sobre o genero-->

                <div class="gender-inputs">
                    <div class="gender-title">
                        <h6>Gênero</h6>
                    </div>

                    <!--div dentro de div sobre o genero-->

                    <div class="gender-group">
                        <div class="gender-input">
                            <input id="female" type="radio" name="gender">
                            <label for="female">Feminino</label>

                        </div>

                            <div class="gender-input">
                                <input id="male" type="radio" name="gender">
                                <label for="male">Masculino</label>
    
                            </div>

                                <div class="gender-input">
                                    <input id="others" type="radio" name="others">
                                    <label for="others">Outros</label>
        
                                </div>

                                <div class="gender-input">
                                    <input id="none" type="radio" name="none">
                                    <label for="none">Prefiro não dizer</label>

                                </div>

                    </div>
                </div>
                <!--Aqui pra o botão continuar existir, foi colocado fora da div de genero, sempre observar que para colocar outra div por fora, é antes do "form", sendo assim, não irá se perder-->
                <div class="continue-button">
                    <button><a href="#">Continuar</a></button>

                </div>
            </form>
        </div>
    </div>
</body>
</html>
