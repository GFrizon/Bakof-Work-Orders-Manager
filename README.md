# Bakof-Work-Orders-Manager
# Bakof Work Orders Manager  
📌 Sistema corporativo de gestão de Ordens de Serviço — implantado e utilizado em produção pela Bakof Tec

Este projeto foi desenvolvido sob demanda para a **Bakof Tec**, com o objetivo de melhorar o fluxo operacional, registro, acompanhamento e análise das ordens de serviço.

> Esta é uma versão de portfólio — sem credenciais reais e com configurações genéricas.

---

## 🔥 Objetivo do sistema

Organizar de forma clara e centralizada todos os pedidos de serviço, permitindo:

✔ rastreabilidade  
✔ priorização  
✔ responsabilidade definida  
✔ histórico consultável  
✔ indicadores de desempenho  

Além disso, reduz comunicação perdida por WhatsApp, bilhetes ou verbal.

---

## ✨ Funcionalidades principais

- Login com perfis (Administrador, Operador e Solicitante)
- Cadastro de ordens de serviço
- Workflow: Em Aberto → Execução → Concluída
- Prioridade: Normal / Urgente
- Fila com filtros e destaques visuais (verde, amarelo, vermelho)
- Atribuição a executores e ajudantes
- Painel de conclusão e arquivamento mensal
- Exportação para Excel
- Gráficos com Plotly
- Gestão de colaboradores (inativação com validação de vínculo)
- Alteração de senha com política forte
- Migração automática SHA → bcrypt de senhas antigas

---

## 🧠 Tecnologias utilizadas

**Backend & UI**  
- Python  
- Streamlit  

**Banco / Persistência**  
- MySQL  
- mysql-connector (connection pooling)

**Visualização e relatórios**  
- Plotly  
- Pandas  
- Styled DataFrames

**Autenticação & segurança**  
- bcrypt (hash robusto)

**Deploy / Infraestrutura**  
- Render / AlwaysData  
- Deploy contínuo por GitHub

## 📸 Screenshots da aplicação

### 🔐 Login
![Tela de Login](prints/LOGIN.png)

### 🏭 Area Administrativa
![Dashboard Operacional](prints/ADM.png)

### 📝 Solicitação de OS
![Solicitação de OS](prints/SOLICI.png)

### 📤 Aprovação / Análise
![Aprovação Administrativa](prints/APROV.png)

### 🔧 Ações Operadores (Iniciar / Encerrar OS + Colaboradores)
![Gestão e Execução](prints/COLAB.png)

### 📦 Tela de Concluídas / Arquivamento
![Concluídas](prints/CONCLUIDAS.png)

### 📊 Fila de Trabalho (Visão Geral)
![Fila de Trabalho](prints/FILA.png)

### 🔍 Zoom interpretativo da Fila
![Fila — Zoom](prints/FILA ZOOM.png)

### 👥 Perspectiva do operador
![Fila Operadores](prints/operadores.png)

 

---
