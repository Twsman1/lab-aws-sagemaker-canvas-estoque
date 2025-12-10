# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

- Optei pela criação de um novo dataset criado com auxilio do Chat-GPT contendo 5000 entradas referentes a um controle de estoque de peças automotivas.

### 2. Construir/Treinar

- O modelo foi construido com base em previsão númerica ao inves de previsão temporal levando em consideração o numero de entradas e saidas de cada peça.
- Usando com base o tipo de modelagem Quick Build que tende a ser mais rápido porem pode pecar um pouco na acuracia do resultado final.
- Após concluido o modelo demonstrou uma analise não muito precisa por se tratarem de dados aleatorios.

### 3. Analisar

-  O modelo obteve um RMSE de 22 e um MSE de 499. Indicando um mal refinamento.
-  Quando menor o RMSE mais preciso seria o resultado em variação as quantidade de estoque sendo assim ele indiciaria uma media de 22 unidades por peça no estoque.
-  O modelo indicou que as datas possuiam maior relevancia no refinamento em seguida o item em especifico.

### 4. Prever

- Foram realizadas algumas prediçoes para teste que estarão na pasta imagens deste repositorio

