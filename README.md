<!-- ======================= HEADER ======================= -->
<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:071A12,100:14532D&height=210&section=header&text=Gabriel%20Alves&fontSize=48&fontColor=F0FDF4&fontAlignY=38&animation=fadeIn"
    width="100%"
  />
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2800&pause=900&color=4ADE80&center=true&vCenter=true&width=850&lines=Software+Engineer;Backend+%7C+Python+%7C+Go;Distributed+Systems;AI+%26+Automation;Infrastructure+%26+Cloud;Building+systems+that+scale."
    alt="Typing SVG"
  />
</p>

<p align="center">
  <a href="https://github.com/xdevgabriel">
    <img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/gabriel-alves-ab8349244/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

<p align="center">
  <a href="#-sobre-mim">Sobre</a> •
  <a href="#-foco-de-engenharia">Foco</a> •
  <a href="#%EF%B8%8F-arquitetura">Arquitetura</a> •
  <a href="#-nanohub">NanoHub</a> •
  <a href="#-stack-tecnológica">Stack</a> •
  <a href="#-estatísticas">Stats</a>
</p>

<br>

<!-- ======================= ABOUT ======================= -->
<h2 align="center">👨‍💻 Sobre mim</h2>

<p align="center">
  Engenheiro de Software focado em <strong>sistemas backend, arquiteturas distribuídas,<br>
  automação e soluções com IA.</strong>
</p>

<p align="center">
  Gosto de transformar requisitos de negócio complexos em software
  <strong>confiável, escalável e fácil de manter</strong> — e de simplificar o que puder ser simplificado.
</p>

<br>
<p align="center">
  <img src="./assets/terminal.svg" width="900" alt="Gabriel Alves Engineering Profile" />
</p>

<br>

<!-- ======================= ENGINEERING FOCUS ======================= -->
<h2 align="center">🚀 Foco de Engenharia</h2>

<table align="center" width="100%">
<tr>
<td width="50%" valign="top">

### 🔧 Backend Engineering
- APIs REST e serviços de alta performance
- Autenticação & autorização
- Processamento assíncrono
- Lógica de negócio complexa
- Microsserviços & integrações

</td>
<td width="50%" valign="top">

### 🔄 Sistemas Distribuídos
- Filas de mensagens (Redis, RabbitMQ)
- Workers e processamento em background
- Arquitetura orientada a eventos
- Celery
- Workflows tolerantes a falha

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 IA & Automação
- Aplicações com LLMs
- Agentes de IA & tool calling
- Workflows inteligentes
- Automação de processos
- LangChain

</td>
<td width="50%" valign="top">

### ☁️ Infraestrutura
- Docker & Linux
- Nginx & reverse proxies
- Deploys containerizados
- Cloud infrastructure
- CI/CD

</td>
</tr>
</table>

<br>

<!-- ======================= ARCHITECTURE ======================= -->
<h2 align="center">🏗️ Arquitetura</h2>

<p align="center">Como penso a construção de sistemas — do client à camada de dados:</p>

```mermaid
%%{init: {'theme':'base', 'themeVariables': {
  'primaryColor':'#071A12',
  'primaryTextColor':'#F0FDF4',
  'primaryBorderColor':'#4ADE80',
  'lineColor':'#22C55E',
  'fontFamily':'JetBrains Mono, monospace'
}}}%%
flowchart TB
    C(["🖥️ Client"])
    A["⚙️ API / BFF"]
    S["🧩 Services"]
    AI["🤖 AI / LLM"]
    W["🔄 Workers"]
    MB[("📨 Message Broker\nRedis / RabbitMQ")]
    DB[("🗄️ Data Layer\nPostgreSQL")]

    C --> A
    A --> S
    A --> AI
    A --> W
    S --> MB
    AI --> MB
    W --> MB
    MB --> DB

    classDef node fill:#0D1117,stroke:#4ADE80,stroke-width:1.5px,color:#F0FDF4,rx:8,ry:8
    classDef store fill:#14532D,stroke:#86EFAC,stroke-width:1.5px,color:#F0FDF4,rx:8,ry:8
    class C,A,S,AI,W node
    class MB,DB store
```

<br>

<!-- ======================= WHAT I BUILD ======================= -->
<h2 align="center">💡 O que eu construo</h2>

<table align="center" width="100%">
<tr>
<td width="50%" valign="top">

**🧠 Sistemas com IA**
Software inteligente capaz de raciocinar, usar ferramentas e executar workflows automatizados.

**⚙️ Plataformas Backend**
APIs, serviços e arquiteturas desenhadas para confiabilidade, manutenibilidade e escala.

