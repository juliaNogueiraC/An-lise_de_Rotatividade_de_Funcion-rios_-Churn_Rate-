# Análise da Rotatividade de Funcionários

Este projeto tem como objetivo analisar a rotatividade de funcionários em uma empresa, identificando padrões e fatores que possam influenciar na saída dos colaboradores. Utilizaremos técnicas de análise de dados e aprendizado de máquina para construir um modelo preditivo que possa prever a probabilidade de um funcionário deixar a empresa.

## Objetivos do Projeto

1. Coletar e carregar os dados de funcionários de um arquivo CSV.
2. Explorar e limpar os dados, identificando e tratando valores ausentes e inconsistentes.
3. Realizar uma análise exploratória detalhada dos dados para entender a distribuição das variáveis e identificar possíveis padrões.
4. Engenharia de características para selecionar e transformar as variáveis mais relevantes para o modelo preditivo.
5. Construir e avaliar um modelo de aprendizado de máquina que preveja a rotatividade dos funcionários com base nas características disponíveis.
6. Criar visualizações para comunicar insights e resultados de forma clara e eficaz.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

- `data/`: Pasta contendo o arquivo CSV com os dados dos funcionários (`employee_data.csv`).
- `notebooks/`: Pasta contendo os notebooks Jupyter utilizados para análise exploratória, engenharia de características e construção do modelo preditivo.
- `scripts/`: Pasta contendo scripts Python para funções auxiliares e pré-processamento de dados.
- `results/`: Pasta para armazenar os resultados intermediários e finais, como modelos treinados e visualizações.
- `README.md`: Documentação detalhada do projeto, incluindo informações sobre o dataset, etapas do projeto e resultados.

## Como Utilizar

1. Clone este repositório em sua máquina local:
````
git clone https://github.com/seu-usuario/análise-rotatividade-funcionários.git

````
2. Instale as dependências necessárias:
```
pip install -r requirements.txt

````

3. Explore os notebooks Jupyter na pasta `notebooks/` para entender as etapas do projeto e executar as análises.

4. Execute os scripts Python na pasta `scripts/` conforme necessário para pré-processamento de dados e outras tarefas.

5. Documente suas descobertas, resultados e conclusões no arquivo `README.md`.

## Dataset

O arquivo `employee_data.csv` contém os seguintes atributos dos funcionários:

- `EmployeeID`: Identificação única do funcionário.
- `Age`: Idade do funcionário.
- `Department`: Departamento em que o funcionário trabalha.
- `YearsAtCompany`: Número de anos que o funcionário está na empresa.
- `JobSatisfaction`: Nível de satisfação no trabalho (escala de 1 a 5).
- `Attrition`: Indicação de rotatividade do funcionário (Yes ou No).

## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas, tiver sugestões ou quiser adicionar novos recursos, fique à vontade para abrir uma issue ou enviar um pull request.

## Autores

- [Julia Nogueira](https://github.com/juliaNogueiraC)


