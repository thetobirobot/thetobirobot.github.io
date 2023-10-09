# Welcome to Tobi The Robot's Page

## This is how we can deploy Jupyter pages in Github Pages

## You can also save images and show


```python
import numpy as np
import matplotlib.pyplot as plt
import scipy.stats as stats
mu = 0
std = 1
x = np.linspace(start=-4, stop=4, num=100)
y = stats.norm.pdf(x, mu, std) 
plt.plot(x, y)
plt.show()
```


    
![png](/images/sample-notebook_3_0.png)
    

