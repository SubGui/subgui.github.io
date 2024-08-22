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


$$\displaystyle \cdots \to H_{n+1}(X)\,\xrightarrow {\partial _{*}} \,H_{n}(A\cap B)\,\xrightarrow {\left({\begin{smallmatrix}i_{*}\\j_{*}\end{smallmatrix}}\right)} \,H_{n}(A)\oplus H_{n}(B)\,\xrightarrow {k_{*}-l_{*}} \,H_{n}(X)\,\xrightarrow {\partial _{*}} \,H_{n-1}(A\cap B)\to \cdots$$
