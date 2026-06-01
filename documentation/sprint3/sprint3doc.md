<h1 align="center">CADê Sprint 03</h1>

<hr>

  <p align="center">
     <a href ="#objetivo">Objetivo da Sprint</a>  |
     <a href ="#cronograma">Cronograma</a>  |
     <a href ="#backlog--sprint">Sprint Backlog</a>  |
     <a href ="#dor">DoR</a>  |
     <a href ="#dod">DoD</a>  |
     <a href ="#requisitos">Requisitos</a>  |
     <a href ="#tecnologias">Tecnologias</a>  |
     <a href ="#arquitetura">Arquitetura</a>  |
     <a href ="#como-usar">Como Usar</a>  |
     <a href ="#equipe">Equipe</a>
   </p>


<span id="objetivo">
   
## :dart: Objetivo da Sprint
<blockquote>
A Sprint 3 tem como objetivo consolidar a plataforma CADê entregando três pilares fundamentais: (1) a migração do frontend para Vue.js com design system completo e responsivo, (2) a integração completa entre os backends Node.js e Python, onde o Node atua como único consumidor da API Python em padrão proxy, e (3) a implementação do sistema RAG com ChromaDB para validação de conformidade com normas técnicas ABNT. Como principal entrega de valor, a sprint entrega o pipeline completo de geração de relatórios por IA — o usuário faz upload de um arquivo DXF, o sistema extrai dados deterministicamente, consulta normas técnicas via busca vetorial, gera Memorial Descritivo via LLM e produz relatórios profissionais em PDF, Markdown e XLSX.
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

<span id="backlog--sprint">
   
## :pushpin: Sprint Backlog
   
| ID    | Prioridade | Descrição | Pontos | Sprint | Meta da Sprint|
|-------|------------|-----------|:------:|--------|-----------|
| US-04 | Alta       | Como projetista, quero gerar relatórios profissionais (PDF, Markdown, XLSX) a partir do processamento IA do meu arquivo DXF. | 13 | Sprint 3 | ✔️ |
| US-06 | Alta       | Como administrador, quero gerenciar normas técnicas (upload, ativar/desativar) e sincronizá-las no banco vetorial para que a IA valide conformidade com NBRs. | 8 | Sprint 3 | ✔️ |
| US-07 | Alta       | Como projetista, quero que o sistema consulte normas técnicas automaticamente durante o processamento para gerar relatórios com validação normativa. | 8 | Sprint 3 | ✔️ |
| US-09 | Média      | Como administrador, quero monitorar o status da IA e do RAG (health check) para garantir que o sistema está operacional. | 3 | Sprint 3 | ✔️ |
| US-10 | Média      | Como usuário, quero visualizar detalhes e revisão de um relatório gerado pela IA. | 3 | Sprint 3 | ✔️ |
| US-11 | Baixa      | Como administrador, quero fazer upload manual de relatórios para associar documentos externos a um arquivo DXF. | 2 | Sprint 3 | ✔️ |

<span id="dor">
  
## 📝 DoR – Definition of Ready
 
- Objetivo da funcionalidade descrito de forma clara e alinhado com a proposta de automação de documentações técnicas
- Critérios de aceitação definidos de forma prática e mensurável
- Estimativa de esforço feita em conjunto pelo time
- Arquivos CAD de referência e normas ABNT aplicáveis identificados e validados pelo time
- Fluxo de interação do usuário desenhado
- Protótipo de interface definido
- Dependências técnicas (bibliotecas de leitura CAD, modelos de IA, banco vetorial) identificadas
- Modelagem de Banco de Dados elaborada e documentada (conceitual, lógico, físico e dicionário de dados)
 
<span id="dod">
 
## ✅ DoD – Definition of Done
 
- Código desenvolvido seguindo os padrões acordados pelo time
- Extração de dados e geração de documentos testadas com arquivos CAD reais ou simulados e validadas
- Testes de aceitação aprovados
- Documentação mínima pronta
- Protótipo de interface ou fluxo de interação atualizado de acordo com a implementação final
- Ambiente de execução configurado e instruções de setup disponíveis
- Problemas críticos e inconsistências nos documentos gerados corrigidos
- Todas as 32 rotas do backend auditadas e conformes com as regras de negócio

<span id="requisitos">
   
