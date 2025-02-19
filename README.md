# 📊 Métricas de Avaliação de Modelos de Classificação

Este projeto implementa e calcula métricas essenciais para avaliação de modelos de classificação, como **Acurácia**, **Sensibilidade (Recall)**, **Especificidade**, **Precisão** e **F-Score**. O objetivo é entender como essas métricas funcionam na prática utilizando Python no **Google Colab**.

---

## 🧠 **Objetivo do Projeto**
Compreender e implementar as principais métricas utilizadas na avaliação de modelos de classificação, explorando seus cálculos a partir de uma matriz de confusão.

Estas métricas são ferramentas fundamentais na área de **Machine Learning**, ajudando a determinar a eficácia de um modelo em prever classes corretamente.

---

## 📋 **Métricas Calculadas**

### 1️⃣ Acurácia  
Proporção de previsões corretas em relação ao total.  
\[
\text{Acurácia} = \frac{VP + VN}{VP + VN + FP + FN}
\]

### 2️⃣ Sensibilidade (Recall)  
Proporção de positivos identificados corretamente.  
\[
\text{Sensibilidade} = \frac{VP}{VP + FN}
\]

### 3️⃣ Especificidade  
Proporção de negativos identificados corretamente.  
\[
\text{Especificidade} = \frac{VN}{VN + FP}
\]

### 4️⃣ Precisão  
Proporção de verdadeiros positivos entre todas as previsões positivas.  
\[
\text{Precisão} = \frac{VP}{VP + FP}
\]

### 5️⃣ F-Score  
Média harmônica entre precisão e sensibilidade.  
\[
\text{F-Score} = 2 \times \frac{\text{Precisão} \times \text{Sensibilidade}}{\text{Precisão} + \text{Sensibilidade}}
\]

---

## 📂 **Estrutura do Repositório**

- `metricas_classificacao.ipynb`: Notebook contendo o código Python e as explicações sobre o cálculo das métricas.
- `README.md`: Documentação do projeto.

---

## 🚀 **Como Rodar o Projeto**

1. **Clone o Repositório**
   ```bash
   git clone https://github.com/seu-usuario/metricas-avaliacao-classificacao.git
   ```

2. **Abra no Google Colab**
   - Faça upload do arquivo `metricas_classificacao.ipynb` ou abra diretamente no Colab.

3. **Execute as Células**
   - Teste o notebook com a matriz de confusão fornecida ou insira novos dados.

---

## 📈 **Exemplo de Resultados**

Para a matriz de confusão arbitrária abaixo:  
```plaintext
[[40, 10], 
 [5, 45]]
```

As métricas calculadas foram:

- **Acurácia**: 0.85  
- **Sensibilidade (Recall)**: 0.90  
- **Especificidade**: 0.80  
- **Precisão**: 0.81  
- **F-Score**: 0.85  

---

## 🛠 **Tecnologias Utilizadas**

- **Python**: Linguagem de programação.
- **Google Colab**: Ambiente de desenvolvimento colaborativo.
- **Scikit-learn**: Biblioteca para criar a matriz de confusão.
- **Numpy**: Para cálculos matemáticos.

---

## 🤝 **Contribuindo**

Contribuições são bem-vindas! Caso encontre problemas ou tenha ideias de melhoria, sinta-se à vontade para:

1. Abrir uma **issue**.  
2. Enviar um **pull request**.  
