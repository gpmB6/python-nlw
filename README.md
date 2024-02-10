<h1>Projeto final da Aula 3 de Python - NLW 10/02/2024</h1>

# :hammer: Funcionalidades do projeto
- App de geração de códigos de barra

<br><br>
Compilado de comandos executados ao longo do projeto, seja para instalação ou configurações,
<br><br>

$ pip3 install virtualenv
Cria a pasta .venv no projeto,
$ py -m venv .venv
Iniciar o ambiente virtual,
$ .\.venv\Scripts\activate

$ pip3 install pylint
Criação do .pylintrc que conterá automaticamente todas as regras do pylint para consulta,
$ pylint --generate-rcfile > .pylintrc

$ pip install pre-commit

Para gerar automaticamente o arquivo com as configurações,
$ .\.venv\Scripts\pip3 > requirements.txt

$ pip3 install Flask

$ pip3 install python-barcode

$ pip install pillow

Para atualizar o requirements.txt,
$ .\.venv\Scripts\pip3 freeze > requirements.txt

Exemplo de sintaxe para ignorar o pylint no commit (flag --no-verify),
$ git commit -m 'feat: exemplo' --no-verify

$ pip install cerberus

$ pip install -U pytest

Executar os arquivos *_test e exibir o status dos seus resultados (Passed/Failed):
$ pytest -s -v

Exemplo de sintaxe para executar um arquivo de teste em específico (comando + path):
$ pytest -s -v src/controllers/tag_creator_controller_test.py
