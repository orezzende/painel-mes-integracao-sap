# Painel MES · Integração Chão de Fábrica com SAP

Simulador de ponte entre chão de fábrica e SAP (módulos PP, PM e QM). Projeto de estudo: roda 100% no navegador, com dados simulados e sem conexão com um SAP real.

**Demo:** https://orezzende.github.io/painel-mes-integracao-sap/

## Funcionalidades

- Leitura simulada de tags de PLC (protocolos OPC UA e Modbus) com qualidade do sinal
- Registro de eventos de produção, refugos e paradas, com inclusão manual de eventos
- Log de mensagens trocadas com o SAP (confirmações PP, notificações PM, inspeções QM), incluindo falhas simuladas de RFC/IDoc
- Cálculo de OEE (disponibilidade, performance e qualidade) com histórico
- Mapa de tags, versionamento de programas de PLC e editor com exportação de dados

## Tecnologias

HTML, CSS, JavaScript, Chart.js

## Como usar

Abra a demo ou o `index.html` no navegador e use **Iniciar simulação** ou **Carregar cenário de exemplo**.

Também dá para baixar o repositório e abrir o `index.html` direto no navegador, sem instalar nada.

## Observações

Projeto de estudo/portfólio. Todos os dados são simulados e ficam em memória no navegador; nada é enviado a servidores.

## Autor

Daniel da Silva Rezende · [GitHub](https://github.com/orezzende) · [LinkedIn](https://www.linkedin.com/in/daniel-da-silva-rezende-711ab1195/)
