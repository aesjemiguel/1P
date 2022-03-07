---
title: "Idade média da mãe ao nascimento do primeiro filho"
layout: post
categories: 
tags: 
permalink:/idade-mae-1-filho/
---

O gráfico seguinte representa a evolução da idade média da mãe ao nascimento do primeiro filho, comparando os anos de 1990 e 2020.

<figure>
<img  src="/1P/assets/Figure_1.png"  width="600"/>
<figcaption>Idade média da mãe ao nascimento do primeiro filho.</figcaption>
</figure>

*Fonte: <https://pordata.pt>*

Como se pode observar pelo gráfico a da idade média das mães, ao nascimento do primeiro filho, aumentou de 1990 para 2020. Este fenómeno terá contribuído para população portuguesa ter menos jovens nos últimos anos.

Exemplo do código python para gerar o gráfico.

{% highlight python %}
import numpy as np
import matplotlib.pyplot as plt

x_labels = ['Norte','Centro','Lisboa','Alentejo','Algarve','Acores','Madeira']

x = np.arange(7)

y = [24.6, 24.4, 25.8, 23.8, 24.0, 23.4, 24.2]
z = [30.9, 30.8, 30.8, 29.7, 29.9, 29.4, 30.4]

plt.bar(x, y, width = 0.35, color ='c', label='1990')
plt.bar(x+0.35, z, width = 0.35, color='b', label='2020')

plt.xlabel('NUTS II')
plt.xticks(x, x_labels, rotation='vertical')
plt.ylabel('Idade')
plt.ylim([16,36])
plt.title('Idade média da mãe ao nascimento do primeiro filho\nComparação entre anos de 1990 e 2020')
plt.legend()
plt.subplots_adjust(bottom=0.2)
plt.show()
{% endhighlight %}
