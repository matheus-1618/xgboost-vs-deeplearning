# xgboost-vs-deeplearning

## Integrantes

<div align="center" style="max-width:68rem;">
<table>
  <tr>
    <td align="center"><a href="https://github.com/matheus-1618"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/matheus-1618" width="100px;" alt=""/><br /><sub><b>Matheus Oliveira</b></sub></a><br /><a href="https://github.com/matheus-1618" title="Matheus Silva M. Oliveira"></a> Developer</td>
   <td align="center"><a href="https://github.com/niveaabreu"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/niveaabreu" width="100px;" alt=""/><br /><sub><b>Nívea de Abreu</b></sub></a><br /><a href="https://github.com/niveaabreu" title="Nívea de Abreu"></a>Developer</td>
  </tr>
</table>
</div>

## Introdução

No campo da ciência de dados, a escolha do modelo adequado para análise de dados é crucial para o sucesso das tarefas de predição. Enquanto modelos de deep learning, as famosas redes neurais, têm demonstrado desempenho excepcional em conjuntos de dados complexos como imagens e textos, a situação se mostra diferente quando lidamos com dados tabulares.

Dados tabulares, caracterizados por suas características heterogêneas, tamanhos de amostra pequenos e valores extremos, apresentam desafios específicos que impactam a eficácia dos modelos de deep learning. 

Modelos de ensemble baseados em árvores, como o XGBoost, continuam sendo a ferramenta preferida para a maioria dos profissionais de ciência de dados e competições, destacando-se na análise de dados tabulares. Esses modelos são altamente eficazes para lidar com a diversidade e irregularidades inerentes aos dados tabulares.

Por outro lado, arquiteturas de deep learning são desenvolvidas para criar vieses indutivos que correspondem a invariâncias e dependências espaciais, características mais facilmente encontradas em dados de imagens ou sequências, mas difíceis de detectar em dados tabulares.

Além disso, a avaliação de modelos de aprendizagem profunda em dados tabulares é dificultada pelo tamanho geralmente pequeno dos conjuntos de dados disponíveis, tornando a avaliação menos precisa e mais suscetível a ruídos.

A criação de um benchmark específico para dados tabulares, com uma metodologia precisa para a inclusão de datasets e ajuste de hiperparâmetros, tem sido uma resposta a essas preocupações. Esse benchmark permite avaliar modelos de deep learning recentes de maneira independente, revelando que os modelos baseados em árvores continuam a ser o estado da arte para datasets tabulares de tamanho médio, mesmo sem considerar o tempo de treinamento mais lento dos algoritmos de deep learning.

Empiricamente, a superioridade dos modelos baseados em árvores pode ser atribuída aos seus vieses indutivos implícitos, que se mostram desejáveis para o aprendizado em dados tabulares. Redes neurais, por outro lado, têm dificuldades em aprender padrões irregulares e sua invariância a rotações prejudica o desempenho, especialmente ao lidar com características não informativas.

Transformar datasets tabulares para modificar o desempenho de diferentes modelos tem revelado os vieses que favorecem os modelos de árvores, ajudando a compreender por que eles superam os modelos de deep learning e guiando a construção de arquiteturas de deep learning mais eficazes para dados tabulares.

Dessa forma, o objetivo desde projeto, é revisar os trabalhos existentes na academia, analisar metodologias utilizadas, e realizar uma pequena experimentação afim de validar se, de fato, modelos Ensemble podem apresentar desempenho maior que Redes Neurais em dados tabulares.
