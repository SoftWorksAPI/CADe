<h1 align="center">CADê</h1>
   <!-- 
   <p align="center">
   <image alt="header-main" src=""/>
   </p>   
   -->
<hr>

  <p align="center">
     <a href ="#objetivo">Objetivo</a>  |
     <a href ="#visão-do-produto">Visão do produto</a>  |
     <a href ="#cronograma">Cronograma</a>  |
     <a href ="#backlog--produto">Backlog Produto</a>  |
     <a href ="#documentacao">Documentação</a>  |
     <a href ="#requisitos">Requisitos</a>  |
     <a href ="#tecnologias">Tecnologias</a>  |
     <a href ="#como-usar">Como usar</a>   |
     <a href ="#equipe">Equipe</a>
   </p>


<span id="objetivo">
   
## :dart: Objetivo 
<blockquote>
O projeto CADê tem como objetivo desenvolver uma aplicação web que automatize a elaboração de documentações técnicas CAD. A plataforma permitirá a geração automática de Memoriais de Cálculo e Especificações Técnicas a partir de plantas em formato CAD, utilizando agentes de inteligência artificial e um modelo de dados relacional complexo.
</blockquote>

<span id="visão-do-produto">
   
## :eye_speech_bubble: Visão do Produto   
<blockquote>   
O CADê busca ser uma plataforma web confiável e eficiente para a automação de documentos técnicos de infraestrutura. Ao interpretar plantas CAD e extrair parâmetros automaticamente, a solução elimina retrabalho manual, reduz erros humanos e padroniza a produção documental conforme as normas vigentes. A visão é entregar uma ferramenta que simplifique o fluxo de trabalho técnico, integrando modelagem de dados robusta, padrões de projeto modernos e interfaces intuitivas para os usuários finais.
</blockquote>

<span id="cronograma">  
   
## :spiral_calendar: Cronograma  
| FASE | INÍCIO | FIM |
| --- | --- | --- |
| Kick-off | 02/03/2026 | 06/03/2026 |
| Sprint 1 | 16/03/2026 | 05/04/2026 |
| Planning | 06/04/2026 | 10/04/2026 |
| Sprint 2 | 13/04/2026 | 03/05/2026 |
| Planning | 04/05/2026 | 08/05/2026 |
| Sprint 3 | 11/05/2026 | 31/05/2026 |
| Review   | 01/06/2026 | 05/06/2026 |

<span id="backlog--produto">
   
## :pushpin: Product Backlog

<details>
 <summary>Product Backlog</summary>
   
| ID    | Prioridade | Descrição | Pontos | Sprint |
|-------|------------|-----------|:------:|--------|
| US-01 | Alta       | Como projetista, quero que o sistema extraia automaticamente os materiais, dimensões e propriedades físicas dos arquivos para eliminar a digitação manual. | 9 | Sprint 1 |
| US-02 | Média      | Como administrador, quero gerenciar usuários, projetos e permissões para garantir a segurança dos dados. | 5 | Sprint 1 |
| US-03 | Baixa      | Como projetista, quero fazer o upload de arquivos CAD e realizar alterações nos dados do projeto para que o sistema reflita sempre o estado atual do meu trabalho. | 4 | Sprint 1 |
| US-04 | Alta       | Como projetista, quero que o sistema processe o memorial de cálculo vinculado ao projeto para validar a viabilidade técnica instantaneamente. | 8 | Sprint 2 |
| US-05 | Alta       | Como projetista, quero que o sistema cruze a lista de materiais extraída com um banco de preços atualizável para gerar o custo estimado de fabricação/montagem. | 7 | Sprint 2 |
| US-06 | Baixa      | Como administrador, quero gerenciar uma tabela de Variáveis Globais (ex: valor base dos materiais) para padronizar os cálculos. | 3 | Sprint 2 |
| US-07 | Alta       | Como projetista, quero gerar relatórios contendo resumo técnico, custos e gráficos para apresentação ao cliente. | 7 | Sprint 3 |
| US-08 | Média      | Como projetista, quero interagir com um chat de linguagem natural que leia os dados do meu projeto para tirar dúvidas rápidas. | 9 | Sprint 3 |


</details>

<span id="documentacao">
   
## 📚 Documentação do Projeto

<!--
<details>
 <summary>Documentação do Projeto</summary>
 -->
   
Este repositório contém a documentação organizada por sprints.  
Abaixo você encontra os links para cada documentação detalhada:

| Sprint | Período       | Documentação |
|--------|---------------|--------------|
| Sprint 1 | 16/03 - 05/04 | [Acessar Documentação](documentation/sprint1/sprint1doc.md) |
| Sprint 3 | 11/05 - 31/05 | [Acessar Documentação](documentation/sprint3/sprint3doc.md) |

<!--
## 🎥 Video Apresentação

<details>
 <summary>Sprints</summary>
## Sprint 1   
https://github.com/user-attachments/assets/
## Sprint 2
https://github.com/user-attachments/assets/
## Sprint 3
https://github.com/user-attachments/assets/
## Sprint 4
https://github.com/user-attachments/assets/
</details>
-->

   
<span id="requisitos">
   
## 🔎 Requisitos
### Requisitos Funcionais
- Upload e processamento de plantas em formato CAD.
- Geração automática de Memorial de Cálculo.
- Geração automática de Especificação Técnica conforme normas ABNT.
- Interface conversacional para solicitação de documentos em linguagem natural.
 
