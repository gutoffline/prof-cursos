# Prof Cursos - Cursos Profissionalizantes
- [X] Criar o ambiente virtual
```
python -m venv .\venv\
```
- [X] Ativar  o embiente virtual
```
venv\Scripts\activate
```
> **obs**: se der erro no powershell utilize o comando abaixo para resolver a permissão `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`
- [X] Instalar o Django
```
python -m pip install django==3.2
```
- [X] Criar o projeto ProfCursos
```
django-admin.py startproject ProfCursos
```
- [X] Subir o servidor e testar o projeto
```
entrar na pasta do projeto
cd ProfCursos

executar o projeto no servidor
python manage.py runserver
```
- [X] Alterar o idioma do projeto para `pt-br`
- Abrir o arquivo `settings.py` e na linha 106 trocar `en-us` para `pt-br`
- [X] Alterar o timezone do projeto para `America/Sao_Paulo`
- Abrir o arquivo `settings.py` e na linha 108 trocar `UTC` para `America/Sao_Paulo`
- [X] Criar o app cursos
```
* preciso estar dentro da pasta do projeto (ProfCursos)
python manage.py startapp cursos
```
- [X] Registrar o app cursos
- no arquivo settings.py adicionar o app **cursos** na lista de apps
    ```python
    INSTALLED_APPS[
        ...
        'cursos',
    ]
    ```
- [ ] Configurar a rota inicial(index)
- [ ] Criar a view para a rota inicial
- [ ] Registrar a rota inicial
- [ ] Criar o arquivo index.html
- [ ] Integrar arquivos estáticos (CSS, JS, IMG)
- [ ] Inserir o bootstrap
- [ ] Utilizando links
- [ ] Criando o base.html
- [ ] Separando em partials
- [ ] Criando o banco de dados(MySQL/MariaDB)
- [ ] Instalando o conector do bando de dados MySQL
- [ ] Configurar a conexão com mysql
- [ ] Criando o modelo **cursos**
- [ ] Criando a migration (mapeamento)
- [ ] Realizando a migration
- [ ] Criando um usuário para o ambiente administrativo
- [ ] Registrando um modelo no admin
- [ ] Trazendo os dados do banco de dados
- [ ] Exibição das páginas individuais de cursos
- [ ] Realizando o deploy de nossa aplicação