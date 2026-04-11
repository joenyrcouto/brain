---
tipo: caixa-de-entrada
tags:
  - caixa-de-entrada
  - ifsc/curso/matemática/biologia/modelagem
criado_em: 2026-03-02 00:40
---

Regressão da reta linear

Valor $R^2$ para avaliar o quão bom é o ajuste.

Pseudo-inversa de Moore-Penrose: resolver mesmo quando as matrizes não são quadradas.
- A qualidade do problema inicial muda pela multiplicação da transposta. Ele muda a projeção do objeto do espaço.
  
Funciona a regressão, com método da pseuda que generaliza, para graus maiores.

Uns dos algoritmos para fazer a regressão em não lineares é tentar diminuir a derivada ${dS}/{st}$, com o vetor gradiente dele com um vetor variação de S na direção do vetor gradiente por um vetor -y/
- Ele é limitado à direção do gradiente, logo, depende fortemente as das condições iniciais.