### Requisitos Não Funcionais
- Manual de Instalação (requisito Fatec – obrigatório, no Git).
- Manual do Usuário (requisito Fatec – obrigatório).
- Usabilidade (requisito Fatec – obrigatório).
- Privacidade de dados (requisito Fatec – obrigatório).
- Uso de Agentes de IA (requisito Fatec – obrigatório).
- Conversão de linguagem natural para chamada de funções, sem uso de API externa (requisito Fatec – obrigatório).
- Extração de parâmetros da mensagem do usuário, sem uso de API externa (requisito Fatec – obrigatório).
- Orquestração de chamadas de funções (requisito Fatec – obrigatório).
- Banco de dados relacional (requisito Fatec – obrigatório).
- Modelo de banco de dados normalizado até a 3ª Forma Normal (3FN) com MER documentado (requisito Fatec – obrigatório).
- Modelagem de dados documentada antes de cada sprint, incluindo modelos conceitual, lógico, físico e dicionário de dados (requisito Fatec – obrigatório).
- Implementação com NodeJS (requisito Fatec – obrigatório).
   
<span id="tecnologias">
   
## 🖥️Tecnologias:
   <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vue,react,javascript,typescript,nodejs,express,mysql,python,fastapi&perline=4">
   </a>
   
<span id="ferramentas">

## 🛠️ Ferramentas:
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,github,git&perline=4">
  </a>

<span id="como-usar">


## 🚀 Como Usar

### Pré-requisitos

- **Node.js 18+** instalado
- **Python 3.14+** instalado
- **uv** instalado (gerenciador de pacotes Python) — `pip install uv`
- **MySQL 8.0** instalado e rodando na porta 3306
- Chave de API do **OpenRouter** (para IA generativa)

---

### Passo 1 — Clonar o repositório

```bash
git clone https://github.com/SoftWorksAPI/CADe.git
cd CADe
```

---

### Passo 2 — Configurar o MySQL

Crie o banco de dados no MySQL:

```sql
CREATE DATABASE cadedb;
```

Ou utilize um cliente MySQL (Workbench, DBeaver, etc.) para criar o banco `cadedb`. O Node.js cria as tabelas automaticamente ao iniciar (`sequelize.sync`).

---

### Passo 3 — Configurar e iniciar o Backend Python

```bash
# Entrar no diretório
cd Python_Backend_CADe

# Instalar dependências com uv
uv sync

# Criar o arquivo .env na raiz do diretório
```

**Conteúdo do arquivo `Python_Backend_CADe/.env`:**
```env
OPENROUTER_API_KEY=sua_chave_aqui
OPENROUTER_MODEL=openai/gpt-oss-120b:free
NODE_BACKEND_URL=http://localhost:3000
INTERNAL_API_KEY=cade-internal-key-2026
CHROMA_PERSIST_PATH=./chroma_db
DEBUG=false
```

> Substitua `sua_chave_aqui` pela sua chave de API do OpenRouter.

**Iniciar o servidor:**

```bash
uv run uvicorn src.main:app --host 0.0.0.0 --port 8080 --reload
```

O Python estará disponível em `http://localhost:8080`.
Swagger interativo: `http://localhost:8080/docs`

---

### Passo 4 — Configurar e iniciar o Backend Node.js

Em um **novo terminal**:

```bash
# Entrar no diretório
cd Backend_CADe

# Instalar dependências
npm install

# Criar o arquivo .env na raiz do diretório
```

**Conteúdo do arquivo `Backend_CADe/.env`:**
```env
PORT=3000
DB_HOST=localhost
DB_PORT=3306
DB_NAME=cadedb
DB_USER=root
DB_PASSWORD=sua_senha_mysql
JWT_SECRET=cade-jwt-secret-2026
ADMIN_EMAIL=admin@admin.com
ADMIN_PASSWORD=admin123
PYTHON_API_URL=http://localhost:8080
INTERNAL_API_KEY=cade-internal-key-2026
```

> Substitua `sua_senha_mysql` pela senha do seu MySQL. Os valores de `ADMIN_EMAIL` e `ADMIN_PASSWORD` definem o usuário administrador padrão criado automaticamente.

**Iniciar o servidor:**

```bash
npm start
```

O Node.js estará disponível em `http://localhost:3000`.
Swagger: `http://localhost:3000/api-docs`

> Na primeira execução, o Node.js cria todas as tabelas no banco e o usuário admin padrão.

---

### Passo 5 — Configurar e iniciar o Frontend Vue.js

Em um **novo terminal**:

```bash
# Entrar no diretório
cd Vue_Frontend_CADe

# Instalar dependências
npm install

# Criar o arquivo .env na raiz do diretório
```

**Conteúdo do arquivo `Vue_Frontend_CADe/.env`:**
```env
VITE_API_URL=http://localhost:3000
```

**Iniciar o servidor de desenvolvimento:**

```bash
npm run dev
```

O frontend estará disponível em `http://localhost:5173`.

---

### Passo 6 — Acessar a aplicação

Abra o navegador em `http://localhost:5173` e faça login com as credenciais do admin padrão:

```
Email: admin@admin.com
Senha: admin123
```

</details>

<span id="equipe">
   
## 👥 Equipe:


   ### ![Static Badge](https://img.shields.io/badge/Scrum_Master-red) - Arthur Silva: 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://br.linkedin.com/in/arthur-sousa-3287391b1)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/Meowo2)

   ### ![Static Badge](https://img.shields.io/badge/Product_Owner-219ebc) - Igor Andrade : 
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/IgorAndrade2024)


   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Guilherme Henrique : 
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/Guih0412)


   ###  ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Tiago Bortoline : 
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/HelionLight)