Inicialmente, crie um diretório em seu computador.

abra-o no VSCode. No VSCode, inicie
o terminal integrado e execute o comando:

python -m venv venv

ativar venv usando o comando:

venv\scripts\activate

instale o Django Rest Framework no terminal
utilizando o seguinte comando:

pip install djangorestframework

Aguarde a conclusão da instalação. execute o comando:

django-admin

criar o projeto (neste exemplo, nomeado como ‘projeto_api’, mas você
pode escolher outro nome), digite o comando correspondente.
django-admin startproject projeto_api .

utilize o seguinte comando:

django-admin startapp api

pronto.

9. Agora para configurar o projeto Django API Rest, siga estas etapas:
1. Acesse o arquivo `settings.py` dentro da pasta do projeto (`projeto_api`).
2. Localize a seção `INSTALLED_APPS`.
3. Adicione as seguintes linhas à lista:
○ 'rest_framewor'`
○ `ap'` (ou o nome do seu aplicativo)
