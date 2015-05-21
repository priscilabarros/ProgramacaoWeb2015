# ProgramacaoWeb2015
<!DOCTYPE html>

<!-- Exercicio 1 Programacao Web -->

<html>
    <head>
        <title> Minha primeira pagina </title>
        <meta charset = "UTF8" />
        <meta name = "author" content = "Priscila Barros"/>
        <meta http-equiv = "refresh" content = "600"/>
        <link rel="stylesheet" type="text/css" href="estilo.css">
    </head>

    <body>
        <h1> Este e um grande cabeçalho</h1>
        <h2>E este aqui e um pequeno cabeçalho</h2>

        <p>Aqui eu coloquei um paragrafo com algum texto aleatorio, e a seguir vou inserir um formulario dentro de uma tabela.
        Alem disso, aqui vai um link: <a href = "http://icomp.ufam.edu.br">http://icomp.ufam.edu.br</a> </p>

        <form>
            <table>
                <tr>
                    <td>Seu nome</td>
                    <td><input type="text" name="nome" id="nome"/></td>
                </tr>
                <tr>
                    <td>Seu sexo</td>
                    <td> <select name="sex" id="sex">
                            <option value="1">Masculino</option>
                            <option value="2">Feminino</option>
                         </select>
                    </td>
                </tr>
                <tr>
                    <td style="vertical-align:top">Seus comentarios</td>
                    <td valign="top" align="left">
                        <textarea name="comentarios" rows="15" cols="50"></textarea> <br />
                        <input type="submit" name="entrar" value="Entrar" id="entrar" />
                    </td>
                </tr>
            </table>
        </form>


    </body>
</html>
