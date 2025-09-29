
# 📊 Dashboard de Vendas - Análise de Assinaturas Microsoft

## 📝 Visão Geral

Este dashboard oferece uma análise estratégica do desempenho de vendas dos serviços de assinatura da Microsoft. O objetivo é fornecer insights claros sobre as fontes de receita, o comportamento dos assinantes e a eficácia das estratégias de retenção e vendas adicionais (cross-sell).

As análises foram construídas para responder a perguntas de negócio críticas e apoiar a tomada de decisão das equipes de estratégia, marketing e produto.

---

## 🚀 Perguntas de Negócio e Análises do Dashboard

O dashboard está estruturado para responder às seguintes perguntas:

### 1. Qual o faturamento Total de vendas dos planos anuais?
Esta análise consolida a receita gerada exclusivamente por clientes que optaram por um ciclo de assinatura anual.

* **KPI no Dashboard:** `TOTAL SUBSCRIPTIONS PER TYPE` (Gráfico de barras)
* **Insight Estratégico:** Este valor representa a contribuição financeira dos clientes de maior comprometimento. É um indicador chave para a previsibilidade de receita e a estabilidade do fluxo de caixa da empresa, mostrando o quanto da receita está "garantida" para os próximos 12 meses.

### 2. Qual o faturamento Total de vendas dos planos anuais, separados por auto renovação?
Aqui, segmentamos a receita dos planos anuais entre os clientes que têm a renovação automática ativada (`Sim`) e os que não têm (`Não`).

* **Gráfico no Dashboard:** `TOTAL SUBSCRIPTIONS PER AUTO RENEWAL` (Gráfico de barras deitado)
* **Insight Estratégico:** Esta é uma métrica vital para a saúde do negócio. Uma alta receita na categoria `Sim` indica satisfação e receita recorrente previsível. Por outro lado, um volume significativo na categoria `Não` representa um **risco de churn** (cancelamento) que exige ações proativas da equipe de retenção.

### 3. Qual o Total de vendas por assinaturas (EA Play e Minecraft Season Pass)?
Esta análise mede o desempenho de vendas dos produtos adicionais (add-ons) oferecidos aos assinantes.

* **KPIs no Dashboard:** `TOTAL SUBSCRIPTION EA PLAY SEASON PASS` e `TOTAL SUBSCRIPTION MINECRAFT SEASON PASS` (Cards)
* **Insight Estratégico:** Avalia o sucesso da estratégia de **cross-sell**. Permite identificar qual add-on é mais popular e entender o potencial de receita incremental. Com base nesses dados, a equipe de produto pode criar novos pacotes (bundles) ou direcionar campanhas de marketing mais eficazes.

### 4. Qual o total faturado mensal com os assinantes em auto renovação?
Este gráfico acompanha a evolução da receita mensal gerada *apenas* pela base de clientes mais fiel, ou seja, aqueles com renovação automática ativada.

* **Gráfico no Dashboard:** `TOTAL SUBSCRIPTIONS PER MONTH (AUTO RENEWAL)` (Gráfico de Linha)
* **Insight Estratégico:** Este é o pulso da receita recorrente e sustentável da empresa. A tendência (crescente, estável ou decrescente) neste gráfico é um dos indicadores mais importantes do crescimento saudável do negócio. Ele ajuda a identificar sazonalidades e o impacto de ações de marketing na base de clientes mais engajada.

---

## ⚙️ Como Utilizar o Dashboard

O dashboard é interativo. Utilize os **filtros laterais** para explorar os dados com mais profundidade:

* **Filtrar por Plano:** `Core`, `Standard`, `Ultimate`
* **Filtrar por Tipo de Assinatura:** `Annual`, `Quarterly`, `Monthly`
* **Filtrar por Auto Renovação:** `Yes`, `No`

Esses filtros permitem cruzar informações e gerar insights ainda mais específicos para análises detalhadas.

---

## 🛠️ Ferramentas e Fonte de Dados

* **Fonte de Dados:** Base de dados de assinantes da Microsoft (fictícia).
* **Ferramenta de Visualização:** O design visual foi elaborado no excel, como projeto do curso da DIO.
* **Proximos passos:** Existem outras perguntas a serem respondidas a partir dessa base de dados, então para complementar o projeto irei trazer novos insights e visualizações graficas.

