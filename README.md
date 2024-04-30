# Projeto Financeiro

O Projeto Financeiro foi desenvolvido com o objetivo de otimizar a obtenção de dados financeiros relacionados à entrega de pacotes. O projeto é dividido em três etapas, todas documentadas neste repositório:

## Etapas do Projeto

1. **Extração dos Dados**:
    - Consiste em obter informações sobre motoristas, encomendas entregues e custos associados às entregas, baseados no bairro ou cidade de destino.

2. **Tratamento dos Dados**:
    - Nessa etapa, os dados são processados para verificar valores nulos, duplicados ou inconsistentes, garantindo a integridade dos dados.

3. **Carregamento dos Dados**:
    - Os dados são transferidos para um Delta Lake no CGP, depois carregados no BigQuery para análise.

Após concluir essas etapas, foi possível responder diversas perguntas de negócios. 

## Perguntas Respondidas

1. **Quantidades de Entregas**:
    - Qual é a quantidade de produtos entregues pelos motoristas, a média dos valores transportados e o valor a receber por essas entregas? Mostre apenas os 10 primeiros resultados em ordem decrescente.

2. **Franquiados com Maior Valor de Mercadorias Entregues**:
    - Quais são os cinco franquiados com o maior valor total de mercadorias entregues nas cidades?

3. **Entregas Realizadas em 15-04-2024**:
    - Quantas entregas foram realizadas em 15-04-2024?

4. **Agregados com Maior Número de Entregas**:
    - Quais são os dez agregados com o maior número de entregas para destinatários diferentes em cidades distintas?

5. **Valor Médio de Mercadorias por Estado Remetente**:
    - Qual é o valor médio de mercadorias entregues em cada estado remetente?

Sinta-se à vontade para explorar o código-fonte e a documentação para mais detalhes sobre o projeto e suas análises.