## 🔎 Requisitos
### Requisitos Funcionais
- Upload e processamento de plantas em formato CAD (DXF).
- Geração automática de Memorial de Cálculo via IA (LLM).
- Geração automática de Especificação Técnica conforme normas ABNT.
- Sistema RAG (Retrieval-Augmented Generation) para consulta de normas técnicas.
- Gerenciamento de normas técnicas (upload, ativar/desativar, sincronização vetorial).
- Geração de relatórios em múltiplos formatos (PDF, Markdown, XLSX).
- Monitoramento de saúde da IA e do sistema RAG.
- Upload manual de relatórios para associação a arquivos DXF.
- Controle de acesso baseado em papéis (Admin vs Usuário comum).
 
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
   
## 🖥️ Tecnologias

### Frontend
| Componente | Tecnologia | Versão |
|------------|-----------|--------|
| Framework | Vue 3 (Composition API) | ^3.5 |
| Build Tool | Vite | ^6.0 |
| Router | Vue Router 4 | ^4.5 |
| State Management | Pinia | ^2.3 |
| HTTP Client | Axios | ^1.7 |
| CSS Framework | Tailwind CSS v4 | ^4.0 |
| Markdown | marked | ^15.0 |
| Linguagem | TypeScript | ^5.7 |

### Backend Node.js
| Componente | Tecnologia | Versão |
|------------|-----------|--------|
| Runtime | Node.js | 18+ |
| Framework | Express | 5.2.1 |
| Banco de Dados | MySQL | 8.0 |
| ORM | Sequelize | 6.37.8 |
| Autenticação | JWT (jsonwebtoken) | - |
| Senhas | bcrypt | - |
| Upload | Multer (memória) | - |
| HTTP Client | axios | - |
| Container | Docker Compose | - |

### Backend Python
| Componente | Tecnologia | Versão |
|------------|-----------|--------|
| Linguagem | Python | >= 3.14 |
| Framework | FastAPI | 0.135.1 |
| Server | Uvicorn | 0.41.0 |
| Parsing DXF | ezdxf | >= 1.4.3 |
| Geometria | Shapely | >= 2.1.2 |
| Vetor | ChromaDB | - |
| IA Generativa | OpenRouter (GPT-OSS-120B) | - |
| PDF | reportlab | - |
| Gerenciador Pkg | uv | - |

### Ferramentas
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,github,git,docker&perline=4">
  </a>

<span id="arquitetura">

## 🏗️ Arquitetura

### Visão Geral do Sistema

```
┌─────────────────────────────────────────────────────────────┐
│                    FRONTEND (Vue.js + Vite)                 │
│  Upload DXF → Processar com IA → Relatórios → Gerenciar     │
│  Porta: 5173 (dev) / 80 (produção)                          │
└──────────────────────────┬──────────────────────────────────┘
                           │ HTTP (JWT)
┌──────────────────────────▼──────────────────────────────────┐
│              BACKEND NODE.JS (Express)                      │
│  Auth → Files → NormFiles → Reports → Processing (proxy)    │
│  Porta: 3000                                                │
└──────────────────────────┬──────────────────────────────────┘
                           │ HTTP (x-api-key)
┌──────────────────────────▼──────────────────────────────────┐
│            PYTHON BACKEND (FastAPI)                         │
│                                                             │
│  ┌─────────────┐   ┌─────────────┐   ┌─────────────────┐    │
│  │ Extração    │   │ Pipeline    │   │ RAG             │    │
│  │ DXF         │──▶│ IA (LLM)   │──▶│ ChromaDB        │    │
│  │ (ezdxf)     │   │ (OpenRouter)│   │ (Normas ABNT)   │    │
│  └─────────────┘   └──────┬──────┘   └─────────────────┘    │
│                           │                                 │
│                    ┌──────▼──────┐                          │
│                    │ Relatórios  │                          │
│                    │ MD/PDF/XLSX │                          │
│                    └─────────────┘                          │
│  Porta: 8080                                                │
└─────────────────────────────────────────────────────────────┘
```

### Pipeline de Processamento

