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
marcar arquivos que devem ser enviados ao github
Gerador do gitignore referente ao django: https://www.toptal.com/developers/gitignore

### git
enviar dados para o github: git push origin master

### startapp
inicia uma nova função do projeto, o comando abaixo automaticamente cria uma nova pasta no diretório do projeto.
* python manage.py startapp galeria