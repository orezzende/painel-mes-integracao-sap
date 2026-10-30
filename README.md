<p align="center">
  <img src="docs/banner.png" alt="Painel MES · Integração Chão de Fábrica com SAP" width="100%">
</p>

<h1 align="center">Painel MES · Integração Chão de Fábrica com SAP</h1>

<p align="center">Simulador de ponte entre o chão de fábrica e o SAP (módulos <b>PP</b>, <b>PM</b> e <b>QM</b>). Roda 100% no navegador, com dados simulados e sem conexão com um SAP real.</p>

<p align="center">
  <a href="https://orezzende.github.io/painel-mes-integracao-sap/"><img src="https://img.shields.io/badge/▶%20Ver%20demo%20online-2dd4bf?style=for-the-badge&labelColor=0b1220" alt="Demo online"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript"> <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white" alt="Chart.js">
</p>

---

## 📌 Sobre

Projeto de estudo que mostra como eventos de produção coletados de PLCs podem alimentar processos do SAP: confirmações de produção (PP), notificações de manutenção (PM) e inspeções de qualidade (QM). Inclui falhas simuladas de RFC/IDoc e reenvio de mensagens, como acontece numa integração real.

## 🖼️ Demonstração

<p align="center">
  <img src="docs/screenshot.png" alt="Visão geral da linha com cenário de exemplo carregado" width="100%">
  <br><sub>Visão geral da linha com cenário de exemplo carregado</sub>
</p>

<p align="center">
  <img src="docs/screenshot-2.png" alt="Log de integração com o SAP" width="100%">
  <br><sub>Log de integração com o SAP</sub>
</p>

## ✨ Funcionalidades

- Leitura simulada de tags de PLC (protocolos **OPC UA** e **Modbus**) com qualidade do sinal
- Registro de eventos de produção, refugos e paradas, com inclusão manual
- Log de mensagens trocadas com o SAP, incluindo falhas simuladas de RFC/IDoc e reenvio
- Cálculo de **OEE** (disponibilidade, performance e qualidade) com histórico
- Mapa de tags, versionamento de programas de PLC e editor com exportação (CSV/TXT)

## 🛠️ Tecnologias

`HTML5` · `CSS3` · `JavaScript` · `Chart.js`

## ▶️ Como usar

Abra a demo, ou baixe o repositório e abra o `index.html` no navegador. Depois clique em **Iniciar simulação** ou **Carregar cenário de exemplo**.

Não precisa instalar nada nem rodar servidor: é só HTML, CSS e JavaScript.

## 📝 Observações

Projeto de estudo/portfólio. Todos os dados são simulados e ficam em memória no navegador; nada é enviado a servidores.

---

## 👤 Autor

**Daniel da Silva Rezende** — estudante de Engenharia de Software e Análise e Desenvolvimento de Sistemas.

[![GitHub](https://img.shields.io/badge/GitHub-orezzende-181717?style=flat&logo=github)](https://github.com/orezzende)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Daniel%20Rezende-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-da-silva-rezende-711ab1195/)
