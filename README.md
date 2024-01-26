# matplotlib_simpleplot
import matplotlib.pyplot as plt
import numpy as np
x = np.arange(1,6)
y = x**2
plt.plot(x,y)
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title("Simple Plot")
plt.show()
