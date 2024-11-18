# Implementação do Algoritmo de Regressão Linear no Conjunto de Dados dos Principais Influenciadores do Instagram
Descrição: O projeto utilizou Regressão Linear para prever a taxa de engajamento de influenciadores no Instagram, considerando variáveis como seguidores, média de curtidas e número de posts. Após uma análise exploratória, os dados foram tratados com imputação de valores ausentes, normalização e codificação de variáveis categóricas. O modelo foi desenvolvido usando métodos como mínimos quadrados e gradiente descendente.

Instalação: O conjunto de dados deve ser instalado previamente através do link https://www.kaggle.com/datasets/surajjha101/top-instagram-influencers-data-cleaned 

Execução:  Assim que a primeira célula do código no Google Colab for executada o ambiente irá solicitar que o Dataset seja importado, basta escolher o arquivo instalado anteriormente e seguir executando as células de modo sequencial.

Estrutura dos Arquivos: Todo o projeto foi elaborado com o uso do Google Colab, sendo ele nosso unico arquivo de código e uplodado direto do próprio colab para o GitHub. Temos esse read.me que guia o usuário na utilização do algortimo, o relatório que descreve todo processo de desenvolvimento e o arquivo .csv que é o dataset utilizado na análise.

Tecnologia: A linguagem utilizada nesse projeto foi o Python e as bibliotecas foram: Pandas, Seaborn, Numpy, scikit-learn (sklearn.model_selection, sklearn.linear_model, sklearn.metrics, sklearn.preprocessing) e matplotlib.

Autores e colaboladores: Dentro desse projeto, os dois autores são Caio Cordeiro Matos, responsável pela limpeza e pré-processamento dos dados, como tratamento valores nulos e remoção dos dados categóricos não relevantes, Identificação de quais insights podem ser extraídos do Dataset para atender aos objetivos do projeto e interpretação dos coeficientes gerados pelos modelos para fornecer recomendações práticas, e Fernando Nardes Ferreira Neto, responsável pela normalização e escalonamento de variáveis para preparar os dados para modelagem, treinamento e ajuste dos modelos para maximizar a precisão e minimizar o erro em produção e criação de gráficos para ilustrar o desempenho do modelo. Dentro do Google Colab contamos com o auxílio do Gemini para estruturar o código para ser reutilizável, modular e limpo, tratando erros e exceções para garantir robustez ao código.
