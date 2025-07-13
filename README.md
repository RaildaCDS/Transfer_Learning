# Horses vs Humans - Classificador com Transfer Learning 🐴🧍‍♂️

Este projeto usa Transfer Learning com MobileNetV2 para classificar imagens entre **cavalos** e **humanos**, usando a base de dados do TensorFlow Datasets.

## 🚀 Tecnologias
- TensorFlow
- Python
- Matplotlib
- Google Colab

## 📊 Resultados
Acurácia de validação superior a 98% após 5 épocas.

[Abrir no Google Colab](https://colab.research.google.com/drive/1BFc2LMmFVU7pkTridtcKnUdv58XqtByh?usp=sharing)


![Transfer Learning](https://github.com/RaildaCDS/Transfer_Learning/raw/main/imgns/tranfer.png)

## 📊 Interpretação dos gráficos:
1. Gráfico da Acurácia (à esquerda)
O que vemos:

 A acurácia de treinamento sobe rapidamente e chega perto de 100% logo na 2ª época.

 A acurácia de validação também sobe, mas se estabiliza por volta de 98%.

 O que isso indica:

 ✅ O modelo está aprendendo muito bem no treino.
 
 ✅ A validação segue bem próxima, o que é um ótimo sinal.

❗ A pequena diferença entre treino e validação pode indicar um leve overfitting — mas não é grave (está sob controle).

 2. Gráfico da Perda (Loss) (à direita)
 O que vemos:

 A perda de treinamento cai rapidamente e se estabiliza perto de zero.

 A perda de validação também diminui, mas em um ritmo mais lento e se estabiliza.

 O que isso indica:

 ✅ O modelo está minimizando erros consistentemente.

❗ A diferença entre a perda de treino e validação sugere que o modelo está começando a memorizar o conjunto de treino um pouco mais do que generalizar.


## 📁 Estrutura
- `notebooks/`: Notebook principal com todo o código
- `imgns/`: Resultados visuais (gráficos)


