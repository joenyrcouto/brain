---
tipo: caixa-de-entrada
tags:
  - caixa-de-entrada
  - ifsc/curso/matemática/biologia/modelagem
criado_em: 2026-03-02 00:40
---

Taxa per capita geral: $\frac{\Delta P}{P}=r\left( 1-\frac{P}{K} \right)$

Definição do modelo malthusiano: taxa per capita constante.

Modelo de Ricker (1954), gráfico: Taxa per capita X População, com a taxa per capita no expoente.
- $P_{t+1}=P_{t}e^{r\left( 1-\frac{P_{t}}{K} \right)}$
- Importante, por exemplo, para modelar população de peixe em um lago, pelas pescas;
- Ou o menor crescimento de vacas dado o acúmulos delas (Competição do tipo "scramble").

Modelo de Beverton-Holt (1957): Fazemos que a população é igual ao produto da população anterior pela taxa de crescimento.
- $P_{t+1}=P_{t}r\left( 1-\frac{P_{t}}{K} \right)=\frac{rP_{t}}{\left( 1+\frac{P}{K} \right)}=\frac{1}{\frac{1}{P_{t}}+\frac{1}{K}}$
- O aumento da curva vai para um ponto fixo, mesmo com bastante aumento da população, pois alguns indivíduos ficam com todos recursos (Competição do tipo competitivo).
- Mesmo não sendo linear, tem solução fechada. Pois $x_{t}\equiv \frac{1}{P_{t}}$, com $\bar{r}=\frac{1}{r}$ e $\bar{K}= \frac{1}{K}$.

Temos as análises de estabilidade linear, analisando se pontos tende ao equilíbrio ou a instabilidade.