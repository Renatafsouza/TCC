# Classificação de melanomas usando a visão computacional para apoio ao diagnóstico clínico
TCC de Engenharia de Software - Unb, Campus do Gama. Por Renata Francelino de Souza.

## Objetivo
Investigar técnicas de extração de característica para classificação de melanomas e auxílio ao diagnóstico clínico.
<br/>

>**Observação:** O algoritmo apresentado é uma ferramenta de apoio clínico 
>e **não** substitui o  diagnóstico realizado por um médico. 
>Em caso de suspeita de doença de pele ou qualquer patologia, consulte um profissional de saúde especializado. 
>Este trabalho é uma pesquisa acadêmica com finalidade de estudo e aprendizado.

## Instalação

O projeto foi realizado na linguagem Python no ambiente [Jupyter Notebook](https://jupyter.org/try). Para executar este projeto, você pode abrir o ambiente 
_Jupyter Lab_ e clonar o código deste repositório.

## Base de dados

A base de dados utilizada neste estudo é uma parte da base _Skin Cancer MNIST:_ HAM10000 contida na plataforma Kaggle. Acesse o link e confira: https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000.

## Técnicas exploradas

Os testes de classificação foram realizados com a ferramenta [Weka](https://www.cs.waikato.ac.nz/ml/weka/) para alguns classificadores. 
Os descritores _Bag-of-features_ (BoF) e _Local Binary Pattern_ (LBP) foram implementados e avaliada sua acurária em relação ao uso de cada
classificador simulado. 

**Saiba mais sobre pesquisas de câncer de pele**

* [O que é câncer](https://www.inca.gov.br/o-que-e-cancer)
* [Como surge o câncer?](https://www.inca.gov.br/como-surge-o-cancer)
* [Câncer de pele:  vamos falar sobre isso?](https://www.inca.gov.br/sites/ufu.sti.inca.local/files//media/document//folder-salvar-vidas-cancer-pele.pdf)
* [Skin Cancer Facts & Statistics](https://skincancer.org/skin-cancer-information/skin-cancer-facts/)

**Referências**

INCA.Câncer de pele: vamos falar sobre isso?[S.l.], 2017. Disponível em: <https://www.inca.gov.br/sites/ufu.sti.inca.local/files//media/document//folder-salvar-vidas-cancer-pele.pdf> Acessado em: 30/04/2019. 

INCA.Como surge o câncer?[S.l.], 2018. Disponível em: <https://www.inca.gov.br/tipos-de-cancer/cancer-de-pele-melanoma> Acessado em: 30/04/2019. 

INCA.O que é câncer. [S.l.], 2019. Disponível em: <https://www.inca.gov.br/o-que-e-cancer> Acessado em: 30/04/2019.

KAGGLE.Skin Cancer MNIST: HAM10000. [S.l.], 2019. Disponível em: <https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000> Acessado em: 03/10/2019.

SKIN CANCER FOUNDATION.Skin Cancer Facts and Statistics. [S.l.], 2019.Disponível em: <https://skincancer.org/skin-cancer-information/skin-cancer-facts/>Acessado em: 06/11/2019.
