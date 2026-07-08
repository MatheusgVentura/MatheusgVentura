<h1 align="center">Matheus Ventura</h1>

<p align="center">
  <b>Estudante de Engenharia de Software · Backend (Python) & Cibersegurança (Blue Team / SOC)</b><br>
  <i>Detecto ameaças, construo sistemas e entendo ataques por dentro.</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/matheus-ventura-a336992b2">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://tryhackme.com/p/skykrakk">
    <img src="https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe">
  </a>
  <a href="mailto:matheusgventura10@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

## Sobre mim

Estudante de Engenharia de Software (6º semestre) no IDP, em Brasília. Trabalho em duas frentes que se complementam:

- 🛡️ **Blue Team / SOC** — análise de logs, triagem de alertas e investigação de incidentes com SIEM (Wazuh como principal, Splunk em laboratório). 75+ salas concluídas no TryHackMe.
- ⚙️ **Backend em Python** — APIs REST com Django e Django REST Framework, autenticação JWT, testes automatizados e containerização com Docker.
- 🔍 **AppSec & Bug Bounty** — OWASP Top 10, testes de IDOR/BOLA e information disclosure em APIs, com ferramentas próprias de reconhecimento.

Busco estágio em **cibersegurança (Blue Team/SOC)** ou **desenvolvimento backend**.

---

## Stack & Ferramentas

**Linguagens**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & APIs**
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Segurança & Blue Team**
![Wazuh](https://img.shields.io/badge/Wazuh-3268C7?style=flat-square&logo=wazuh&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Caido](https://img.shields.io/badge/Caido-FF6A00?style=flat-square&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square&logo=nmap&logoColor=white)

**Infra & Dev**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Projetos em destaque

### 🔐 Secure Auth API
API REST de autenticação em Django REST Framework com 8 endpoints: JWT (access/refresh), blacklist de token no logout, troca e recuperação de senha e endpoints protegidos por permissão. Testes com pytest (meta de 90% de cobertura), configuração por ambiente, Docker e documentação OpenAPI (Swagger/ReDoc).
`Python 3.12` · `Django 5.2` · `DRF` · `Simple JWT` · `pytest` · `Docker`
➡️ **[Ver repositório](https://github.com/MatheusgVentura/secure-auth-api)**

### 🏆 Bolão da Copa
Web App PWA full-stack em produção, com backend em Supabase/PostgreSQL. Modelagem do banco com schema SQL e migrações, cálculo de pontuação e ranking em tempo real (Supabase Realtime), e sincronização automática dos 104 jogos da Copa 2026 a cada 5 minutos. Em uso por participantes reais.
`JavaScript` · `Supabase` · `PostgreSQL` · `PWA`
➡️ **[Ver repositório](https://github.com/MatheusgVentura/Bolao_Copa)**

### 🧪 WebSecLab
Laboratório de segurança web que reproduz as 10 categorias do OWASP Top 10 em versões vulnerável e segura, conectando a perspectiva ofensiva à de detecção e mitigação. Cada cenário documentado com exploração e correção.
`Python` · `Django` · `Docker` · `OWASP Top 10`
➡️ **[Ver repositório](https://github.com/MatheusgVentura/WebSecLab)** <!-- TODO: substituir pelo link real do WebSecLab -->

### 🔐 Projeto Institucional — IDP × União dos Escoteiros do Brasil
Fluxo centralizado de autenticação e controle de acesso: Supabase Auth com validação de tokens JWT/Bearer, login e renovação de sessão via refresh token, e RBAC por perfil de usuário (Escoteiro e Gestor). Automações de integração com n8n e ambiente padronizado com Docker.
`Supabase Auth` · `JWT` · `RBAC` · `n8n` · `Docker`
<sub>Projeto institucional — repositório privado.</sub>

---

## Trilha Blue Team / SOC

- **TryHackMe** — 75+ salas concluídas · Cyber Security 101 (concluído) · SOC Level 1 (em andamento)
- Labs de análise de logs, triagem de alertas, phishing e investigação de incidentes com **Wazuh** e **Splunk**
- **Google Cybersecurity Professional Certificate** (Coursera) — em andamento
- Participação em programas públicos de **bug bounty** (HackerOne)

---

## Estatísticas

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MatheusgVentura&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MatheusgVentura&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165">
</p>

---

<sub>⚠️ Todo o conteúdo relacionado a segurança ofensiva neste perfil é destinado exclusivamente a fins educacionais e éticos, em ambientes autorizados.</sub>