```
Upload DXF
    │
    ▼
[Nó 1] Extração Determinística (ezdxf)
    │  - LINE, LWPOLYLINE, ARC, CIRCLE, ELLIPSE, SPLINE
    │  - HATCH, DIMENSION, LEADER, MLEADER
    │  - INSERT (blocos com geometria interna recursiva)
    │  - TEXT / MTEXT
    │  - Classificação por disciplina (Elétrico, Hidrossanitário, etc.)
    │  - Detecção de ambientes (Shapely polygonize)
    │
    ▼
[Nó 1.5] Busca RAG (ChromaDB) ← Normas técnicas indexadas
    │  - Montagem de query inteligente com dados extraídos
    │  - Busca por similaridade (top-5 chunks)
    │  - Contexto normativo injetado no prompt
    │
    ▼
[Nó 2] Análise via LLM (OpenRouter)
    │  - System prompt de engenheiro civil auditor
    │  - User prompt com dados extraídos + normas
    │  - Output: JSON estruturado (Memorial Descritivo)
    │
    ▼
[Nó 3] Parse e Validação do JSON
    │  - Tenta json.loads → regex markdown → regex genérico
    │  - Fallback: JSON mínimo com confiança "baixa"
    │
    ▼
[Nó 4] Montagem + Geração de Relatórios
    │  - Markdown (9 seções formatadas)
    │  - PDF (reportlab, A4 profissional)
    │  - Revisão por IA
    │
    ▼
Resposta ao cliente + Salvar no banco
```

### Comunicação entre Backends

O Node.js atua como **único consumidor** da API Python (padrão proxy). O frontend nunca acessa o Python diretamente.

| Rota Node.js | Ação | Rota Python consumida |
|-------------|------|-----------------------|
| `POST /processing/:id/process` | Pipeline completo | `POST /v1/extract/dxf` |
| `POST /processing/:id/relatorio/pdf` | Gerar PDF standalone | `POST /v1/relatorios/pdf` |
| `POST /processing/:id/relatorio/markdown` | Gerar MD standalone | `POST /v1/relatorios/markdown` |
| `GET /system/ai/health` | Health check IA | `GET /v1/ai/health` |
| `GET /system/rag/health` | Health check RAG | `GET /v1/rag/health` |
| `POST /system/rag/sync` | Sincronizar normas | `POST /v1/rag/sync` |

**Autenticação interna:** O Node.js envia `x-api-key` no header para autenticar-se junto ao Python.

### Controle de Acesso (RBAC)

| Funcionalidade | Usuário Comum | Admin |
|----------------|:-------------:|:-----:|
| Login | Sim | Sim |
| Dashboard | Sim | Sim (com status IA) |
| Upload DXF | Sim | Sim |
| Processar DXF | Sim (próprios) | Sim (todos) |
| Baixar relatórios | Sim (próprios) | Sim (todos) |
| Ver relatórios | Sim (próprios) | Sim (todos) |
| Normas Técnicas | Não | Sim |
| Sincronizar RAG | Não | Sim |
| Gerenciar usuários | Não | Sim |
| System Health | Não | Sim |
| Upload manual de relatório | Sim (próprios) | Sim (todos) |

### Modelos de Dados

#### User (`users`)

| Campo | Tipo | Detalhes |
|-------|------|----------|
| id | INTEGER | PK, auto-incremento |
| name | STRING | obrigatório |
| email | STRING | único, validação de email |
| passwordHash | STRING | obrigatório (bcrypt) |
| isAdmin | BOOLEAN | padrão: false |
| createdAt | DATE | automático |
| updatedAt | DATE | automático |

#### File (`files`)

| Campo | Tipo | Detalhes |
|-------|------|----------|
| id | INTEGER | PK, auto-incremento |
| originalName | STRING | nome original do arquivo |
| title | STRING | título editável |
| filename | STRING | nome gerado (timestamp + nome) |
| filePath | STRING | caminho no servidor |
| fileSize | INTEGER | tamanho em bytes |
| userId | INTEGER | FK -> users.id |
| description | TEXT | descrição opcional |
| markdownContent | TEXT(long) | conteúdo markdown gerado |
| createdAt | DATE | automático |
| updatedAt | DATE | automático |

#### NormFile (`norm_files`)

| Campo | Tipo | Detalhes |
|-------|------|----------|
| id | INTEGER | PK, auto-incremento |
| title | STRING | título da norma |
| category | STRING | categoria (Elétrica, Estrutural, etc.) |
| description | TEXT | descrição opcional |
| originalName | STRING | nome original do arquivo |
| filename | STRING | nome gerado no servidor |
| filePath | STRING | caminho no servidor |
| fileType | STRING | extensão (pdf, docx, xlsx) |
| fileSize | INTEGER | tamanho em bytes |
| ativo | BOOLEAN | ativo/inativo (padrão: true) |
| userId | INTEGER | FK -> users.id (quem fez upload) |
| createdAt | DATE | automático |
| updatedAt | DATE | automático |

