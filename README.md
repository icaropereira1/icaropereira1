# 👋 Olá, eu sou o Ícaro Pereira!

## 💻 Sobre mim
Sou desenvolvedor na **[Vuca Solution](https://www.vucasolution.com.br)**, onde trabalho no ecossistema de software para gestão de restaurantes e bares (PDV, delivery, KDS, fiscal e financeiro) e nos sistemas internos da empresa (CRM, cobrança e implantação de clientes).

Sou estudante de **Engenharia de Computação na UFG**, com base em **Análise de Dados** e **Inteligência de Negócios (BI)**. Tenho experiência com **dashboards**, processos de **ETL** e automação com **Python**, inglês avançado e facilidade com ferramentas de **Machine Learning** e **Web Scraping**.

---

## 🚀 Na Vuca Solution

**CRM interno** · principal contribuidor desde abr/2026
- **Design system v2:** tokens CSS, componentes, styleguide e guia de migração; dezenas de telas migradas para o novo layout.
- **Cobrança modular:** migração de dados com backfill, dry-run e validação antes da virada; motor de descontos com regras de precedência; dashboard de cobrança com drill-down.
- **Implantação de clientes:** tela única guiada por máquina de estados modelada como dados, kanban do pipeline e provisionamento de instâncias com trava de concorrência e trilha de auditoria.
- **Suporte, CX e vendas:** escala de plantão, jornada de CX com drag-and-drop, métricas com gráficos e captação de leads com Google Places API.
- **Segurança:** controle de acesso por página, cookies seguros, segredos fora do código, correções de XSS e IDOR e adequação à LGPD.

**ERP / Retaguarda para restaurantes**
- **Módulo Catálogo, criado do zero:** produtos, categorias, opcionais e publicação no cardápio, com preço por canal, ações em massa, ordenação por arrastar, histórico com desfazer e níveis de permissão.
- **KDS 2.0:** fluxos de produção por etapas e estações de cozinha.
- **Fiscal:** wizard de configuração, gestão de NCM/CEST em massa, conciliação de NF-e de entrada e base de IBS/CBS da reforma tributária.
- **Relatórios** de RH (turnover e absenteísmo) e de estoque.
- **Performance em MySQL:** otimização de consultas (ex.: de 40 s para 95 ms), uso de réplica de leitura e eliminação de N+1.

**Cardápio IA** · FastAPI + GPT-4o Vision
- Extração de cardápios a partir de PDF e imagem com LLM de visão, com prompts determinísticos e regras anti-alucinação.
- Importação de cardápios do iFood, criação por canal de venda e sugestão de classificação fiscal (NCM/CEST).
- Processamento assíncrono em background para PDFs grandes, sessões de edição persistentes e transações assíncronas no MySQL.
- Construtor de cardápios de pizza: matriz de tamanhos × sabores × bordas expandida em produtos e grupos de opcionais.

**Automação e APIs**
- Scraper de boletos de ERP externo com **Playwright**, sessão persistente, gravação em MySQL e reconciliação via API, integrado ao CRM.
- Endpoints da API do app de delivery e pedido na mesa (JWT), com regras de preço validadas no servidor.
- Telemetria de módulos por unidade com migration no padrão expand/contract.

---

## 🧭 Práticas de Engenharia
- Análise de causa raiz validada com dados reais antes de corrigir.
- Migrations seguras: idempotentes, em fases, com dry-run e rollback.
- Concorrência em MySQL com `GET_LOCK` e leituras em réplica.
- Segurança de aplicações web: SQL injection, XSS, IDOR e controle de acesso.
- Testes automatizados (pytest, `node:test`, PHP em Docker).
- Code review via pull request e documentação técnica (specs e runbooks).
- Desenvolvimento assistido por IA com **Claude Code**.

---

## 🛠️ Tecnologias e Ferramentas

<p align="left">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white" alt="CSS" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />

  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge" alt="Playwright" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />

  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Google_Maps_API-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Google Maps API" />
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" alt="Chart.js" />
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code" />

  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />

  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

---

## 📌 Áreas de Interesse e Habilidades
- **Desenvolvimento Web Full-Stack:** sistemas SaaS multi-tenant, APIs e modelagem de banco de dados.
- **IA Aplicada:** LLMs de visão para extração de dados estruturados.
- **Análise de Dados & BI:** transformação de dados, ETL e criação de dashboards.
- **Machine Learning:** modelos preditivos e classificação.
- **Automação & Web Scraping:** `Playwright`, `Requests` e `BeautifulSoup`.
- **Suporte & Infra:** troubleshooting, Linux e gestão de ativos.

---

## 📌 Repositórios em destaque

<p align="left">
  <a href="https://github.com/icaropereira1/SistemaPedidosPRestaurante">
    <img src="https://img.shields.io/badge/🍽️ Sistema de Pedidos-181717?style=for-the-badge&logo=github&logoColor=white" alt="Sistema de Pedidos" />
  </a>
  <a href="https://github.com/icaropereira1/Projeto-de-Programacao-Orientada-a-Objetos">
    <img src="https://img.shields.io/badge/🅿️ Estacionamento (POO)-181717?style=for-the-badge&logo=github&logoColor=white" alt="Sistema de Estacionamento" />
  </a>
</p>

---

## 🌱 Atualmente Estudando e Aprimorando
- 📊 Aprofundamento em **Python para Data Science**
- 🤖 Algoritmos de **Machine Learning**
- 📈 Técnicas avançadas de **Power BI** e Visualização de Dados

---

## 📫 Onde me encontrar

<p align="left">
  <a href="mailto:xicaroestudos@gmail.com">
    <img src="https://img.shields.io/badge/Email-xicaroestudos@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/icaropereira1">
    <img src="https://img.shields.io/badge/LinkedIn-icaropereira1-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/icaropereira1">
    <img src="https://img.shields.io/badge/GitHub-icaropereira1-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>
