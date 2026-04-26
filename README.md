# Controle de Entrega e Validade de EPIs 🛡️

Este projeto faz parte do meu portfólio de **Análise de Dados**. Ele demonstra a integração entre **Python**, para automação e tratamento de dados, e **Power BI**, para visualização estratégica de indicadores.

## 📌 Objetivo do Projeto
O objetivo foi criar uma solução automatizada para gerenciar a entrega de Equipamentos de Proteção Individual (EPIs), calculando automaticamente a data de vencimento com base na validade técnica de cada item.

## 🛠️ Tecnologias Utilizadas
* **Python 3.14**: Linguagem principal.
* **Pandas**: Biblioteca para manipulação e tratamento dos dados.
* **VS Code + Jupyter Notebook**: Ambiente de desenvolvimento.
* **Power BI**: Criação de dashboard interativo.
* **GitHub**: Controle de versão e portfólio.

## 🚀 Como o projeto funciona
1.  **Geração de Dados**: O script Python cria uma base de dados fictícia simulando a entrega de EPIs para colaboradores.
2.  **Tratamento e Cálculo**: Utilizei o Pandas para converter formatos de data e calcular a `Data_Vencimento` somando a `Data_Entrega` ao prazo de validade.
3.  **Exportação**: Os dados são salvos automaticamente em um arquivo Excel (`.xlsx`).
4.  **Visualização**: O Power BI consome esse arquivo para exibir o status de validade de cada colaborador.

## 📊 Resultados
O projeto permite que um gestor de Qualidade ou RH identifique rapidamente quais EPIs estão próximos do vencimento, garantindo a segurança dos colaboradores e a conformidade com as normas.

---
**Desenvolvido por:** Fábio Junio de Souza Lima
