# 🏆 Automação de Coleta – Tabela Brasileirão Série A (UiPath)

Este projeto realiza uma automação com **UiPath** para coletar os dados da **tabela da Série A do Campeonato Brasileiro** diretamente do Google, e organiza todas as estatísticas dos times em um único arquivo Excel.

---

## 📌 Funcionalidades

- Acessa automaticamente o Google e pesquisa pela tabela da Série A do Brasileirão
- Extrai as seguintes informações:
  - Nome dos times
  - Pontuação
  - Número de partidas
  - Vitórias
  - Empates
  - Derrotas
- Armazena os dados em **duas variáveis de DataTable**
- Une as duas tabelas em **uma única tabela final**
- Exporta os dados para uma planilha Excel (`.xlsx`)
- Salva o arquivo localmente
- Encerra o processo automaticamente

---

## 🧰 Tecnologias e Ferramentas

- [UiPath Studio](https://www.uipath.com/)
- Data Scraping
- Merge DataTable
- Write Range (Excel Application Scope)
- Navegador Chrome (ou Edge)
- Google Search


