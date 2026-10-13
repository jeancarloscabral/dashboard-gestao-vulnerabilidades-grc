# 🛡️ Dashboard de Gestão de Vulnerabilidades (GRC)

## 📌 Visão Geral
Este projeto consiste em um painel interativo desenvolvido no **Power BI** para apoio à Governança, Riscos e Compliance (GRC) e Segurança da Informação. O objetivo principal é monitorar falhas de segurança nos servidores da infraestrutura, categorizá-las por nível de gravidade e acompanhar o status das correções em tempo real.

---

## 📊 Estrutura dos Dados e Indicadores

### 1. Base de Dados (`tabela_seguranca.xlsx`)
A estrutura contém os seguintes atributos essenciais:
* **`ID_Servidor`**: Identificador único do ativo afetado.
* **`Nome_Servidor`**: Nome do servidor na rede.
* **`Problema_Encontrado`**: Descrição da vulnerabilidade/falha identificada.
* **`Gravidade`**: Classificação do risco (*Crítica*, *Alta*, *Média*).
* **`Status`**: Situação da remediação (*Pendente*, *Corrigido*).

### 2. Visuais do Dashboard (Power BI)
* **Cartão de Métrica:** Total de vulnerabilidades identificadas.
* **Gráfico de Rosca:** Distribuição percentual das falhas por nível de gravidade.
* **Gráfico de Barras:** Mapeamento do status de tratamento (Pendentes vs. Corrigidos).

---

## 🛠️ Tecnologias Utilizadas
* **Microsoft Excel**: Estruturação e modelagem inicial da base de dados.
* **Microsoft Power BI Desktop**: Tratamento de dados, criação de métricas e construção do visual.
* **GitHub**: Versionamento e documentação do projeto de portfólio.

---

## 📂 Como Reproduzir o Projeto
1. Faça o clone ou download deste repositório.
2. Abra o arquivo `Dashboard_Gestao_Vulnerabilidades.pbix` no **Power BI Desktop**.
3. Certifique-se de atualizar o caminho da fonte de dados apontando para o arquivo `tabela_seguranca.xlsx`, caso necessário.
