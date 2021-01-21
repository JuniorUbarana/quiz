# QUIZ
<style>
  :root{
    background-color: #1D2241;
    font-size: 62.5%;
  }

  body {
    background-image: url("./quiz_dev/quiz/static/assets/img/img-bg.jpg");
    background-position: top center;
    background-repeat: no-repeat;
    background-size: cover;
  }

</style>

<p style="font-size: 75%; font-style: italic; text-align: center">Criada durante a Jornada Rumo a Primeira Vaga organizada pela Python DevPro, com Renzo Nuccitelli</p>

### Aplicação desenvolvida em Python e Django para criação de questionários tipo Quiz com login do partipante e ranking dos melhores colocados na competição.
<br><br>
<p style="text-align:center;"><img style="border: 3px solid #fff" src="tela.gif"></p>
<br><br>
<strong>Tecnologias utilizadas</strong>: Python, Django, HTML, CSS, JS<br>
<strong>Versão</strong>: 0.1

### Passo a passo
1. Criar projeto php no pycharm;
2. Instalar o django através do comando:  <em>pip instal django</em>;
3. Criar projeto django com o comando: <em>django-admin startproject quiz_dev .</em>;
4. Verificar se o projeto foi criado corretamente executando o servidor por meio do comando: <em>php manage.py runserver</em>; 
5. No navegador, acesse o endereço <em>http://localhost:8000</em>. Caso tenha tudo dado certo, será exibida a página do Django;
6. Navegar para o diretório quiz_dev (<em>cd quiz_dev</em>) e em seguida digitar o comando <em>python ..\manage.py startapp quiz</em>;
7. Editar o arquivo settings.py e, no final da seção <strong>INSTALLED_APPS</strong>, incluir: <em>'quiz_dev.quiz'</em>;
8. Criar em .\quiz_dev\quiz o diretório static, incluindo os arquivos estáticos html, css e js, existentes no projeto;