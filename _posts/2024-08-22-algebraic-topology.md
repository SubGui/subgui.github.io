---
title:  "Topologia Algébrica"
mathjax: true
layout: post
categories: media
---

<img src="https://github.com/SubGui/subgui.github.io/blob/master/images/poincare.png?raw=true" width="250" height="250">

Henri Poincaré (1854-1912), matemático francês. Notavelmente um dos mais prolíficos matemáticos de todos os tempos, foi o inventor da Topologia Algébrica.

## Alguns teoremas interessantes

[Sequência de Mayer-Vietoris](https://en.wikipedia.org/wiki/Mayer-Vietoris_sequence) Seja $$X$$ um espaço topológico e subconjuntos $$A,\,B\subset X$$ cujos interiores cobrem $$X$$. Em homologia simplicial, a **sequência de Mayer-Vietoris** para a tripla $$(X,\,A,\,B)$$ é a sequência longa exata relacionando os grupos de homologia singular (com coeficiente no grupo dos inteiros $$\mathbb{Z}$$ dos espaços $$X,\,A,\,B$$, e a interseção $$A\cap B$$. Ela afirma que a seguinte sequência longa é exata:

$$\cdots \rightarrow H_{n+1}(X)\overset{\partial_{\ast}}{\rightarrow} H_n(A\cap B)\overset{(\imath_{\ast},\,\jmath_{\ast})}{\rightarrow}H_n(A)\osum H_n(B)\overset{k_{\ast}-l_{\ast}}{\rightarrow} H_n(X)\overset{\partial_{\ast}}{\rightarrow} H_{n-1}(A\cap B) \rightarrow\cdots H_0(A)\osum H_0(B)\overset{k_{\ast}-l_{\ast}}{\rightarrow} H_0(X)\rightarrow 0$$

onde $$\imath:A\cap B\hookrightarrow A,\,\jmath:A\cap B\hookrightarrow B,\,k:A\hookrightarrow X$$ e $$l:B\hookrightarrow X$$ são mapas inclusão e $$f_{\ast}$$ denota o homomorfismo induzido pelos mapas nos respectivos grupos de homologia.
