# Previsão de Preços de Criptomoedas

Este projeto é uma aplicação de previsão de preços de criptomoedas desenvolvida com Python, utilizando machine learning e uma interface web interativa.

## Objetivo

O objetivo deste projeto é fornecer aos usuários uma ferramenta para prever os preços de criptomoedas com base em dados históricos. Isso é alcançado através do desenvolvimento de um modelo de machine learning treinado com dados históricos de preços, volume de negociação e capitalização de mercado. Além disso, uma interface web foi construída para permitir que os usuários insiram uma data específica e obtenham uma previsão do preço da criptomoeda para essa data.

## Funcionalidades

* Previsão de preços de criptomoedas para uma data específica.
* Interface web interativa para facilitar o uso.
* Suporte para diferentes criptomoedas.
* Atualizações regulares dos dados para manter a precisão das previsões.

## Como Usar

1. Clone o repositório em sua máquina local.
2. Instale as dependências listadas no arquivo requirements.txt.
3. Execute a aplicação web executando o arquivo app.py.
4. Acesse a interface web através do navegador e insira uma data para obter uma previsão do preço da criptomoeda.

## Conteúdo dos Dados

Os dados utilizados para treinar o modelo foram extraídos da API da CoinGecko e estão disponíveis diariamente desde 1º de janeiro de 2015. As informações contidas nos dados incluem a data da observação, o preço na data e hora determinadas, o volume total de transações em um determinado dia e a capitalização de mercado em dólares americanos.

## Tecnologias Utilizadas

* Python
* Flask
* Pandas
* Scikit-learn
* HTML/CSS

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias ou correções.

## Licença

Este projeto está licenciado sob a MIT License.