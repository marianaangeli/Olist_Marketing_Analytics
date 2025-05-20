# Triggo AI - Teste Tecnico
### Visão Geral ###
 Este projeto analisa dados do marketplace brasileiro Olist para extrair insights sobre o comportamento
 de compras, satisfação dos clientes e eficiência operacional. O código utiliza Python com bibliotecas
 como Pandas, Matplotlib, Seaborn e Scikit-learn para análise exploratória e modelagem preditiva.
 ### Requisitos ###
 - Python 3.6+
 - Pandas
 - NumPy
 - Matplotlib
 - Seaborn
 - Scikit-learn
 - Geopy
 - Pandasql
 - SMOTE (imblearn)
### Conjunto de Dados ###
O projeto utiliza o dataset público do Olist, que contém informações sobre pedidos, produtos, clientes, vendedores e avaliações. Os principais arquivos são:
 - olist_orders_dataset.csv : Informações sobre pedidos
 - olist_order_items_dataset.csv : Itens incluídos nos pedidos
 - olist_order_payments_dataset.csv : Métodos de pagamento
 - olist_order_reviews_dataset.csv : Avaliações dos clientes
 - olist_customers_dataset.csv : Dados dos clientes
 - olist_sellers_dataset.csv : Dados dos vendedores
 - olist_products_dataset.csv : Informações dos produtos
 - olist_geolocation_dataset.csv : Dados geográficos
### Principais Análises ###
1. Análise Exploratória dos Dados 
 - Volume de pedidos por mês
 - Distribuição do tempo de entrega
 - Relação entre valor do frete e distância
 - Categorias mais vendidas
- Valor médio de pedido por estado
2. Análise de Retenção 
 - Taxa de clientes recorrentes
 - Estratégias para melhorar a retenção
3. Predição de Atrasos 
 - Modelo de machine learning para prever atrasos nas entregas
 - Métricas de performance do modelo
 - Importância das features
4. Segmentação de Clientes 
 - Clustering por valor gasto
 - Estratégias específicas por segmento
5. Análise de Satisfação 
 - Relação entre tempo de entrega e nota de avaliação
 - Notas por categoria de produto
 - Relação entre valor do pedido e satisfação
### Principais Insights ###
1. Volume de Vendas:
 - Crescimento consistente entre 2016-2017
 - Picos de vendas em novembro/dezembro (Black Friday e Natal)
 - Estabilização em 2018
 2. Entregas e Logística:
 - 80% das entregas ocorrem em menos de 15 dias
 - Correlação fraca (-0.176) entre tempo de entrega e satisfação
 - Valor do frete não apresenta forte correlação com a distância
 3. Clientes:
 - Taxa de retenção (3,03%)
 - Segmentação identifica 3 perfis claros de clientes
 - Valor do pedido não afeta significativamente a satisfação
 4. Produtos e Categorias:
 - Categorias populares têm notas médias entre 3,9 e 4,2
 - Brinquedos e perfumaria são as categorias mais bem avaliadas
 5. Modelo Preditivo:
 - Acurácia de 99,21% na previsão de atrasos
- Precisão de 92,05% na identificação de pedidos atrasados
### Recomendações Estratégicas ###
 1. Melhorar retenção de clientes:
 - Implementar programa de fidelidade
 - Utilizar remarketing e e-mail marketing personalizado
 - Aprimorar experiência do cliente
 2. Otimizar logística:
 - Focar em reduzir tempos de entrega (impacta satisfação)
 - Revisar política de fretes (aparentemente desconectada da distância)
 3. Marketing por segmento:
 - Estratégias específicas para os 3 clusters identificados
 - Foco em aumentar ticket médio dos clientes do cluster 0
 4. Categorias de produtos:
 - Promover mais categorias bem avaliadas (brinquedos, perfumaria)
 - Investigar razões de satisfação menor em eletrônicos
 5. Previsão operacional:
 - Implementar modelo preditivo para antecipar problemas de entrega
 - Utilizar dia da semana como variável importante no planejamento
