# PrintFlow — Sistema de Gestão e Automação para Serviços de Impressão 3D

## 🎯 Objetivo do Projeto
Desenvolver uma plataforma web (com suporte mobile ou responsiva) para ajudar makers e pequenas marcas de impressão 3D a gerenciarem seus pedidos, calcularem custos com precisão cirúrgica, controlarem o estoque de filamentos e acompanharem o fluxo de produção de forma automatizada.

## ⚙️ Módulos e Funcionalidades Principais
- **Calculadora Inteligente de Custos:**
Algoritmo que calcula o custo real de cada peça com base no peso do filamento (g), tempo de impressão (horas), consumo elétrico estimado da máquina, taxa de depreciação do equipamento e margem de lucro desejada.

- **Kanban de Produção (Fila de Impressão):**
Painel visual no estilo Trello/Kanban para gerenciar o status dos pedidos: Orçamento -> Aguardando Filamento -> Fatiando -> Imprindo -> Acabamento -> Pronto/Entregue.

- **Controle de Estoque de Matéria-Prima:**
Cadastro de bobinas de filamento (tipo: PLA, PETG, ABS; cor; peso restante). O sistema dá baixa automática no estoque conforme o peso calculado nos pedidos finalizados e emite alertas quando o material estiver acabando.

- **Catálogo de Clientes e Histórico de Pedidos:**
CRM básico para salvar dados de contato, preferências e histórico de peças impressas por cliente, facilitando reedições.

- **Portal do Cliente (Rastreio):**
Um link público onde o cliente final pode acompanhar em tempo real (ou por status atualizados) em qual etapa a impressão dele está.

## 🛠️ Tecnologias Utilizadas

#### **Backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

#### **Frontend**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

#### **Banco de Dados**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005E86?style=for-the-badge&logo=mysql&logoColor=white)

#### **Ferramentas e Versionamento**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Mermaid](https://img.shields.io/badge/Mermaid-FF3670?style=for-the-badge&logo=mermaid&logoColor=white)
