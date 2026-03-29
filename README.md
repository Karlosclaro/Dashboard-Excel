Perfeito ✅  
Abaixo está o **README adaptado para padrão GitHub**, usando Markdown, linguagem clara e estrutura comum em repositórios de dados/analytics.

Você pode copiar **diretamente** para um arquivo `README.md`.

***

# 📊 Vendas Mensais por Produto – Base de Dados

Este repositório contém a **base de dados de vendas mensais por produto**, utilizada como **fonte principal de um Dashboard dinâmico** desenvolvido em planilha (Excel / Google Sheets).

Os dados permitem análises de **quantidade vendida** e **faturamento**, segmentadas por **produto** e **mês**.

***

## 🗂 Estrutura da Base de Dados

Cada linha da tabela representa o **resultado de vendas de um produto em um mês específico**.

### Colunas

| Coluna        | Descrição                                                             |
| ------------- | --------------------------------------------------------------------- |
| `Produto`     | Nome do produto comercializado                                        |
| `Mês`         | Mês de referência da venda (`Jan`, `Fev`, `Mar`, `Abr`, `Mai`, `Jun`) |
| `Quantidade`  | Total de unidades vendidas no mês                                     |
| `Faturamento` | Valor total faturado no mês (em R$)                                   |

***

## 📈 Integração com o Dashboard

*   Esta base é consumida diretamente pelo **Dashboard dinâmico**
*   Os dados alimentam:
    *   Gráficos comparativos
    *   KPIs de faturamento
    *   Análise de desempenho por produto e por mês
*   Qualquer alteração nesta base reflete automaticamente no Dashboard após atualização

⚠️ **Mudanças estruturais podem quebrar filtros, gráficos e tabelas dinâmicas.**

***

## ✍️ Regras de Uso e Manutenção

### ✅ Permitido

*   Inserir novos registros abaixo da última linha
*   Atualizar valores de quantidade ou faturamento
*   Adicionar novos meses, mantendo o padrão já existente

### 🚫 Não Permitido

*   Alterar o nome das colunas
*   Excluir colunas
*   Inserir linhas ou colunas em branco dentro da tabela
*   Mesclar células
*   Alterar o formato dos campos (especialmente o faturamento)

***

## 📐 Padrões Utilizados

*   **Mês:** abreviação em português (`Jan`, `Fev`, `Mar`, etc.)
*   **Quantidade:** número inteiro
*   **Faturamento:** formato monetário brasileiro  
    Exemplo:
    ```text
    R$ 581,00
    ```

***

## 🔄 Atualização dos Dados

*   Após qualquer alteração na base:
    *   Atualize tabelas dinâmicas, se aplicável
    *   Recarregue o Dashboard
*   Recomenda-se revisar os indicadores após:
    *   Inclusão de novos meses
    *   Correção de valores históricos

***

## ✅ Boas Práticas

*   Manter consistência nos nomes dos produtos
*   Evitar copiar e colar dados com formatação externa
*   Realizar backup antes de alterações em grande volume
*   Validar os dados antes de atualizar o Dashboard

***

## 👤 Responsável

*   **Responsável pela base:** *Karlos Claro*
*   **Última atualização:** *16:58 29/03/2026*
