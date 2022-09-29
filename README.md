# Telco-Customer-Churn

![Badge in progress](http://img.shields.io/static/v1?label=STATUS&message=IN%20PROGRESS&color=GREEN&style=for-the-badge)

#### Notebook I : [Data Cleaning](https://github.com/camilamaestrelli/Telco-Customer-Churn/blob/main/01_DataCleaning_TelcoCustomerChurn.ipynb)

#### Notebook II : [Exploratory Data Analysis with Plotly](https://github.com/camilamaestrelli/Telco-Customer-Churn/blob/main/02_EDA_TelcoCustomerChurn.ipynb)

#### Notebook III : [Machine Learning with PySpark](https://github.com/camilamaestrelli/Telco-Customer-Churn/blob/main/03_ML_TelcoCustomerChurn.ipynb)


#### Dicionário de dados

<b>Cliente:</b>
 
* `gender`: gênero (masculino e feminino)
* `SeniorCitizen`: informação sobre um cliente ter ou não idade igual ou maior que 65 anos
* `Partner`: se o cliente possui ou não um parceiro ou parceira
* `Dependents`: se o cliente possui ou não dependentes

<b>Serviço de telefonia</b>


 * `tenure`: meses de contrato do cliente
 * `PhoneService`: assinatura de serviço telefônico
 * `MultipleLines`: assisnatura de mais de uma linha de telefone
 

<b>Serviço de internet</b>


 * `InternetService`: assinatura de um provedor internet
 * `OnlineSecurity`: assinatura adicional de segurança online
 * `OnlineBackup`: assinatura adicional de backup online
 * `DeviceProtection`: assinatura adicional de proteção no dispositivo
 * `TechSupport`: assinatura adicional de suporte técnico, menos tempo de espera
 * `StreamingTV`: assinatura de TV a cabo
 * `StreamingMovies`: assinatura de streaming de filmes


<b>Contrato</b>


 * `Contract`: tipo de contrato
 * `PaperlessBilling`: se o cliente prefere receber online a fatura
 * `PaymentMethod`: forma de pagamento
 * `Charges.Monthly`: total de todos os serviços do cliente por mês
 * `Charges.Total`: total gasto pelo cliente
