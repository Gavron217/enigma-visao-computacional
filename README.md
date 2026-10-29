# Resolvendo Enigma com Visão Computacional 🧠💻

Este projeto resolve um enigma visual viral utilizando **Python, OpenCV (Visão Computacional)** e **Lógica Matemática de Progressão**.

## 🧠 A Lógica (Metacognição e Engenharia de Variáveis)
O enigma apresenta três figuras com quadrados preenchidos e vazios:
*   Figura 1: 3 quadrados preenchidos = 18
*   Figura 2: 5 quadrados preenchidos = 20
*   Figura 3: 7 quadrados preenchidos = ?

**A Solução Proposta:**
Em vez de buscar regras complexas de multiplicação ou posição, a solução aplica uma **progressão aritmética baseada na variação (delta)**. 
A cada +2 quadrados preenchidos, o valor final aumenta em +2. 
Portanto, a regra é: `Valor = 18 + (Qtd_Preenchidos - 3)`.
Logo, a Figura 3 resulta em: 18 + (7 - 3) = **22**.

## ⚙️ Como o código funciona
1. O código gera imagens sintéticas simulando o enigma.
2. O OpenCV lê as imagens, aplica binarização e conta os contornos (quadrados preenchidos).
3. A função de lógica aplica a progressão e retorna o valor final.

## 🚀 Como executar
1. Clone este repositório.
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o script: `python solucao_enigma.py`

## 📸 Resultado
O terminal exibe a contagem exata e o resultado da lógica: **22**.
