---
title: "Utilização do Python: os gases efeito de estufa"
layout: post
categories: 
tags: 
---

Os gases com efeito de estufa são:

-   dióxido de carbono,
-   metano,
-   óxido nitroso,
-   ozono,
-   vapor de água, etc.

Estes gases  reduzem a libertação de calor provocando a subida
da temperatura e o aquecimento global do planeta.

Os principais gases que provocam o **efeito de estufa** são:

-   Dióxido de carbono 56%
-   Metano 18%
-   CFCs 13%
-   Ozono 7%
-   Óxido nitroso 6%

Cálculo utilizando *Python*

{% highlight python %}
emissao_dioxido_carbono = 0.56
emissao_metano = 0.18
soma = emissao_dioxido_carbono + emissao_metano
print('O total, em %, de gases libertados de dioxido de carbono e metano:', soma)
{% endhighlight %}

    ('O total, em %, de gases libertados de dioxido de carbono e metano:', 0.74)
