📊 Análise Estratégica de Performance Operacional da Olist

Projeto de análise exploratória e executiva dos dados do marketplace da Olist, com foco em crescimento de receita, comportamento dos meios de pagamento, distribuição geográfica e satisfação dos clientes. O objetivo é transformar dados operacionais em insights estratégicos capazes de apoiar a tomada de decisão e sustentar o crescimento da empresa.

📌 Objetivo

Responder à seguinte pergunta norteadora:

Como a Olist pode sustentar seu crescimento e aumentar a receita mantendo altos níveis de satisfação dos clientes e eficiência operacional?

A análise busca identificar riscos, oportunidades e recomendações estratégicas com base no histórico de pedidos entre janeiro de 2017 e agosto de 2018.

📂 Dataset

Este projeto utiliza o conjunto de dados público da Olist disponibilizado no Kaggle:

🔗 https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Os dados incluem:

Pedidos realizados;
Informações de clientes e vendedores;
Produtos;
Pagamentos;
Avaliações dos clientes;
Dados geográficos;
Informações logísticas e de entrega.
🎯 Principais Objetivos da Análise
Avaliar a evolução do faturamento e volume de pedidos;
Analisar o comportamento dos meios de pagamento;
Investigar a distribuição geográfica das receitas;
Medir a satisfação dos clientes por meio das avaliações;
Identificar os impactos dos atrasos logísticos na experiência do consumidor;
Mapear riscos operacionais e oportunidades de crescimento.
🛠 Ferramentas Utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
SQL Server
Power BI
Jupyter Notebook
📈 Principais Insights
🚀 Crescimento e Receita
A operação apresentou forte crescimento em 2017, impulsionado pela Black Friday.
Em 2018, o negócio atingiu um novo patamar de estabilidade.
O crescimento ocorreu principalmente pelo aumento do número de clientes, e não pelo aumento do ticket médio.
🌎 Distribuição Geográfica
O Sudeste concentra cerca de 65% da receita.
São Paulo representa aproximadamente 38% do faturamento.
Norte e Nordeste possuem menor participação, porém apresentam ticket médio superior.
💳 Meios de Pagamento
Cartão de crédito representa cerca de 74% das transações.
Boleto corresponde a aproximadamente 19%.
Mais de 80% das compras parceladas concentram-se em até 4 parcelas.
⭐ Satisfação do Cliente
77% dos clientes avaliam a experiência com notas 4 e 5.
Existe uma parcela relevante de clientes detratores (nota 1).
Atrasos logísticos impactam diretamente a satisfação.
📦 Logística
Aproximadamente 92% dos pedidos são entregues dentro do prazo ou antecipadamente.
Atrasos superiores a 10 dias reduzem a avaliação média para 1,72 estrelas.
A capacidade logística é um dos principais riscos para o crescimento sustentável.
⚠️ Principais Riscos Identificados
Vulnerabilidade da operação em períodos de pico de demanda;
Risco reputacional causado por clientes detratores;
Dependência do crescimento por aquisição de novos clientes;
Elevada concentração dos pagamentos em cartão de crédito.
💡 Recomendações Estratégicas
Expandir a capacidade logística e criar planos de contingência;
Investir na expansão para Norte e Nordeste;
Desenvolver programas de recuperação de clientes insatisfeitos;
Implementar estratégias para aumento do ticket médio;
Diversificar os meios de pagamento, ampliando o uso do Pix e carteiras digitais.
📊 Dashboard

O projeto inclui dashboards desenvolvidos em Power BI para visualização dos principais indicadores:

Receita mensal;
Volume de pedidos;
Ticket médio;
Distribuição geográfica;
Participação dos meios de pagamento;
Avaliação dos clientes;
Impacto dos atrasos logísticos.
📁 Estrutura do Projeto
📦 olist-performance-analysis
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── analise_exploratoria.ipynb
│
├── sql/
│   ├── criacao_tabelas.sql
│   ├── consultas.sql
│
├── dashboard/
│   ├── dashboard_olist.pbix
│
├── relatorio/
│   ├── Relatorio_Executivo.pdf
│
├── images/
│   ├── dashboard.png
│
└── README.md
📚 Principais Métricas Analisadas
Indicador	Valor
Pedidos entregues	97,82%
Cancelamentos	0,48%
Clientes satisfeitos (4 e 5 estrelas)	77%
Participação do cartão de crédito	74%
Receita concentrada no Sudeste	65%
Avaliação média em atrasos >10 dias	1,72
🎓 Aprendizados

Este projeto permitiu aplicar conceitos de:

Análise exploratória de dados (EDA);
Storytelling com dados;
Construção de indicadores de negócio (KPIs);
Análise de comportamento do consumidor;
Inteligência de negócios (BI);
Formulação de recomendações estratégicas baseadas em dados.
📬 Contato

João Pedro

LinkedIn: www.linkedin.com/in/joaopedrobarbosa-analyst
GitHub: https://github.com/seu-usuario

⭐ Se este projeto foi útil ou interessante para você, considere deixar uma estrela no repositório!
