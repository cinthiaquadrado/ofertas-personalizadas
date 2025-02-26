# Análise de Clientes - Segmentação RFM com K-Means

Este projeto tem como objetivo realizar a segmentação de clientes de uma empresa utilizando a técnica RFM (Recência, Frequência, Monetário), seguida pela segmentação dos clientes em grupos distintos utilizando o algoritmo K-Means.

# Descrição do Projeto
Este projeto segmenta os clientes de uma empresa com base em três métricas principais:

- Recência: Quantos dias se passaram desde a última compra do cliente.
- Frequência: Quantas compras o cliente fez em um período.
- Monetário: O valor total gasto pelo cliente.

Utilizando essas métricas, criamos uma tabela RFM, em seguida aplicamos o algoritmo de K-Means para realizar a segmentação dos clientes, agrupando-os em diferentes clusters. Além disso, o projeto gera gráficos de distribuição dessas métricas e fornece sugestões de marketing personalizadas para cada grupo.

# Requisitos
Certifique-se de ter as seguintes bibliotecas instaladas:

pandas
numpy
matplotlib
seaborn
scikit-learn
datetime

# Uso
1. Carregar os Dados
O projeto requer alguns arquivos CSV com dados de pedidos, clientes, pagamentos e itens. Coloque os seguintes arquivos no mesmo diretório do código:

olist_orders_dataset.csv - Contém os pedidos dos clientes.
olist_customers_dataset.csv - Contém os dados dos clientes.
olist_order_payments_dataset.csv - Contém os dados de pagamentos.
olist_order_items_dataset.csv - Contém os itens dos pedidos.

2. Rodar o Script
O script fará as seguintes etapas:
- Carregará os dados.
- Preparará os dados e criará a tabela RFM.
- Gerará gráficos de distribuição para as métricas RFM.
- Realizará a segmentação utilizando o K-Means.

3. Saída
O script irá gerar gráficos de distribuição para as variáveis de Recência, Frequência e Monetário, além de exibir a segmentação dos clientes em diferentes clusters.

Exemplo de Saída:
- Cluster 0: Clientes Dormindo: Ofertas de reativação, cupons de desconto
- Cluster 1: Clientes Frequentes, Baixo Gasto: Promoções de upsell, descontos progressivos
- Cluster 2: Clientes VIP: Benefícios exclusivos, programa de fidelidade premium
- Cluster 3: Novos Clientes ou Clientes Ocasionalmente Ativos: Incentivos para engajamento, descontos em próximas compras
