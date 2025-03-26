import numpy as np
import matplotlib.pyplot as plt
data = np.random.randn(1000)
plt.hist(data, bins=30, alpha=0.75)
plt.title('Distribution des données')
plt.show()
