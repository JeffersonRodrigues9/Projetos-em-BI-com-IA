# Projetos de Business Intelligence e Análise de Dados utilizando Power BI e IA

Este repositório reúne projetos pessoais e acadêmicos desenvolvidos durante minhas formações no SENAC e no SENAI, focados na construção de soluções fim a fim em Business Intelligence, Análise de Dados e Inteligência Artificial.

Os projetos cobrem desde a ingestão e tratamento de dados até a visualização executiva e automação de insights. As principais abordagens técnicas incluem:

Processos de ETL e ELT: Limpeza, transformação e carga de dados integrando Power BI, Excel e Python.

Modelagem de Dados & DAX: Criação de modelos relacionais performáticos (Star Schema) e desenvolvimento de métricas avançadas em DAX.

Engenharia & Automação com Python: Uso de scripts para automação de rotinas de dados, manipulação avançada e modelagem.

Inteligência Artificial & Automação (GenAI): Utilização de modelos de linguagem como Gemini e Claude para apoio na geração automatizada de insights, suporte à análise de dados e otimização de processos de tomada de decisão estratégica.

O objetivo deste portfólio é demonstrar a aplicação prática da Análise de Dados moderna, combinando a robustez do BI tradicional com o potencial transformador da Inteligência Artificial.

## Business Intelligence

### 📈 Projeto 1: Dashboard de Análise Financeira & Performance
Objetivo: Transformar dados financeiros brutos e desestruturados num painel interativo no Power BI para suporte ao planeamento estratégico de receitas, despesas e margem de lucro.

🛠️ Funcionalidades e Etapas TécnicasETL & Tratamento de Dados (Power Query): Limpeza, unpivot (pivotação de colunas), padronização de layouts e estruturação de tabelas para análise.Modelagem de Dados & DAX: Criação de modelo relacional e desenvolvimento de medidas em DAX para cálculo de indicadores-chave (KPIs) de performance:

Receita Total (1,92 Mi)   
Despesa Total (1,15 Mi)   
Margem de Lucro (39,96%)   

Análise Visual & Key Influencers:Distribuição de receitas por componente (Vendas, Licenciamento, Aluguéis, etc.).   Comparativo de despesas por centro de custo em relação à média geral.   
Tabela matricial hierárquica (Tipo/Componente/Ano) para análise temporal.   Uso do visual Principais Influenciadores do Power BI para segmentação automática de comportamentos financeiros. 

💡 Insights do NegócioIdentificação dos componentes de maior peso na receita bruta (ex: Vendas a liderar o faturamento).   Mapeamento dos principais ofensores de despesas (ex: Administrativo e Salários) em relação à linha média.   Segmentação estratégica para tomada de decisão focada em corte de custos e otimização da margem de lucro.   

![Image](https://github.com/user-attachments/assets/c164942d-5bcf-42c1-9c8b-dda631249243)


### 📈 Projeto 2: Dashboard de Performance Financeira Multibancária

Objetivo: Desenvolvi um painel financeiro consolidado no Power BI para analisar o desempenho operacional de cinco grandes instituições bancárias (Nubank, Safra, Santander, Bradesco e Itaú), permitindo o acompanhamento de receitas, despesas, tributação e lucratividade ao longo do ano.

#### 🛠️ Funcionalidades e Etapas TécnicasModelagem de Dados & DAX:
Design & Análise Visual:

* **Modelagem de Dados & DAX:** Criei medidas calculadas para consolidar as métricas essenciais e os KPIs executivos de receita, despesa, impostos e margem de lucro.
* **Segmentação por Instituição:**  Construí um filtro interativo com marcas bancárias para permitir análises individualizadas ou comparativas.
* **Gráfico de Cascata (Waterfall Chart):** Implementei a visualização da variação acumulada do lucro mensal ao longo do ano.   
* **Análise Transacional:** Destaquei o volume e a representatividade das movimentações via Pix.  
* **Ticker Superior:** Configurei a exibição dinâmica de variações percentuais por praças/regiões.   

💡 Insights do NegócioAcompanhei o impacto direto das despesas e da carga tributária sobre a margem final de lucro.   
Mapeei a alta adoção do Pix como principal meio transacional e a sua representatividade nas movimentações operacionais.   
Identifiquei os meses de maior retração e expansão de resultado por meio da análise de cascata financeira.   

![Image](https://github.com/user-attachments/assets/f1d76627-6a93-4b3f-b596-b0f6d0fcd629)

### 📈 Projeto 3: Dashboard de Gestão Estratégica de Recursos Humanos (RH)

Objetivo: Desenvolvi um painel executivo no Power BI focado na gestão de pessoas, permitindo acompanhar a dinâmica da força de trabalho, monitorar a retenção de talentos e analisar a distribuição demográfica e operacional da empresa.

#### 🛠️ Funcionalidades e Etapas Técnicas
* **Modelagem de Dados & DAX:** Criei medidas calculadas em DAX para mensurar os indicadores fundamentais de RH:
  * **Headcount & Movimentação:** Acompanhamento do total de contratações, demissões e funcionários ativos.
  * **Taxa de Turnover:** Cálculo da rotatividade de colaboradores para apoiar estratégias de retenção.
* **Design & Análise Visual:**
  * **Árvore de Decomposição (Decomposition Tree):** Implementei o visual IA para detalhar a distribuição de funcionários ativos por cargos (Estagiário, Analista, Coordenador, etc.) e áreas (Administrativo, Comercial, Operações, etc.)[cite: 7].
  * **Distribuição Geográfica e Demográfica:** Construí visuais focados na alocação por cidades e na proporção por gênero[cite: 7].
  * **Análise Temporal:** Acompanhamento gráfico da evolução das contratações ao longo do período[cite: 7].

#### 💡 Insights do Negócio
* Identifiquei padrões de retenção e gargalos por área através da decomposição de cargos e departamentos[cite: 7].
* Mapeei as principais praças de alocação de talentos e a distribuição demográfica da empresa[cite: 7].
* Apoiei a tomada de decisões estratégicas para planejamento de headcount, recrutamento e gestão de pessoas.

![Image](https://github.com/user-attachments/assets/a0b2dbf5-c385-40ae-8785-63fd0d6f4b3f)



