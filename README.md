# 🤖 Análise de Classificação de Spam com Machine Learning

## 📖 Sobre o Projeto

Este repositório documenta uma jornada prática e educacional na construção de um modelo de machine learning para classificar e-mails como SPAM ou NÃO SPAM. O projeto foi desenvolvido a partir de um pequeno conjunto de dados manual e serve como um estudo de caso para explorar os desafios e as soluções de problemas de classificação com machine learning, especialmente com recursos de dados limitados.

O objetivo principal não é criar o filtro de spam mais preciso do mundo, mas sim **entender como diferentes algoritmos funcionam, suas limitações e o papel crucial dos dados no sucesso de um modelo**.

## 🚀 Notebooks e Experimentos

O projeto é dividido em cinco notebooks, cada um focado em um aspecto diferente da construção do modelo.

1.  **`01_Classificacao_Spam_Naives_Bayes.ipynb`**
    * **Propósito:** Estabelecer a linha de base (baseline) do nosso projeto usando um dos algoritmos mais clássicos e eficientes para detecção de spam.
    * **Aprendizado:** Entender os conceitos de classificação binária, as suposições do Naïve Bayes e a importância da Acurácia e Matriz de Confusão.

2.  **`02_Otimizacao_Limiar_Spam.ipynb`**
    * **Propósito:** Otimizar o modelo de Naïve Bayes sem adicionar novos dados, ajustando o limiar de probabilidade para reduzir Falsos Positivos.
    * **Aprendizado:** Descobrir que a acurácia nem sempre é a melhor métrica e que o ajuste de hiperparâmetros (como o limiar) é crucial para alinhar o modelo com as necessidades do negócio.

3.  **`03_Modelo_Semi_Supervisionado.ipynb`**
    * **Propósito:** Explorar uma abordagem alternativa de aprendizado (semi-supervisionado) para cenários com poucos dados rotulados, simulando a adição de dados não rotulados.
    * **Aprendizado:** Entender a diferença entre modelos supervisionados e semi-supervisionados e as limitações de ambos quando a base de dados rotulada é insuficiente.

4.  **`04_Arvore_Decisao_para_Classificacao.ipynb`**
    * **Propósito:** Testar a Árvore de Decisão, um modelo supervisionado baseado em regras, para entender como ele lida com a classificação em um cenário de dados limitados.
    * **Aprendizado:** Observar como um modelo focado em regras simples pode falhar em generalizar quando não tem exemplos suficientes.

5.  **`05_Random_Forest_para_Classificacao.ipynb`**
    * **Propósito:** Avaliar um modelo mais complexo e poderoso (Random Forest) para ver se ele consegue superar o desempenho dos modelos anteriores com o mesmo conjunto de dados.
    * **Aprendizado:** Concluir que a complexidade do algoritmo não garante melhor performance se a base de dados for pequena.

## 📈 Conclusões Principais

Após testar cinco abordagens diferentes, as principais conclusões do projeto são:

1.  **Os Dados são o Fator Limitante:** A performance do modelo, independentemente do algoritmo, foi diretamente limitada pela quantidade e variedade dos dados de treinamento.
2.  **A Simplicidade Venceu:** O modelo mais simples, **Naïve Bayes**, teve o melhor desempenho, mostrando que, para conjuntos de dados pequenos e específicos, uma abordagem menos complexa pode ser a mais eficaz.
3.  **A Matriz de Confusão é Essencial:** A análise da matriz de confusão foi fundamental para identificar o problema real do nosso modelo (Falsos Positivos), algo que a acurácia sozinha não revelaria.

Este projeto é um excelente lembrete de que um cientista de dados não se resume a escolher o algoritmo mais sofisticado, mas sim a entender profundamente os dados e as limitações do problema em questão.

## 🛠️ Requisitos

Para rodar os notebooks, você precisará das seguintes bibliotecas Python:
* `pandas`
* `scikit-learn`
* `numpy`
* `graphviz` (para visualizar a Árvore de Decisão)

## 🤝 Como Contribuir

Sinta-se à vontade para clonar este repositório, testar com seus próprios dados ou sugerir melhorias.

---
Feito com ❤️ por [Seu Nome]
