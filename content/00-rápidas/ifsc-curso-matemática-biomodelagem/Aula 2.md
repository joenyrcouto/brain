---
tipo: caixa-de-entrada
tags:
  - caixa-de-entrada
  - ifsc/curso/matemática/biologia/modelagem
criado_em: 2026-03-02 00:40
---

T. R. Malthus define o crescimento populacional de uma maneira Darwiniana, com uma visão materialista e competitiva da matéria, e apela a dizer que as pessoas deveriam fazer o "sacrifício" de ter menos filhos para evitar um fim catastrófico.

Uma população pode ter um estado homeostático a partir de um período, e estar alheio à perturbação do mesmo.

Euler define, de acordo com a bíblia, um início com 6 pessoas para estudar um crescimento exponencial da população. Malthus fez algo semelhante, depois em torno de 100 anos.

Modelo Malthusiano, linear simples, para resolver o tamanho da população: 
- $P_{t+1}=P_{t}+(f-d)P_{t} = (1+f-d)P_{t}= \lambda P_{t}$ ou $P_{t}=\lambda^tP_{0}$
	- $\Delta P = P_{t+1}-P_{t} \rightarrow \Delta P = fP_{t}-dP_{t}$
	- d = 1 para tirar sobreposição de gerações.
	- A mudança de unidade do tempo é feita pela modulando o expoente t, ex.: t: anos $\rightarrow$ t/12:meses.
	- Neste modelo temos taxa per capita $\frac{\Delta P}{P_{t}} = (f-d) \equiv r$ (constante), um problema dela é possibilitar o crescimento infinito da fórmula.

Para aprimora o modelo anterior, podemos pensar em $r_{t} = r_{\text{malthusiano}}\left( 1-\frac{P_{t}}{K} \right)$.
- Logo obtemos, $\frac{\Delta P}{P_{t}} = r_{\text{intríseca}}\left( 1-\frac{P_{t}}{K} \right)$
	- Para população pequenas, temos um resultado semelhante ao malthusiano, com crescimento exponencial.
	- Chamamos de "r" intrínseco por ser o valor que a população cresceria sem limitação.

Iremos focar na análise de limite assintótico, ou ponto fixo, que foca num tempo distante da população.
- Temos os ponto fixo $P = 0$ e $P=K$, para quando a população não varia mais.

Gráfico de Coweb servem para observar a dinâmica sobre curva (fazemos a polução sobre um tempo que usa como unidade a própria populacão).
- Podemos usar nossa curva de crescimento com uma diagonal, veremos variação como lados de quadrados simétricos entre a curva e a diagonal.
	- Possível ter convergência.

Como menção temos:
- Função do tempo contínuo;
- Função geradora transforma uma função discreta em função do tempo contínuo.

Bibliografia: 
- [[Principle of Population]]
- [[Introductio In Analysin Infinitorum]]