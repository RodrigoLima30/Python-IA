Neste projeto, desenvolvi um modelo de inteligência artificial para prever o score de crédito dos clientes de um banco, categorizando-o como "Ruim", "Ok" ou "Bom". A análise foi feita utilizando as bibliotecas pandas (manipulação de dados), scikit-learn (criação e avaliação de modelos de IA) e ferramentas como LabelEncoder para transformar colunas de texto em números, preparando os dados para o treinamento.

Os dados foram divididos em variáveis independentes (X) e dependentes (y) e, posteriormente, em conjuntos de treino e teste usando train_test_split. Dois modelos de IA foram comparados: Random Forest (árvore de decisão) e K-Nearest Neighbors (KNN). Após treinar ambos, foi avaliada a precisão de cada modelo com accuracy_score. O modelo de árvore de decisão apresentou o melhor desempenho.

Por fim, o modelo foi utilizado para prever o score de crédito de novos clientes, demonstrando eficiência na classificação e fornecendo insights úteis para a tomada de decisão do banco.
