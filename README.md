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
     <!--<a href ="#como-usar">Como usar</a>   |-->
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
    <img src="https://skillicons.dev/icons?i=nextjs,react,javascript,typescript,nodejs,express,mysql,python,fastapi&perline=4">
   </a>
   
<span id="ferramentas">

## 🛠️ Ferramentas:
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,github,git&perline=4">
  </a>

  <!-- 
<span id="como-usar">


## 🚀 Como utilizar

Este projeto é composto por três serviços independentes, mas integrados: **AIService_Junipy**, **Backend_Junipy** e **Frontend_Junipy**. Siga os passos abaixo para configurar e executar todos os componentes corretamente.

<details>
 <summary>Como utilizar</summary>

## ⚙️ 0. Configurações e Pré-requisitos Gerais

Certifique-se de ter instalado:

* **Python 3.8+** e **pip**
* **Java/JDK** e **Maven (mvn)**
* **Node.js** e **npm**
* **Docker** (necessário para o banco de dados MongoDB)

---

## 📌 1. Configuração e Execução do Banco de Dados (MongoDB)

O Backend requer uma instância do MongoDB. Use o Docker para iniciar um contêiner rapidamente.

1.  **Crie e Inicie o Contêiner MongoDB:**
    ```bash
    docker run -d -p 27017:27017 --name junipymongo mongo:7
    ```

---

## 🧠 2. AIService — FastAPI (Python)

Este é o serviço de Inteligência Artificial.

### **Passos de Configuração**

1.  **Crie e Ative um Ambiente Virtual:**
    * **Linux/macOS:**
        ```bash
        python -m venv venv
        source venv/bin/activate
        ```
    * **Windows:**
        ```bash
        python -m venv venv
        venv\Scripts\activate
        ```

2.  **Instale as Dependências:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Configure o Modelo:**
    * Crie uma cópia do arquivo `.env.example` e renomeie-a para **`.env`** no diretório do projeto.
    * Preencha o arquivo `.env` com as chaves e configurações necessárias para a API de IA.

### **Execução**

* **Rode o Servidor FastAPI:**
    ```bash
    uvicorn main:app --reload
    ```
* **Acesso:** O serviço estará disponível em `http://localhost:8000`. A documentação **Swagger** pode ser acessada em `http://localhost:8000/docs`.

---

## ☕ 3. Backend — NutritionAgent (Spring Boot)

Este é o servidor de aplicação principal que se conecta ao Frontend, ao AIService e ao MongoDB.

### **Configuração**

1.  **Configure a Conexão com o AIService:**
    * No arquivo de configurações (geralmente `application.properties` ou `application.yml`, ou variáveis de ambiente), verifique e ajuste a URL base do AIService para `http://localhost:8000`.

### **Execução**

* **Rode o Projeto (com Maven):**
    ```bash
    mvn spring-boot:run
    ```
* **Acesso:** O Backend estará disponível em `http://localhost:8080`.

---

## 💻 4. Frontend — Junipy (Vue 3 + Vite)

Esta é a interface do usuário.

### **Passos de Configuração**

1.  **Instale as Dependências:**
    ```bash
    npm install
    ```
    > **Recomendação:** Use o **VSCode** com a extensão **Volar** para melhor experiência de desenvolvimento Vue.

### **Execução**

1.  **Rode em Modo Desenvolvimento:**
    ```bash
    npm run dev
    ```
* **Acesso:** A aplicação estará disponível em `http://localhost:5173`.

### **Build para Produção (Opcional)**

1.  **Gere os Arquivos Estáticos de Produção:**
    ```bash
    npm run build
    ```

---

## ✅ Resumo da Ordem de Inicialização

1.  **MongoDB** (Docker)
2.  **AIService** (Python)
3.  **Backend** (Java/Spring Boot)
4.  **Frontend** (Node/Vue)

   </details>
   -->

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