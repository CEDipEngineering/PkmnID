# PkmnID

## Algorítimo utilizando Random Forest machine learning para identificar qual Pokemón está na imagem:

O projeto consiste em uma aplicação de Machine Learning utilizando a linguagem de programação Python. Utilizando algumas bibliotecas como SKlearn, stats, numpy, os, entre outras; foi possível construir, um classificador de imagens. O qual, recebendo uma imagem qualquer, consegue com acurácia significativa, identificar qual seria o Pokemón que está na imagem (ou caso não haja Pokémon na imagem, com qual pokémon a imagem mais se assemelha).

## Todo o trabalho consiste nesses arquivos presentes no repositório, sendo:

## a) Data_Cleanup
 
 Arquivo responsável por transformar as imagens, obtidas pelo dataset disponível online, em imagens menores buscando melhorar o desempenho e a extração de features de cada uma. Além disso, também separa todo o dataset limpo e organizado em dois grupos: Treinamento e Teste. Por fim, executa uma rotação de cada imagem em 90 graus para assim obter mais dados diferentes para treinamento do classificador.
 
## b) Image_Reader:
 
Arquivo responsável por, após limpas as imagens no DataSet, extrair as diversas Features de cada imagem de cada Pokemón e utiliza-lás para o treinamento de fato do modelo. Dessa forma, este arquivo executa todo o classificador.
 
## c) Assets:

## Data_Filtered_Resized:

Dados (dataset) devidamente redimensionados, e filtrados inicialmente à mão, removendo imagens muito discrepantes, como por exemplo, memes de pokemóns com rosto substituído pelo de pessoas, fundos muito tumultuosos (que afetariam muito a extração de features), etc.

## temp_Test:

Dados do tamanho devido e separados para teste.

## temp_Train:

Dados do tamanho devido e separados para treinamento.

## Data_Test:

Dados do tamanho devido e adicionados os dados rotacionados separados para teste.

## Data_Train:

Dados do tamanho devido e adicionados os dados rotacionados separados para treinamento.


# Equipe:

- André Luís Silva Lopes
- Carlos Eduardo Dip
- Gianluca Lazaris Giudici
- João Pedro Andrade Gianfaldoni

# Links:

- Modelo Bag of Visual Words, e parte da análise exploratória produzidos por/com assistência de Fábio Ayres.
- Dataset: [Pokémon Gen One](https://www.kaggle.com/thedagger/pokemon-generation-one/data) da plataforma Kaggle.com
- https://scikit-learn.org/stable/auto_examples/model_selection/plot_confusion_matrix.html



