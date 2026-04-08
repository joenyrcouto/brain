---
tipo: caixa-de-entrada  
tags: [caixa-de-entrada]  
criado_em: 2026-03-02 00:40  
---

Revisão de equações de Maxwell na forma vetorial e escalar.
- Reconhecimento da equação de onda, reconhecida como aquela da luz.
- O curso focará na equação de onda em coordenadas cartesiana.

Fluxo do calor: modelando uma esfera quanto um espaço retangular, considerando densidade de energia de ambos.
- A partir da derivação da formula de calor da integral desse sistema, podemos interpor o conceito de gradiente (Relaciona à Cálculo 3, por Gauss). Lei de Fick.
	- Seria vantagem misturar o café frio ao leite para abaixar a temperatura desse último.
		- Tendo como objetivo perder a menor temperatura possível.
		- Considerando que houve variação infinitesimal.

Menção: difusão da bateria, neste contexto, é interessante de se comentar no portifólio.
EDPs, nomes importantes:
- Lavoisier;
- Poisson;
- Maxwell;
- Fick.

Obs.: Temos  que considerar as condições de contorno.
- Dirichlet;
- Neumann;
- Cauchy.

A EDO de primeiro grau tem uma solução geométrica com o vetor $\vec{S}$, por meio comparativo.
- $a \frac{\partial\phi}{\partial x}+b \frac{\partial\phi}{\partial y} = 0 \rightarrow \vec{S} \cdot \vec{v}\phi = 0$
- Usa regra da cadeia para derivar $\frac{\partial\phi}{\partial x}$ e $\frac{\partial\phi}{\partial y}$ para conseguir ambos em relação a outra variável.
	- Exemplo: $\frac{\partial\phi}{\partial x} = \frac{\partial\phi}{\partial s}\cdot \frac{\partial s}{\partial x} + \frac{\partial\phi}{\partial t}\cdot \frac{\partial t}{\partial x} = a \frac{\partial\phi}{\partial s}-b \frac{\partial\phi}{\partial t}$
	- Depois, montando um sistema de equação com essas parciais, obteremos a solução que não depende da magnitude de S, em outras palavras, qualquer solução no espaço da direção de $\vec{S}$ é admitida.

Bibliografia do curso:

- [[Mathematical Methods for Physicists]];
- [[Mathematical Methods for Physics and Engineering]];
- [[Fourier analysis and its applications]].