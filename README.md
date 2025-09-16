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
🖥️ Back-end: Arthur Angelo, Maria Clara, Arthur Holanda e Leonardo Harlam

🎨 Front-end: João Lucas, Gabriella Theóphilo, Caio Vinicius

📌 P.O / Scrum Master: Davi

🧪 Tester: Aluisio

✨ Observações
Ative sempre o ambiente virtual antes de rodar comandos.

Use o requirements.txt para instalar dependências em outras máquinas.

O projeto está configurado para desenvolvimento local; para produção, recomenda-se banco e servidor adequados.


👤Storyboards atuais (podem sofrer alteração)
 
 
[US01: Cadastro de usuário]
1. Usuário acessa a página de cadastro.
2. Preenche nome, e-mail/usuário e senha.
3. Clica no botão “Cadastrar”.
4.  O sistema valida os dados e cria a conta.
5. Usuário recebe mensagem de sucesso e é redirecionado para login.
 
[US02: Login no sistema]
1. Usuário acessa a página de login.
2. Coloca e-mail/usuário e senha.
3. Clica no botão “Entrar”.
4. Sistema verifica as informações
5. Usuário é redirecionado para o painel principal.
 
[US03: Criar pedido de entrega]
1. Usuário logado acessa a página “Criar Pedido”.
2. Preenche informações do item e endereço de entrega.
3. Clica em “Enviar Pedido”.
4. Sistema registra o pedido e mostra confirmação.
5. Pedido fica disponível para o cliente e para os entregadores.
 
[US04: Listar meus pedidos]
1. Usuário acessa a página “Meus Pedidos”.
2. Sistema lista todos os pedidos do usuário com status atual.
3. O usuário pode acompanhar a entrega.
 
[US05: Ver pedidos disponíveis (Entregador)]
1. Entregador acessa a página “Pedidos Disponíveis”.
2. Sistema mostra todos os pedidos pendentes.
3. Entregador escolhe um pedido para aceitar.
 
[US06: Aceitar pedido]
1. Entregador clica no pedido escolhido.
2. Clica em “Aceitar Pedido”.
3. Sistema atualiza status do pedido para “Em andamento” e atribui ao entregador.
 
[US07: Marcar pedido como entregue]
1. Entregador acessa pedidos em andamento.
2. Clica em “Marcar como Entregue”.
3. Sistema atualiza status para “Entregue” e realiza uma notificação ao cliente.
 
[US08: Gerenciar usuários (Gerente)]
1. Gerente acessa a página “Gerenciar Usuários”.
2. Sistema lista todos os usuários ativos.
3. Gerente pode ver detalhes e status de cada usuário.
 
[US09: Excluir pedido (Gerente)]
1. Gerente visualiza a lista de pedidos.
2. Seleciona um pedido inválido.
3. Clica em “Excluir”.
4. Sistema remove o pedido e atualiza a lista.
 
[US10: Logs de alteração (Gerente)]
1. Gerente acessa a página “Logs”.
2. Sistema exibe histórico de ações realizadas por usuários.
3. Gerente pode filtrar ou buscar alterações específicas.
