<h1 align="center">Olá, eu sou o Vitor 👋</h1>

<p align="center">
  <b>Desenvolvedor Python · Foco em Engenharia de Dados</b>
  <br>
  Pipelines ETL · SQL · Integração de dados · Docker
  <br>
  📍 Goiânia - GO, Brasil · 🌎 Disponível para trabalho 100% remoto
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vitrolagg"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:vitrolagg@gmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
</p>

---

## Sobre mim

Sou desenvolvedor Python e estou direcionando minha carreira para **engenharia de dados**. Nos meus trabalhos até aqui, cuidei da parte "invisível" dos sistemas: coletar dados de várias fontes, tratar, enfileirar, sincronizar e garantir que tudo chegue certo ao destino, rodando em containers em servidores Linux.

Venho da **automação industrial**. Antes do software, trabalhei com painéis elétricos, lógica de CLPs (Siemens/TIA Portal), parametrização de inversores de frequência e manutenção. Isso moldou meu jeito de trabalhar: diagnóstico metódico, documentação clara e sistemas que precisam funcionar de verdade, todo dia.

- 💼 Experiência mais recente: **Python Automation Software Developer** na A&D International (remoto)
- 🎓 Tecnólogo em Automação Industrial (SENAI Ítalo Bologna) e cursando **MBA em Big Data e Machine Learning** (SENAI)
- 📄 Coautor de artigo no **CEEL 2024 (UFU)** sobre um robô paralelo tipo delta com interface IHM
- 🛢️ Construindo agora o **[Litro](https://github.com/vitrolagg/litro)**, um pipeline de dados com o histórico de preços de combustíveis da ANP

---

## Tecnologias

**Linguagens e dados**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=databricks&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy">
</p>

**Ingestão e integração**
<p>
  <img src="https://img.shields.io/badge/Redis%20(filas)-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Web%20scraping-4B4B4B?style=flat-square&logo=python&logoColor=white" alt="Web scraping">
  <img src="https://img.shields.io/badge/APIs%20REST-000000?style=flat-square&logo=flask&logoColor=white" alt="APIs REST">
  <img src="https://img.shields.io/badge/Webhooks-2C3E50?style=flat-square" alt="Webhooks">
</p>

**Infraestrutura**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

<details>
<summary><b>Embarcados e automação industrial</b> (minha origem)</summary>
<br>
<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/Microcontroladores%20PIC-EE2223?style=flat-square" alt="Microcontroladores PIC">
  <img src="https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32">
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
  <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT">
  <img src="https://img.shields.io/badge/Modbus%20RTU-4B4B4B?style=flat-square" alt="Modbus RTU">
</p>
</details>

---

## Projeto em destaque

### 🛢️ [Litro](https://github.com/vitrolagg/litro) · *em desenvolvimento*

Pipeline de dados que transforma o histórico de preços de combustíveis publicado pela **ANP** (dados abertos) em uma base confiável e consultável. Hoje essa informação está espalhada em quase 200 CSVs, com formatos que mudaram ao longo de 20 anos. O objetivo é que uma pergunta como *"quanto a gasolina subiu em Goiânia nos últimos 5 anos?"* tenha resposta em uma consulta.

```mermaid
flowchart LR
    A[Site da ANP] -->|scraping + download| B[CSVs brutos]
    B -->|limpeza e padronização| C[(PostgreSQL)]
    C --> D[API de consulta]
    C --> E[Modelo de ML]
```

O andamento de cada etapa fica documentado no próprio repositório.

`Python` `Web scraping` `Pandas` `Jupyter` `PostgreSQL`

---

## Outros projetos

### 🌐 [gateway](https://github.com/vitrolagg/gateway)
Porta de entrada única para as aplicações hospedadas em um servidor, usando **Cloudflare Tunnel** e **Docker Compose**. Nenhuma porta fica exposta na máquina: cada aplicação publica só o seu container de entrada numa rede compartilhada, enquanto serviços internos e banco ficam isolados. Funciona igual em VPS ou servidor local.

`Docker` `Docker Compose` `Cloudflare Tunnel` `Nginx`

### 🤖 [DeltaController](https://github.com/vitrolagg/DeltaController)
Biblioteca Python para controlar um **robô paralelo tipo delta**, com cinemática inversa, cálculo de velocidade dos motores e comunicação **Modbus RTU** com drivers servo INVT DA180. Base do trabalho publicado no CEEL 2024 (UFU).

`Python` `Modbus RTU` `Cinemática` `Robótica`

---

## Trabalhos para clientes

A maior parte do que desenvolvo fica em repositórios privados de clientes, por isso não aparece nas estatísticas do GitHub. Alguns exemplos, sem detalhes confidenciais:

### 🔗 Integração de dados entre CRM e ferramentas de vendas
Webhooks recebem eventos de várias ferramentas de prospecção (automação de LinkedIn, sequências de e-mail, discador, enriquecimento e verificação de contatos) e os enfileiram no **Redis**. Workers dedicados, cada um em seu container, consomem as filas e sincronizam tudo com o CRM, que funciona como hub central dos dados. Inclui rotinas agendadas e scripts de manutenção e **migração de dados**.

`Python` `Redis` `Filas` `Docker` `Integração de APIs`

### 🔄 Coleta e sincronização de cotas de consórcio
Pipeline que roda em ciclos: **extrai** cotas contempladas de quatro fornecedores parceiros (scraping e APIs), **transforma** aplicando as regras de comissão e taxa de cada um e **carrega** o resultado no PostgreSQL, de onde é publicado no site do cliente. Um painel permite cadastrar cotas manuais e forçar uma sincronização imediata.

`Python` `Web scraping` `PostgreSQL` `Docker Compose`

### 🧮 Plataforma de cotas com busca combinatória
Catálogo de cotas sincronizado automaticamente, com busca em tempo real por combinações que chegam perto do crédito desejado com uma entrada menor, buscas salvas com alerta quando o estoque atende os parâmetros e métricas para a gestão.

`Python` `SQLAlchemy` `PostgreSQL` `Redis`

### 🏥 Painel de desempenho comercial para clínicas
Clínicas registram agendamentos e fechamentos, e o consultor responsável acompanha os indicadores de cada uma e o consolidado de todas, com perfis de acesso por função.

`Python` `PostgreSQL` `Métricas` `Docker`

---

## Estatísticas

<p align="center">
  <img height="165" src="https://streak-stats.demolab.com/?user=vitrolagg&hide_border=true&locale=en" alt="Contribuições no GitHub">
</p>

---

<p align="center">
  Buscando minha primeira oportunidade em <b>engenharia de dados</b>, remota, no Brasil ou no exterior. Vamos conversar! 🚀
</p>
