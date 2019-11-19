  PkmnID

## Algorítimo utilizando Random Forest machine learning para identificar qual Pokemón está na imagem:

O projeto consiste em uma aplicação de Machine Learning utilizando a linguagem de programação Python. Utilizando algumas bibliotecas como SKlearn, stats e principalmente Random Forest Classifier; foi possível construir, basicamente, um classificador de imagens. O qual, recebe uma imagem qualquer de um Pokemón qualquer, consegue com acurácia significativa identificar qual seria o Pokemón que está na imagem.

## Todo o trabalho consiste nesses arquivos presentes no repositório, sendo:

## a) Data_Cleanup
 
 Arquivo responsável por transformar as imagens, obtidas pelo DataSet disponível online, em imagens menores buscando melhorar o desempenho e a extração de features de cada uma. Além disso, executa uma rotação de cada imagem em 90 graus para assim obter mais dados diferentes para trfeinamento do classificador. Por fim, também como parte essencial do projeto, separa todo o DataSet limpo e organizado em dois grupos: Treinamento e Teste.
 
## b) Image_Reader:
 
 Arquivo responsável por, após limpas as imagens no DataSet, extrair as diversas Features de cada imagem de cada Pokemón e utiliza-lás para a confecção de fato do modelo. Dessa forma, este arquivo executa todo o classificador; utilizando dados para treino do modelo e depois de elaborado. Utiliza os dados para teste do mesmo; ao final indicando a sua acurácia. (Todo o processo de construção do classifier codada no arquivo /// main-file)
 
## c) Assets:

## Data_Filtered_Resized:

Dados (DataSet) devidamente redimensionados

## temp_Test:

Dados do tamanho devido e separados para teste

## temp_Train:

Dados do tamanho devido e separados para treinamento

## Data_Test:

Dados do tamanho devido e adiconados os dados rotacionados separados para teste

## Data_Train:

Dados do tamanho devido e adiconados os dados rotacionados separados para teste


