# Normalize-data-in-Python

```from sklearn import preprocessing
import numpy as np 
```
preprocessing function would do the taks.

```
arr = np.random.randint(100,size=(15))
print('Original Array = ', arr)

arr_norm = preprocessing.normalize([arr])
print('Normalized Array = ', arr_norm )
```

