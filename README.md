# Autores do Projeto

- https://github.com/GabrielNFR
- https://github.com/juanbrazz

# Análise de Churn de Clientes

Este projeto visa analisar os fatores que influenciam a retenção e a saída de clientes de uma empresa, identificando perfis de clientes que são mais propensos a sair e recomendando estratégias para melhorar a retenção.

## Objetivo

O objetivo deste projeto é explorar as características dos clientes que permaneceram e dos que saíram, compreendendo quais fatores, como idade, gênero, nacionalidade, saldo, tipo de cartão de crédito, e status de atividade influenciam na decisão de saída ou retenção.

## Conjunto de Dados

O conjunto de dados utilizado neste projeto é o Customer-Churn-Records.csv, que contém informações detalhadas sobre os clientes, incluindo idade, gênero, saldo, status de atividade, e status de saída.
Aqui está o link para a base de dados utilizada: https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn

## Link para os Artigos

- Parte 1: https://medium.com/@skicklel/bank-customer-churn-analysis-part-1-54765740f129
- Parte 2: https://medium.com/@jfcbdo/customer-bank-churn-analysis-part-2-170268105301
- Parte 3: https://medium.com/@jfcbdo/customer-churn-bank-analysis-part-3-418ec467957b

### Variáveis

- RowNumber — corresponde ao número do registro (linha) e não tem efeito na saída.
- CustomerId — contém valores aleatórios e não tem efeito na saída do cliente do banco.
- Surname — o sobrenome de um cliente não tem impacto na decisão de deixar o banco.
- CreditScore — pode ter efeito na rotatividade de clientes, já que um cliente com uma pontuação de crédito mais alta tem menos probabilidade de deixar o banco.
- Geography — a localização de um cliente pode afetar sua decisão de deixar o banco.
- Gender — é interessante explorar se o gênero desempenha um papel na saída de um cliente do banco.
- Age — isso é certamente relevante, já que clientes mais velhos têm menos probabilidade de deixar o banco do que os mais jovens.
- Tenure — refere-se ao número de anos que o cliente é cliente do banco. Normalmente, clientes mais velhos são mais leais e menos propensos a deixar o banco.
- Balance — também um ótimo indicador de rotatividade de clientes, já que pessoas com um saldo maior em suas contas têm menos probabilidade de deixar o banco em comparação com aquelas com saldos menores.
- NumOfProducts — refere-se ao número de produtos que um cliente comprou por meio do banco.
- HasCrCard — indica se um cliente tem ou não um cartão de crédito. Esta coluna também é relevante, pois pessoas com cartão de crédito têm menos probabilidade de deixar o banco.
- IsActiveMember — clientes ativos têm menos probabilidade de deixar o banco.
- EstimatedSalary — assim como com balance, pessoas com salários mais baixos têm mais probabilidade de deixar o banco em comparação com aquelas com salários mais altos.
- Exited — se o cliente deixou ou não o banco.
- Complain — o cliente tem reclamação ou não.
- Satisfaction Score — pontuação fornecida pelo cliente para a resolução de sua reclamação.
- Card Type — tipo de cartão mantido pelo cliente.
- Points Earned — os pontos ganhos pelo cliente por usar o cartão de crédito.

## Principais Descobertas

Algumas das descobertas principais incluem:

- Clientes de *28 a 42 anos* são os mais ativos. Dentro desse grupo, *clientes com 35 anos* têm maior probabilidade de permanecer, enquanto *clientes com 40 anos* tendem a sair com maior frequência.
- *Clientes com saldo baixo* tendem a permanecer, enquanto aqueles com saldo entre *$120,000–$150,000* têm maior probabilidade de sair.
- *Clientes do gênero feminino* tendem a sair mais do que clientes do gênero masculino.
- *Clientes com cartão de crédito* são mais propensos a permanecer, enquanto clientes sem cartão têm maior probabilidade de sair.
- *Clientes inativos* são mais propensos a sair, enquanto clientes ativos tendem a permanecer.

## Requisitos

Para rodar este projeto, você precisará das seguintes bibliotecas:

- pandas
- numpy
- matplotlib
- seaborn
