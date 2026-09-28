
# Miniguia de Estudos: Machine Learning Aplicado a Dados
## Contexto e Objetivos

Este projeto foi desenvolvido como parte de um bootcamp da DIO, utilizando o NotebookLM como ferramenta de apoio aos estudos. O tema escolhido foi Machine Learning aplicado a Dados.

O objetivo é aprofundar conceitos de Machine Learning que ainda não domino e compreender sua aplicação na área de dados, desenvolvendo conhecimentos importantes para minha formação e para a construção da minha carreira como profissional de dados.

# Curadoria de Fontes

As fontes abaixo foram selecionadas como material de estudo e utilizadas no NotebookLM, além de outras 26 fontes, entre elas artigos e videos do youtube:

* [Material de estudo — Blucher](https://storage.blucher.com.br/book/pdf_preview/9786555063967-amostra.pdf)
* [Material de estudo — ENAP](https://repositorio.enap.gov.br/server/api/core/bitstreams/eef97893-1eda-4b04-9a3e-590ff253a62d/content)
* [Machine Learning e Python: um guia prático à ciência de dados — ResearchGate](https://www.researchgate.net/publication/369179315_Machine_Learning_e_Python_um_guia_pratico_a_ciencia_de_dados)

## Engenharia de Prompts

Durante o projeto, utilizei diferentes prompts no NotebookLM para explorar os fundamentos de Machine Learning e aprofundar conceitos importantes para a área de Dados.

**Prompt 1:**

> Como Machine Learning pode ser aplicado na análise de dados?

**Resumo da resposta obtida:**

O Machine Learning pode ampliar a análise de dados ao identificar padrões e realizar previsões a partir de dados históricos. Entre suas aplicações estão **classificação, regressão, agrupamento, redução de dimensionalidade e detecção de anomalias**. A preparação dos dados, inclui **limpeza, tratamento de valores ausentes, seleção e criação de atributos, normalização e divisão dos dados para treinamento e teste**.


**Prompt 2 :**

>Como a qualidade e o tratamento dos dados influenciam um modelo de Machine Learning?

**Resumo da resposta obtida:**

A qualidade dos dados influencia diretamente a capacidade do modelo de aprender padrões reais e gerar previsões confiáveis. Dados incorretos, incompletos, enviesados ou desbalanceados podem prejudicar os resultados e fazer com que o modelo aprenda padrões inadequados. Além disso a importância de etapas como tratamento de valores ausentes e outliers, normalização e padronização, seleção e engenharia de atributos e divisão dos dados em treino e teste.

**Prompt 3 :**

> Como preparar um conjunto de dados para treinar um modelo?

**Resumo da resposta obtida:**

A preparação dos dados envolve várias etapas, começando pelo **entendimento do problema e identificação das features e da variável-alvo**. Em seguida, são realizadas etapas de **análise exploratória, limpeza, tratamento de valores ausentes e outliers e tratamento de classes desbalanceadas**. Também podem ser necessárias transformações como **normalização, padronização e codificação de variáveis categóricas**, além de seleção e engenharia de atributos. Por fim, os dados são separados em **treino e teste**, podendo utilizar técnicas como validação cruzada para avaliar a capacidade de generalização do modelo.

**Prompt 4 :**

>Crie um resumo breve e didático sobre o uso de Machine Learning na área de Dados. Explique os principais benefícios de utilizar Machine Learning em projetos de dados, quais profissionais da área de Dados costumam utilizar esses conhecimentos e em quais situações. Apresente também os principais conceitos e métricas de Machine Learning que um profissional de Dados deve conhecer, explicando brevemente cada um. Organize a resposta de forma objetiva e utilize exclusivamente as fontes deste caderno.

**Resumo da resposta obtida:**

O Machine Learning permite automatizar análises, identificar padrões em grandes volumes de dados e realizar previsões a partir de dados históricos. Seus conhecimentos podem ser utilizados por diferentes profissionais, como Cientistas de Dados, Analistas de Dados, Engenheiros de Dados e profissionais de Machine Learning. Entre os principais conceitos estão features, target, treino e teste, overfitting, underfitting e trade-off viés-variância. Para avaliar modelos, destacam-se métricas como acurácia, precisão, recall e F1-Score em classificação, e MAE, MSE, RMSE e R² em regressão.
 
 ## Troubleshooting

Durante os estudos, percebi que algumas respostas do NotebookLM eram muito extensas ou apresentavam conceitos de forma mais técnica do que eu precisava naquele momento. Para obter respostas mais adequadas ao meu objetivo, precisei refinar os prompts, especificando que queria explicações breves, didáticas, com exemplos práticos e voltadas para quem está iniciando na área de Dados. E portanto precisei resumir algumas respostas. Também foi necessário fazer perguntas complementares para aprofundar conceitos que não ficaram claros nas primeiras respostas. 

## Outros recursos utilizados

Além do chat, foram utilizados outros recursos disponíveis no NotebookLM para complementar os estudos, como **mapa mental, apresentação de slides e teste de conhecimentos**.

**Materiais gerados:**

Os materiais abaixo contém um mapa mental, uma apresentação de slides, um vídeo curto sobre pseudo-rotulagem e aprendizado semi-supervisionado, e um infográfico explicativo de separação de dados para teste e treino. Esses materiais foram gerados durante o processo de estudo utilizando os recursos do NotebookLM.

📁 [Acessar materiais gerados](https://drive.google.com/drive/folders/1sK2LEYL_WZrMLQF_QESZaU0Qk-kfOiLE?usp=drive_link)

## Miniguia de Estudo

### Resumo
Machine Learning é uma área da Inteligência Artificial que permite que sistemas aprendam padrões a partir de dados para realizar previsões, classificações ou identificar estruturas nos dados. Na área de Dados, pode ser aplicado em problemas como previsão de vendas, segmentação de clientes, detecção de fraudes e recomendações. O desenvolvimento de modelos depende da qualidade dos dados e envolve etapas como **limpeza, tratamento, preparação, seleção de atributos, treinamento e avaliação**. Entre os principais conceitos estão treino e teste, features, target, overfitting e underfitting.

### Glossário

| Conceito                 | Definição                                                                 |
| ------------------------ | ------------------------------------------------------------------------- |
| **Feature**              | Variável utilizada como entrada para o modelo.                            |
| **Target**               | Variável que o modelo busca prever.                                       |
| **Treinamento**          | Processo no qual o modelo aprende padrões a partir dos dados.             |
| **Teste**                | Avaliação do modelo utilizando dados que não foram usados no treinamento. |
| **Overfitting**          | Quando o modelo se adapta excessivamente aos dados de treinamento.        |
| **Underfitting**         | Quando o modelo é simples demais para aprender os padrões dos dados.      |
| **Classificação**        | Predição de categorias ou classes.                                        |
| **Regressão**            | Predição de valores numéricos.                                            |
| **Clustering**           | Agrupamento de dados semelhantes.                                         |
| **Precisão (Precision)** | Proporção de previsões positivas que estavam corretas.                    |
| **Recall**               | Proporção dos casos positivos reais identificados pelo modelo.            |
| **F1-Score**             | Métrica que combina Precision e Recall.                                   |
| **MAE**                  | Média dos erros absolutos de um modelo de regressão.                      |
| **RMSE**                 | Métrica de erro que penaliza mais fortemente erros maiores.               |
| **R²**                   | Mede quanto da variação dos dados é explicada pelo modelo.                |

### Prompts reutilizáveis

* **Revisão:** "Explique os principais conceitos de Machine Learning de forma breve e didática, utilizando exemplos relacionados à área de Dados."

* **Aprofundamento:** "Explique [CONCEITO] de forma simples, apresente um exemplo prático e explique sua importância para um profissional de Dados."

* **Comparação:** "Compare [CONCEITO A] e [CONCEITO B], apresentando suas diferenças, aplicações e exemplos."

* **Teste:** "Crie um teste com perguntas sobre [TEMA], variando entre questões conceituais e situações práticas. Ao final, apresente o gabarito e explique as respostas."

* **Revisão completa:** "Faça uma revisão dos principais conceitos de Machine Learning que um profissional de Dados deve conhecer, destacando os pontos mais importantes e possíveis dúvidas."
