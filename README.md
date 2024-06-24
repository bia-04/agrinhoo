# agrinhoo
* {
    margin: 0;
    padding: 0;
}

.cabeçalho {
    background-color: rgb(39, 228, 187);
    color: rgba(0, 0, 0, 0.258);
    display: flex;
    justify-content: space-around;
    padding: 15px 0;
    font-family: 'Ubuntu', sans-serif;
    position: fixed;
    top: 0;
    width: 100%;
}

.cabeçalho-imagem {
    width: 5%;
    border-radius: 50%;
    padding: 5px 5px;
}

.foto-corpo {
    width: 30%;
    padding: 40px;
}

#Introdução {
    background-color: rgb(255, 255, 255);
    color: rgb(0, 0, 0);
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px 0;
    padding-top: 200px;
}

#Trabalho {
    background-color: rgb(255, 255, 255);
    color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px 0;
}

#Conclusão {
    background-color: rgb(255, 255, 255);
    color: rgb(0, 0, 0);
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px 0;
}

.cabeçalho-lista-item {
    display: inline-block;
    margin: 0 25px;
    font-size: 20px;
    padding: 15px 0px;
}

.texto-cabecalho {
    font-size: 20px;
    margin: 27px 0px;
}

.corpo-div-conteudo {
    font-family: 'Ubuntu', sans-serif;
    line-height: 1.8;
}

.roda-pé {
    background-color: rgb(39, 228, 187);
    justify-content: center;
    ;
}

.nome-aluno {
    padding: 0px 0px 20px 0px;
}

.roda-pé-texto {
    margin: 10px 0px 5px 0px;
    color: rgb(255, 255, 255);
}

li {
    float: left;
}

li {
    float: left;
}

li a,
.dropbtn {
    display: inline-block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover,
.dropdown:hover .dropbtn {
    background-color: rgb(0, 0, 0);
}

li.dropdown {
    display: inline-block;
    font-size: 20px;
    padding: 15px 0px;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: rgb(255, 77, 77);
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: center;
}

.dropdown-content a:hover {
    background-color: white;
}

.dropdown:hover .dropdown-content {
    display: block;

}

.final {
    text-align: center;
    color: white;
    line-height: 2.5;
}

.metade {
    display: flex;
    justify-content: center;
}
.formulario{
    width: 400px;
    padding: 30px;
    border:1px solid #000000;
}
.formulario p{
    width: 100%;
    font-size: 1.5em;
}
.field{
    width: 100%;
    margin: 15px 0;
}
input[type=text],
input[type=email],
textarea{
    width: 100%;
    padding-left: 10px;
    height: 30px;
    line-height: 30px;
    border-radius: 15px;
    border: 1px solid #000000;
    outline: none;
}
input#nao{
    margin-left: 30px;
}
textarea{
    line-height: 20px;
    padding: 10px;
    height: 90px;
    resize: none;
}
input[type=submit]{
    display: block;
    background-color: #56e4e9;
    height: 35px;
    border: none;
    outline: 0;
    cursor: pointer;
    width: 100px;
    margin: 0 auto;
    text-align: center;
    border-radius: 15px;
}