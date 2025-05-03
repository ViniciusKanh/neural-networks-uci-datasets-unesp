# 🧠 Trabalho 2 – Computação Inspirada pela Natureza (2024)

Este repositório contém a implementação e análise dos experimentos do Trabalho 2 da disciplina de **Computação Inspirada pela Natureza**, com foco em **redes neurais artificiais** aplicadas a problemas clássicos de classificação.

## 📚 Descrição Geral

O trabalho é dividido em três exercícios, cada um com foco em um dataset e técnica específica de aprendizado supervisionado:

| Exercício | Dataset              | Técnica Utilizada              | Objetivo                             |
|----------|----------------------|-------------------------------|--------------------------------------|
| 1        | Iris                 | Perceptron One-vs-Rest (OvR)  | Classificação multiclasse linear     |
| 2        | Wine                 | Perceptron One-vs-Rest (OvR)  | Avaliação de separabilidade linear   |
| 3        | Breast Cancer (Wisconsin) | MLP (com e sem Dropout) | Comparação entre arquiteturas de redes neurais |

---

## 📦 Tecnologias Utilizadas

- Python 3.11
- Google Colab / Jupyter
- Bibliotecas:
  - `numpy`, `pandas`, `matplotlib`, `scikit-learn`
  - `tensorflow`, `keras`

---

## 🧪 Estrutura dos Arquivos

- `Trabalho 2.ipynb` – Notebook com todos os códigos, gráficos, interpretações e resultados.
- `Trabalho 2.pdf` – Relatório final exportado com comentários científicos em Markdown.
- `README.md` – Este documento com instruções e descrição do projeto.

---

## 🔍 Resultados Obtidos

### 🔸 Perceptron – Iris
- **Treinamento**: 82.86%  
- **Validação**: 59.09%  
- **Teste**: 82.61%  

### 🔸 Perceptron – Wine
- **Treinamento**: 100.00%  
- **Validação**: 96.30%  
- **Teste**: 88.89%  

### 🔸 Redes Neurais – Breast Cancer
| Arquitetura                 | Acurácia no Teste |
|----------------------------|-------------------|
| MLP (1 camada oculta)      | 96.51%            |
| MLP (2 camadas ocultas)    | 96.51%            |
| MLP + Dropout              | **97.67%**        |

---

## 📌 Conclusão

O projeto demonstrou que modelos simples como o Perceptron podem ser eficientes em problemas linearmente separáveis, mas redes neurais multicamadas (MLP) oferecem maior capacidade de generalização e desempenho em cenários mais complexos. A regularização com Dropout foi eficaz na redução do overfitting.

---

## ✍️ Autor

**Vinicius de Souza Santos**  
Estudante de Engenharia da Computação  
IFSP – Instituto Federal de São Paulo  
2024–2025

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
