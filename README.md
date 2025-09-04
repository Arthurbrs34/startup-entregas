# 🚀 Startup Entregas  
📦 Ferramenta de entregas desenvolvida para a disciplina de **Análise e Projeto de Software**  

---

## 🔧 Pré-requisitos  
Antes de começar, certifique-se de ter instalado:  
- 🐍 **Python 3.10+**  
- 📦 **pip** (gerenciador de pacotes)  
- 🛠️ **venv** (ambiente virtual recomendado)  

---

## ⚙️ Guia de Instalação  

### 1️⃣ Criar ambiente virtual  

**Windows**  
```bash
python -m venv venv
venv\Scripts\activate
Linux / MacOS

python3 -m venv venv
source venv/bin/activate
2️⃣ Instalar dependências

pip install -r requirements.txt
3️⃣ Rodar o servidor
Windows

python manage.py runserver
Linux / MacOS

python3 manage.py runserver
📍 Acesse no navegador: http://127.0.0.1:8000/ ✅

📌 Entrega 01 (02/09)
### ✅ Histórias de Usuário  

- **US01 – Cadastro de usuário**  
  Como um usuário, eu quero me cadastrar informando meu usuário ou e-mail e a senha para ter acesso ao sistema e usar os recursos.  
  🔥 Prioridade: **ALTA**  

- **US02 – Login no sistema**  
  Como usuário e tendo cadastro, quero fazer login com usuário ou e-mail e senha para acessar as funcionalidades.  
  🔥 Prioridade: **ALTA**  

- **US03 – Criar pedido de entrega**  
  Como cliente e usuário, quero criar um pedido informando item e endereço para ter uma entrega rápida.  
  🔥 Prioridade: **ALTA**  

- **US04 – Listar os meus pedidos**  
  Como cliente e usuário, quero visualizar todos os meus pedidos de entrega e acompanhar eles.  
  ⚡ Prioridade: **MÉDIA**  

- **US05 – Ver os pedidos disponíveis**  
  Como entregador, quero visualizar os pedidos que ainda estão pendentes para escolher qual eu quero entregar.  
  ⚡ Prioridade: **MÉDIA**  

- **US06 – Aceitar o pedido**  
  Como entregador, eu quero aceitar um pedido para fazer a entrega.  
  ⚡ Prioridade: **MÉDIA**  

- **US07 – Marcar o pedido como entregue**  
  Como entregador, eu quero finalizar uma entrega para encerrar a minha tarefa.  
  ⚡ Prioridade: **MÉDIA**  

- **US08 – Gerenciar os usuários**  
  Como gerente, quero ver todos os usuários para acompanhar quem está usando o sistema no momento.  
  🟢 Prioridade: **BAIXA**  

- **US09 – Excluir pedido (Gerente)**  
  Como gerente, quero excluir pedidos incorretos, inválidos etc., mantendo o sistema em ordem.  
  🟢 Prioridade: **BAIXA**  

- **US10 – Logs de alteração**  
  Como gerente, quero ver os históricos de alterações para acompanhar as ações realizadas.  
  🟢 Prioridade: **BAIXA**  

---

### 📊 Priorização das Entregas  
- **Alta**: US01, US02, US03  
- **Média**: US04, US05, US06, US07  
- **Baixa**: US08, US09, US10  



📊 Priorização das Entregas
Alta: US01, US02, US03

Média: US04, US05, US06, US07

Baixa: US08, US09, US10

👥 Papéis de Cada Integrante
🖥️ Back-end: Arthur Angelo, Maria Clara, Arthur Holanda

🎨 Front-end: João Lucas, Gabriella Theóphilo, Caio Vinicius

📌 P.O / Scrum Master: Davi

🧪 Tester: Leonardo

✨ Observações
Ative sempre o ambiente virtual antes de rodar comandos.

Use o requirements.txt para instalar dependências em outras máquinas.

O projeto está configurado para desenvolvimento local; para produção, recomenda-se banco e servidor adequados.
