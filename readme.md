### Cuidar com a secrety key do django
- Criar arquivo .env no diretório do projeto
- Dentro do arquivo criar uma variável SECRET_KEY = ***** com a key removida do arquivo settings.py.
- Dentro do arquivo settings importar:
   * from pathlib import Path, os 
   * from dotenv import load_dotenv
   * SECRET_KEY = str(os.getenv('SECRET_KEY'))

### Iniciar servidor
python manage.py runserver

### variáveis de ambiente
pip install python-dotenv

### iniciar um projeto
pip install python-dotenv

### atualizar requisitos
pip freeze > requirements.txt

### git ignore
Marcar arquivos que devem ser enviados ao github
Gerador do gitignore referente ao django: https://www.toptal.com/developers/gitignore

### git
Enviar dados para o github: git push origin master

### startapp
Inicia uma nova função do projeto, o comando abaixo automaticamente cria uma nova pasta no diretório do projeto.
* python manage.py startapp galeria
Também é necessário ir até o arquivo settings em INSTALLED_APPS e adicionar o app recem criado. Depois disso rodar o server novamente.

### Trabalhando com o app
- views.py cuidar do que será exibido em cada página
- importar as bibliotecas necessárias por exemplo django.http

        funcao(request)
            retornar conteudo
