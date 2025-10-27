<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> DIO :: BairesDev - Machine Learning Training</span>
</h1>

## Sobre o Projeto

Página desenvolvida para fins didáticos para o desafio - `Cálculo de Métricas de Avaliação de Aprendizado ` do bootcamp **BairesDev - Machine Learning Training** da [Digital Innovation One](https://www.dio.me/). 

## Tecnologias

![PYTHON](https://img.shields.io/badge/PYTHON-000?style=for-the-badge&logo=python&logoColor=30A3DC)

## O Desafio

Cálculo de Métricas de Avaliação de Aprendizado 

Neste projeto, vamos calcular as principais métricas para avaliação de modelos de classificação de dados, como acurácia, sensibilidade (recall), especificidade, precisão e F-score. Para que seja possível implementar estas funções, você deve utilizar os métodos e suas fórmulas correspondentes (tabela 1). 

Para a leitura dos valores de VP, VN, FP e FN, será necessário escolher uma matriz de confusão para a base dos cálculos. Essa matriz você pode escolher de forma arbitraria, pois nosso objetivo é entender como funciona cada métrica.  

<table>
    <tr>
        <th>Método</th>
        <th>Fórmula</th>
    </tr>
    <tr>
        <td>Sensibilidade</td>
        <td>VP / (VP + FN)</td>
    </tr>
    <tr>
        <td>Especificidade</td>
        <td> VN / (VN + FP)</td>
    </tr>
    <tr>
        <td>Acurácia</td>
        <td>(VP + VN) / (VP + VN + FP + FN)</td>
    </tr>
    <tr>
        <td>Precisão</td>
        <td>VP / (VP + FP)</td>
    </tr>
    <tr>
        <td>F-score</td>
        <td>(2 \* VP) / (2 \* VP + FP + FN)</td>
    </tr>
</table>

_Tabela 1: Visão geral das métricas usadas para avaliar métodos de classificação. VP: verdadeiros positivos; FN: falsos negativos; FP: falsos positivos; VN: verdadeiros negativos; P: precisão; S: sensibilidade; N: total de elementos._
 