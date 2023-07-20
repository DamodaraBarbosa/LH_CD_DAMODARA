# PREVISÃO DOS PREÇOS DE VEÍCULOS DA LIGHTHOUSE

O seguinte projeto tem por objetivo modelar os dados da Lighthouse a fim de desenvolver um modelo de *machine learning* para previsão dos preços dos veículos.
Para isso, foram testados diferentes modelos de regressão, desde a regressão linear simples, mas também modelos baseados em árvore de decisão, para atingir o melhor
desempenho.

## Sobre os arquivos

Este repositório contém os arquivos:

> * `01_estatisticas_e_analise_exploratoria_dos_dados`:  *notebook* produzido no *Google Colab* que contém informações sobre o conjunto de dados, as principais estatísticas
das *features* e análise exploratória dos dados com uso de ferramentas de visualização. Além disso, também possui as hipóteses de negócio levantadas.
>
> * `02_modelo_predicao_preco_carros`: desenvolvimento do modelo de *machine learning* supervisionado para resolução de um problema de regressão. Tratamento dos dados,
> seleção do melhor modelo e previsão dos dados. Por fim, os dados previstos foram exportados.
>
> * `predicted.csv`: contém as **ids** dos veículos e os preços previstos pelo modelo de regressão.
>
> * `requirements.txt`: arquivo de texto com as ferramentas, e suas respectivas versões, que foram utilizadas no desenvolvimento do projeto.

## Como executar?

Os relatórios e códigos da modelagem foram desenvolvidos no ambiente do *Google Colab*. Portanto, são *notebooks*, arquivo no formato *.ipynb*. Tais arquivos podem ser
baixados deste repositório e executados ou no próprio *Google Colab*, no ambiente do *Jupyter Notebook* da extensão Anaconda, ou até mesmo no *VSCode* a partir da extensão
para executar *notebooks*.

* *Download* do arquivo *.ipynb*:
  
![image](https://github.com/DamodaraBarbosa/LH_CD_DAMODARA/assets/107199898/9791af44-0068-4ed9-a549-d016986f2212)

* *Upload* e execução no *Google Colab*:

![image](https://github.com/DamodaraBarbosa/LH_CD_DAMODARA/assets/107199898/d1c50b19-c798-41e4-afee-4c94d4abdbfa)

## O que precisa ser instalado?

A maior parte das ferramentas utilizadas já estão instaladas no ambiente do *Google Colab*, as versões são mostradas no arquivo `requirements.txt`. No entanto, apenas
duas bibliotecas devem ser instaladas para execução do **modelo de regressão**: `category-encoders` e `catboost`. A primeira para realizar o pré-processamento
das variáveis categóricas e a segunda para executar um dos modelos que foram testados. Para instalação:

* `category-encoders`:
  
```
!pip install category-encoders
```

* `catboost`:
  
```
!pip install catboost
```

### Desenvolvido por:

Damodara Barbosa, Cientista de Dados e Instrutor de Ciência de Dados

LinkedIn: https://www.linkedin.com/in/damodarabarbosa/
