# Alura Challenge - Churn Prediction
Esse projeto faz parte do primeiro desafio de Ciência de Dados proposto pela plataforma de ensino Alura

## Objetivo:
O objetivo proposto pelo projeto é o de utilização de um banco de dados com informações referentes a uma companhia ficticia de telefonia para identificação da taxa de Churn dos clientes, identificação dos principais critérios que geram essa taxa e por fim criação de um modelo de predição para identificar os clientes com maiores potenciais de ocorrência, possibilitando uma redução nessa taxa.

Antes de iniciar, se mostra importante definir o que seria o Churn. Trata-se de um indicador utilizado por diversas companhias de diferentes setores para identificar a taxa de abandono de clientes durante um período de tempo, sendo bem relevante para a estimativa impactos na receita da empresa, além da saúde da empresa.

Para esse projeto, decidimos seguir um roteiro simplificado de entendimento do negócio, entendimento dos dados, preparação dos dados, modelagem, avaliação de resultados e implementação, tentando assim cobrir o máximo possível de conceitos utilizados em uma análise real para o mercado.

Por fim, um método capaz de predizer o Churn para cada cliente individualmente será proposto, buscando usufruir de técnicas e modelos de aprendizado de máquina, gerando uma avaliação individual para cada cliente de acordo com as características presentes no cadastro.

## Métodos utilizados
* Análise exploratória
* Visualização e processamento dos dados
* Técnicas de over-sampling para balanceamento
* Machine Learning
* Modelos de classificação como Random Forest Classifier
* Técnicas de avaliação de modelos


## Tecnologias utilizadas
* Python
* Pandas, Numpy
* Matplotlib, Seaborn, Plotly
* Scikit-Learn
* Imblearn
* Jupyter Notebook
* Descrição do projeto

Esse projeto tem como objetivo a identificação e a classificação de clientes com maiores possibilidades para ocorrência de Churn, sendo assim, é fundamental entendermos as informações presentes no dataset fornecido, então temos as seguintes colunas:

* `customerID`: ID de identificação unico de cliente
* `Churn`: Se o cliente deixou a companhia ou não
* `gender`: gênero (masculino ou feminino)
* `SeniorCitizen`: Se o cliente possui mais de 65 anos
* `Partner`: Se o cliente possui um companheiro(a) ou não
* `Dependents`: Se o cliente possui dependentes ou não
* `tenure`: período de duração do contrato
* `PhoneService`: Se possui serviço de telefonia
* `MultipleLines`: Se possui mais de uma linha
* `InternetService`: Se possui serviço de internet
* `OnlineSecurity`: Se possui uma inscrição adicional para segurança online
* `OnlineBackup`: Se possui uma inscrição adicional para realização de backup online
* `DeviceProtection`: Se possui uma assinatura adicional para proteção de aparelhos
* `TechSupport`: Se possui uma inscrição adicional para suporte técnico
* `StreamingTV`: Se possui uma inscrição de TV via Streaming
* `StreamingMovies`: Se possui inscrição de Streaming
* `Contract`: Tipo de contrato
* `PaperlessBilling`: Se o cliente prefere receber a conta online
* `PaymentMethod`: Método de pagamento
* `Charges.Monthly`: Valor total da conta do cliente por mês
* `Charges.Total`: Valor total gasto pelo cliente


Mais detalhes do processo realizado durante a análise pode ser encontrado no arquivo churn-prediction.ipynb

Tais como, quais informações foram consideradas, motivos das técnicas utilizadas, resultados esperados, resultados obtidos e pontos de melhorias.


Esse notebook foi desenvolvido para fins de estudo e aplicação de técnicas, portanto existe bastante espaço para aprimoramento, sinta-se livre para entrar em contato caso queira continuar o estudo do ponto que foi finalizado ou para sinalizar algo incorreto.