#### Report (`reports`)

| Campo | Tipo | Detalhes |
|-------|------|----------|
| id | INTEGER | PK, auto-incremento |
| title | STRING | título do relatório |
| fileId | INTEGER | FK -> files.id |
| userId | INTEGER | FK -> users.id |
| fileType | STRING | tipo (json, md, pdf, xlsx) |
| filePath | STRING | caminho do arquivo no servidor |
| memorialDescritivo | TEXT(long) | memorial em JSON |
| dadosExtracao | TEXT(long) | dados de extração em JSON |
| confianca | STRING | nível de confiança (alta/média/baixa) |
| numInconsistencias | INTEGER | inconsistências detectadas |
| review | TEXT | revisão gerada pela IA |
| status | STRING | status individual (gerando/concluido/erro) |
| createdAt | DATE | automático |
| updatedAt | DATE | automático |

### Endpoints

#### Backend Node.js

**Rotas Públicas:**

| Método | Rota | Descrição |
|--------|------|-----------|
| GET | `/` | Health check |
| POST | `/users/login` | Autenticação, retorna JWT (7 dias) |

**Rotas de Usuário (`/users`):**

| Método | Rota | Descrição | Permissão |
|--------|------|-----------|-----------|
| POST | `/users/register` | Criar novo usuário | Admin |
| PATCH | `/users/update/:id` | Atualizar dados | Admin ou próprio |
| PATCH | `/users/change-password` | Alterar senha | Admin ou próprio |
| DELETE | `/users/delete/:userId` | Deletar usuário | Admin |
| GET | `/users/list` | Listar usuários (paginado) | Admin |
| GET | `/users/me` | Perfil do usuário logado | Autenticado |
| GET | `/users/:id` | Obter usuário por ID | Admin ou próprio |

**Rotas de Arquivo (`/files`):**

| Método | Rota | Descrição | Permissão |
|--------|------|-----------|-----------|
| POST | `/files/upload` | Upload de arquivo DXF | Autenticado |
| GET | `/files` | Listar arquivos (paginado) | Autenticado |
| GET | `/files/user/:userId` | Arquivos de um usuário | Admin ou próprio |
| GET | `/files/:id` | Obter arquivo por ID | Admin ou próprio |
| DELETE | `/files/:id` | Deletar arquivo | Admin ou próprio |
| PATCH | `/files/:id/markdown` | Adicionar markdown | Admin ou próprio |

**Rotas de Processamento (`/processing`):**

| Método | Rota | Descrição | Permissão |
|--------|------|-----------|-----------|
| POST | `/processing/:id/process` | Pipeline completo (DXF → IA → relatórios) | Autenticado |
| POST | `/processing/:id/relatorio/pdf` | Gerar PDF standalone | Autenticado |
| POST | `/processing/:id/relatorio/markdown` | Gerar Markdown standalone | Autenticado |
| POST | `/processing/:id/relatorio/xlsx` | Gerar XLSX standalone | Autenticado |

**Rotas de Relatórios (`/reports`):**

| Método | Rota | Descrição | Permissão |
|--------|------|-----------|-----------|
| POST | `/reports` | Criar relatório (JSON ou multipart) | Autenticado / API Key |
| GET | `/reports` | Listar relatórios | Autenticado |
| GET | `/reports/:id` | Obter relatório por ID | Autenticado |
| DELETE | `/reports/:id` | Deletar relatório | Autenticado |

**Rotas de Normas (`/norm-files`):**

| Método | Rota | Descrição | Permissão |
|--------|------|-----------|-----------|
| POST | `/norm-files/upload` | Upload de norma técnica | Admin |
| GET | `/norm-files` | Listar normas | Autenticado |
| GET | `/norm-files/:id` | Obter norma por ID | Autenticado |
| PATCH | `/norm-files/:id/toggle-ativo` | Toggle ativo/inativo | Admin |
| DELETE | `/norm-files/:id` | Deletar norma | Admin |
| GET | `/norm-files/internal/ativas` | Listar normas ativas | API Key |

