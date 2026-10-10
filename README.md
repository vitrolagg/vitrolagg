<h1 align="center">Olá, eu sou o Vitor 👋</h1>

<p align="center">
  <b>Desenvolvedor Python Backend</b> · APIs REST · Automação · Docker
  <br>
  📍 Goiânia - GO, Brasil · 🌎 Disponível para trabalho 100% remoto
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vitrolagg"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:vitrolagg@gmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
</p>

---

## Sobre mim

Sou desenvolvedor Python focado em **backend**: construo APIs RESTful, automatizo processos de ponta a ponta e coloco tudo para rodar em containers, em servidores VPS Linux ou servidores locais.

Venho da **automação industrial**. Antes do software, trabalhei com painéis elétricos, lógica de CLPs (Siemens/TIA Portal), parametrização de inversores de frequência e manutenção, e isso moldou meu jeito de trabalhar: diagnóstico metódico, documentação clara e sistemas que precisam funcionar de verdade.

- 💼 Hoje sou **Python Automation Software Developer** na A&D International (remoto)
- 🎓 Tecnólogo em Automação Industrial (SENAI Ítalo Bologna) e cursando **MBA em Big Data e Machine Learning** (SENAI)
- 📄 Coautor de artigo no **CEEL 2024 (UFU)** sobre um robô paralelo tipo delta com interface IHM
- 🌱 Interesses atuais: arquitetura de microsserviços, infraestrutura self-hosted e dados

---

## Tecnologias

**Backend**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy">
</p>

**Dados e filas**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
</p>

**Infraestrutura**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

**Frontend (complementar)**
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
</p>

**Embarcados e automação industrial**
<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/Microcontroladores%20PIC-EE2223?style=flat-square" alt="Microcontroladores PIC">
  <img src="https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32">
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
  <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT">
  <img src="https://img.shields.io/badge/Modbus%20RTU-4B4B4B?style=flat-square" alt="Modbus RTU">
</p>

---

## Projetos em destaque

### 🌐 [gateway](https://github.com/vitrolagg/gateway)
Porta de entrada única para as aplicações hospedadas em um servidor, usando **Cloudflare Tunnel** e **Docker Compose**. Nenhuma porta fica exposta na máquina: cada aplicação publica só o seu container de entrada numa rede compartilhada, enquanto API e banco ficam isolados na rede interna do projeto. Funciona igual em VPS ou servidor local.

`Docker` `Docker Compose` `Cloudflare Tunnel` `Nginx`

### 💇 [glowfy](https://github.com/vitrolagg/glowfy) · *em desenvolvimento*
Sistema web de gestão para salão de beleza: agenda sem encaixes duplicados, registro de atendimentos, cálculo automático de comissões, caixa, financeiro e tarefas da equipe, com perfis de acesso por função. O projeto está na fase de levantamento de requisitos e modelagem (entrevista com a cliente, documento de requisitos, modelo de domínio e de banco de dados).

`Engenharia de requisitos` `Modelagem de dados` `Python` `PostgreSQL`

### 🤖 [DeltaController](https://github.com/vitrolagg/DeltaController)
Biblioteca Python para controlar um **robô paralelo tipo delta**, com cinemática inversa, cálculo de velocidade dos motores e comunicação **Modbus RTU** com drivers servo INVT DA180. Base do trabalho publicado no CEEL 2024 (UFU).

`Python` `Modbus RTU` `Cinemática` `Robótica`

---

## Trabalhos para clientes

A maior parte do que desenvolvo fica em repositórios privados de clientes, o que também não entra nas estatísticas do GitHub. Alguns exemplos, sem detalhes confidenciais:

### 🔗 Integração de CRM com ferramentas de vendas
Webhooks em Flask recebem eventos de várias ferramentas de prospecção (automação de LinkedIn, sequências de e-mail, discador, enriquecimento e verificação de contatos) e os enfileiram no Redis. Workers dedicados, cada um em seu container, consomem as filas e sincronizam tudo com o CRM, que funciona como hub central. Inclui rotinas agendadas e scripts de manutenção e migração de dados.

`Python` `Flask` `Redis` `Docker` `Integração de APIs`

### 🔄 Sincronização de cotas de consórcio
Coletor que roda em ciclos, extrai cotas contempladas de quatro fornecedores parceiros, aplica as regras de comissão e taxa de cada um e publica o resultado no site do cliente. Uma API Flask com painel em React permite cadastrar cotas manuais e forçar uma sincronização imediata.

`Python` `Flask` `PostgreSQL` `React` `Docker Compose` `Web scraping`

### 🧮 Plataforma de cotas com busca combinatória
Sistema web para vendedores e revendedores: catálogo de cotas sincronizado automaticamente, busca em tempo real por combinações de cotas que chegam perto do crédito desejado com uma entrada menor, buscas salvas com alerta quando o estoque atende os parâmetros, cadastro por convite e métricas para a gestão.

`Python` `Flask` `SQLAlchemy` `PostgreSQL` `Redis` `React`

### 🏥 Painel de desempenho comercial para clínicas
Sistema em que clínicas registram agendamentos e fechamentos e o consultor responsável acompanha o desempenho de cada uma e o consolidado de todas, com perfis de acesso para administrador, proprietário e secretária.

`Python` `Flask` `PostgreSQL` `React` `Docker`

---

## Estatísticas

<p align="center">
  <img height="165" src="https://streak-stats.demolab.com/?user=vitrolagg&hide_border=true&locale=en" alt="Contribuições no GitHub">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vitrolagg&layout=compact&hide_border=true" alt="Linguagens mais usadas">
</p>

**Tempo de programação na última semana** (inclui projetos privados, via [WakaTime](https://wakatime.com))

<!--START_SECTION:waka-->

```txt
Total Time: 0 secs

No activity tracked
```

<!--END_SECTION:waka-->

---

<p align="center">
  Aberto a oportunidades remotas no Brasil e no exterior. Vamos conversar! 🚀
</p>
