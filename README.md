# Telecom X - Análise de Evasão de Clientes (Churn)

## Contexto

A Telecom X enfrenta um alto índice de cancelamentos de clientes (*Churn*), o que impacta diretamente sua receita e crescimento.
Este projeto tem como objetivo analisar os dados de clientes e identificar fatores que influenciam a evasão, gerando insights e recomendações estratégicas para reduzir o churn.


---

## Objetivos

* Realizar limpeza e tratamento de dados provenientes da API da Telecom X.
* Conduzir uma análise exploratória de dados (EDA) para identificar padrões relacionados ao cancelamento de clientes.
* Extrair insights valiosos que auxiliem a empresa a entender as causas da evasão.
* Sugerir recomendações práticas para retenção de clientes.

---

## Requisitos

* Plotly
* Pandas
* Numpy
* Requests
* Json

---

## Como executar

1. **Clone o repositório**

   ```bash
   git clone https://github.com/alcyberan/Challenge-Telecom-X.git
   cd Challenge-Telecom-X
   ```

2. **Instale as dependências**

   ```bash
   pip install pandas
   pip install numpy
   pip install plotly
   pip install requests
   ```

3. **Abra o notebook**

   ```bash
   jupyter notebook
   ```

   Ou abra diretamente no [Google Colab](https://colab.research.google.com/) enviando os arquivos do projeto.

4. **Execute as células** para carregar os dados, gerar os gráficos e visualizar o relatório final.

---

## Etapas do Projeto

1. **Extração e Tratamento de Dados**

   * Dados obtidos via API da Telecom X em formato JSON.
   * Conversão para DataFrame, padronização de tipos e remoção de inconsistências.
   * Criação de novas variáveis como "Contas\_Diárias".

2. **Análise Exploratória de Dados (EDA)**

   * Estatísticas descritivas.
   * Visualizações de churn por variáveis categóricas (contrato, forma de pagamento, gênero, etc.).
   * Visualizações de churn por variáveis numéricas (gastos diários, mensais e totais).

---

## Conclusões

* 88% dos clientes em churn possuem contratos Mês-a-Mês.
* 57% dos clientes em churn utilizam cheque eletrônico como meio de pagamento.
* Os picos de evasão ocorrem nos primeiros 5 meses de contrato, com destaque para o 1º mês.
* Clientes que cancelam apresentam gasto total em média 23% superior ao dos clientes ativos.

---

## Recomendações

* Incentivar contratos de longo prazo com benefícios exclusivos.
* Incentivar métodos de pagamento mais práticos e confiáveis (cartão, débito automático).
* Implementar estratégias de retenção nos primeiros meses de contrato.
* Revisar precificação e percepção de valor dos planos oferecidos.

---

## Próximos Passos

* Construção de modelos preditivos de churn.

---