</td>
<td width="50%" valign="top">

**🔁 Infraestrutura de Automação**
Sistemas que transformam processos repetitivos em workflows automatizados.

**📡 Sistemas Distribuídos**
Workers, filas e arquiteturas assíncronas para processar grandes volumes de dados.

</td>
</tr>
</table>

<br>

<!-- ======================= CURRENT PROJECT ======================= -->
<h2 align="center">🚀 NanoHub</h2>

<p align="center">
  <strong>Infraestrutura de negócios autônoma, potencializada por IA.</strong>
</p>

<p align="center">
  O NanoHub é desenhado em torno de capacidades de IA especializadas que atuam em diferentes<br>
  áreas de uma empresa, combinando automação, inteligência e operações em um só sistema.
</p>

```mermaid
%%{init: {'theme':'base', 'themeVariables': {
  'primaryColor':'#071A12',
  'primaryTextColor':'#F0FDF4',
  'primaryBorderColor':'#4ADE80',
  'lineColor':'#22C55E',
  'fontFamily':'JetBrains Mono, monospace'
}}}%%
flowchart LR
    AG(["🧠 AI Agents"])
    B1["💼 Business Operations"]
    B2["🎧 Customer Service"]
    B3["📣 Marketing"]
    B4["📊 Intelligence"]
    B5["💰 Finance"]
    B6["⚙️ Automation"]

    AG --> B1
    AG --> B2
    AG --> B3
    AG --> B4
    AG --> B5
    AG --> B6

    classDef node fill:#0D1117,stroke:#4ADE80,stroke-width:1.5px,color:#F0FDF4,rx:8,ry:8
    classDef root fill:#14532D,stroke:#86EFAC,stroke-width:2px,color:#F0FDF4,rx:10,ry:10
    class B1,B2,B3,B4,B5,B6 node
    class AG root
```

<p align="center">
  <img src="https://img.shields.io/badge/AI-14532D?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Automation-14532D?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/SaaS-14532D?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Backend-14532D?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Distributed_Systems-14532D?style=flat-square&logoColor=white" />
</p>

<br>

<!-- ======================= PRINCIPLES ======================= -->
<h2 align="center">🧩 Princípios de Engenharia</h2>

```text
01. Simplicidade antes da complexidade.
02. Arquitetura explícita, sem abstração desnecessária.
03. Automatizar o que for repetitivo.
04. Projetar para a falha, não só para o sucesso.
05. Observabilidade faz parte da arquitetura.
06. Software deve evoluir sem se tornar frágil.
07. Performance importa, mas confiabilidade vem primeiro.
```

<br>

<!-- ======================= TECH STACK ======================= -->
<h2 align="center">💻 Stack Tecnológica</h2>

<p align="center"><img src="./assets/tech-stack.svg" width="900"></p>

<p align="center">
<img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/Go-0D1117?style=for-the-badge&logo=go&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/TypeScript-0D1117?style=for-the-badge&logo=typescript&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/JavaScript-0D1117?style=for-the-badge&logo=javascript&logoColor=4ADE80" />
<br>
<img src="https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/Next.js-0D1117?style=for-the-badge&logo=next.js&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/Node.js-0D1117?style=for-the-badge&logo=node.js&logoColor=4ADE80" />
<br>
<img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/MongoDB-0D1117?style=for-the-badge&logo=mongodb&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/Redis-0D1117?style=for-the-badge&logo=redis&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/RabbitMQ-0D1117?style=for-the-badge&logo=rabbitmq&logoColor=4ADE80" />
<br>
<img src="https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/Nginx-0D1117?style=for-the-badge&logo=nginx&logoColor=4ADE80" />
<img src="https://img.shields.io/badge/Google_Cloud-0D1117?style=for-the-badge&logo=googlecloud&logoColor=4ADE80" />
</p>

<br>


<h3 align="center">🐍 Gráfico de Contribuições</h3>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/xdevgabriel/xdevgabriel/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/xdevgabriel/xdevgabriel/output/github-snake.svg" />
    <img alt="github contribution snake" src="https://raw.githubusercontent.com/xdevgabriel/xdevgabriel/output/github-snake.svg" />
  </picture>
</p>

<br>

<!-- ======================= FOOTER ======================= -->
<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:14532D,50:071A12,100:020617&height=120&section=footer"
    width="100%"
  />
</p>

<p align="center">
  <strong>Building systems. Automating processes. Solving complex problems.</strong>
</p>

<p align="center">
  <code>gabriel@github:~$ ./build_future.sh</code>
</p>
