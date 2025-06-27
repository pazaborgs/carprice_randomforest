# Previsão de Preços de Carros Usados 🚗

Este projeto demonstra na prática como usar o algoritmo Random Forest para estimar o preço de revenda de veículos com base em características como quilometragem, ano de fabricação, potência, entre outras. O dataset utilizado é o **Used Cars Price Prediction**, e abrange desde o pré-processamento até a avaliação do modelo e visualizações finais.

## Objetivo

Demonstrar o uso de regressão em um problema real, aplicando conceitos como:

- Criação de variáveis dummies.
- Normalização das features numéricas.
- Divisão dos dados em treino e validação.
- Treinamento de um modelo de Random Forest.
- Avaliação da performance com métricas de regressão.

## O Dataset

O conjunto de dados utilizado é o [Used Cars Price Prediction](https://www.kaggle.com/datasets/avikasliwal/used-cars-price-prediction), criado por **avikasliwal** e disponibilizado na plataforma Kaggle. Ele contém:

- **6.019 amostras** de carros usados.
- Variáveis categóricas e numéricas, incluindo: Localização, Tipo de combustível, Quilometragem...
- **Variável alvo**: O target é preço de revenda do veículo.

---

## Executando o Código

Clone este repositório ou baixe o notebook abaixo:

```bash
git clone https://github.com/pazaborgs/carprice_randomforest
cd carprice_randomforest
```

Instale as dependências:
```bash
pip install -r requirements.txt
```
Abra o arquivo com Jupyter Notebook ou ferramenta a sua escolha (Colab...):
```bash
jupyter notebook carprice_randomforest.ipynb
```