**Rotas de Sistema (`/system`):**

| Método | Rota | Descrição | Permissão |
|--------|------|-----------|-----------|
| GET | `/system/ai/health` | Status da IA | Autenticado |
| GET | `/system/rag/health` | Status do RAG | Admin |
| POST | `/system/rag/sync` | Sincronizar normas no ChromaDB | Admin |

#### Backend Python

| Método | Rota | Descrição |
|--------|------|-----------|
| GET | `/` | Redireciona para Swagger |
| POST | `/v1/extract/dxf` | Pipeline completo (DXF → IA → MD + PDF) |
| POST | `/v1/extract/dxf/raw` | Extração pura sem IA |
| POST | `/v1/extract/dxf/prompt` | Retorna apenas o prompt de IA |
| POST | `/v1/rag/sync` | Sincroniza normas ativas → ChromaDB |
| GET | `/v1/rag/health` | Status do ChromaDB |
| DELETE | `/v1/rag/clear` | Limpa todo o ChromaDB |
| GET | `/v1/ai/health` | Testa se a IA está online |
| POST | `/v1/relatorios/pdf` | Gera PDF a partir de dados fornecidos |
| POST | `/v1/relatorios/markdown` | Gera Markdown a partir de dados fornecidos |
| GET | `/v1/reports/list` | Lista relatórios gerados |
| GET | `/v1/reports/download/{filename}` | Download de um relatório |

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

---

### Resumo dos serviços

| Serviço | Comando | Porta | URL |
|---------|---------|-------|-----|
| MySQL | Serviço local ou `net start mysql80` | 3306 | - |
| Python (FastAPI) | `uv run uvicorn src.main:app --host 0.0.0.0 --port 8080 --reload` | 8080 | http://localhost:8080/docs |
| Node.js (Express) | `node index.js` | 3000 | http://localhost:3000/api-docs |
| Vue.js (Vite) | `npm run dev` | 5173 | http://localhost:5173 |

> **Importante:** O MySQL deve estar rodando antes de iniciar o Node.js. O Python e o Node.js podem ser iniciados em qualquer ordem, mas ambos devem estar ativos para que o processamento de DXF funcione.

---

### Fluxo de Uso

#### 1. Login
```
Tela de login → POST /users/login → JWT salvo → Redirect para Dashboard
```

#### 2. Upload de arquivo DXF
```
Files → Arrasta/arquivo → POST /files/upload (multipart) → Arquivo aparece na lista
```

#### 3. Upload de normas técnicas (Admin)
```
NormFiles → Preenche título/categoria → Upload PDF/DOCX/XLSX
  → Botão "Sincronizar RAG" → POST /system/rag/sync
  → Normas indexadas no ChromaDB para busca vetorial
```

#### 4. Processar com IA
```
FileDetail → Botão "Processar com IA" → POST /processing/:id/process
  → Node.js envia DXF para Python
  → Python: extração determinística + RAG + LLM
  → Gera Memorial Descritivo + MD + PDF + Revisão
  → Node salva 4 Reports no banco
  → Resultado exibido na tela
```

#### 5. Baixar relatórios
```
FileDetail → Botão PDF/MD/XLSX → POST /processing/:id/relatorio/{tipo}
  → Download do arquivo gerado
```

#### 6. Gerar relatório standalone (após pipeline)
```
FileDetail → Botão "Gerar PDF" → POST /processing/:id/relatorio/pdf
  → Node busca Reports json do fileId
  → Envia dados para Python → IA gera novo conteúdo
  → Salva e retorna novo arquivo
```

#### 7. Ver detalhes do relatório
```
Reports → Click no relatório → ReportDetail
  → Visualiza revisão da IA, metadados, confiança
```

#### 8. Monitorar sistema (Admin)
```
System → Card IA (online/offline) + Card RAG (chunks, normas)
  → Botão "Sincronizar RAG" para atualizar base vetorial
```

### Formatos de Arquivo Suportados

| Tipo | Formatos | Uso |
|------|----------|-----|
| CAD | `.dxf` | Upload de plantas para processamento |
| Normas | `.pdf`, `.docx`, `.xlsx` | Upload de normas técnicas para RAG |
| Relatórios | `.md`, `.pdf`, `.xlsx` | Relatórios gerados pelo sistema |

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
