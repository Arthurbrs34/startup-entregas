# startup-entregas
Ferramenta de entregas desenvolvida para a disciplina de Análise e Projeto de Software

# 📖 Documentação do Projeto Django

Este é um guia de configuração e desenvolvimento para o projeto Django. Siga os passos abaixo para começar.

---

### 📋 Sumário
* [Pré-requisitos](#pré-requisitos)
* [Guia de Instalação](#guia-de-instalação)
  * [Passo 1: Criar Ambiente Virtual](#passo-1-criar-ambiente-virtual)
  * [Passo 2: Instalar Dependências](#passo-2-instalar-dependências)
  * [Passo 3: Aplicar Migrações](#passo-3-aplicar-migrações)
  * [Passo 4: Rodar o Servidor](#passo-4-rodar-o-servidor)
* [Próximos Passos](#próximos-passos)
* [Banco de Dados](#banco-de-dados)

---

### Pré-requisitos
Certifique-se de que você tem o seguinte instalado na sua máquina:
* **Python:** Versão 3.10 ou superior.
* **pip:** O gerenciador de pacotes do Python.
* **Ambiente Virtual (venv):** Recomendado para isolar as dependências do projeto.

---

### Guia de Instalação

#### Passo 1: Criar Ambiente Virtual
Abra o terminal na pasta do projeto e execute os comandos de acordo com seu sistema operacional.

**Windows (PowerShell ou CMD)**
```bash
python -m venv venv
venv\Scripts\activate
````

**Linux / MacOS (Bash ou Zsh)**

```bash
python3 -m venv venv
source venv/bin/activate
```

---

#### Passo 2: Instalar Dependências

Com o ambiente virtual ativado, instale o Django:

```bash
pip install django
```

Se houver um arquivo `requirements.txt`, você pode instalar todas as dependências com:

```bash
pip install -r requirements.txt
```

Para gerar o `requirements.txt` (caso queira compartilhar o projeto):

```bash
pip freeze > requirements.txt
```

---

#### Passo 3: Aplicar Migrações (no momento o projeto esta sem banco de dados, ignorem por enquanto esse passo)

Configure o banco de dados e aplique as migrações iniciais:

```bash
python manage.py migrate
```

---

#### Passo 4: Rodar o Servidor

Execute o servidor de desenvolvimento:

**Windows**

```bash
python manage.py runserver
```

**Linux / MacOS**

```bash
python3 manage.py runserver
```

Abra o navegador e acesse:

[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

Se aparecer a tela padrão do Django, o servidor está funcionando ✅

---

### Banco de Dados

O projeto utiliza **SQLite** por padrão, configurado no arquivo `settings.py`:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / "db.sqlite3",
    }
}
```

Para criar tabelas no banco, defina seus **models** nos apps e execute:

```bash
python manage.py makemigrations
python manage.py migrate
```

Para visualizar e gerenciar dados, registre os models no admin (`admin.py`) e crie um superusuário:

```bash
python manage.py createsuperuser
```

Acesse o painel admin em [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin).

---

### Próximos Passos

* Criar apps no projeto:

```bash
python manage.py startapp nome_do_app
```

* Configurar rotas no `urls.py` de cada app.
* Criar models, aplicar migrações e registrar no admin.
* Desenvolver views, templates e interações com o banco.
* Testar funcionalidades no servidor local.

---

### Observações

* Sempre mantenha o ambiente virtual ativado antes de rodar comandos do Django.
* Use o `requirements.txt` para instalar dependências rapidamente em outras máquinas.
* O projeto está preparado para desenvolvimento local; para produção, recomenda-se configurar outro banco e servidor web.

```


```
