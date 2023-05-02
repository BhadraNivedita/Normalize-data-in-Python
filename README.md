# Normalize-data-in-Python

```from sklearn import preprocessing
import numpy as np 
```
Preprocessing function would do the taks.

```
arr = np.random.randint(100,size=(15))
print('Original Array = ', arr)

arr_norm = preprocessing.normalize([arr])
print('Normalized Array = ', arr_norm )
```

```
Original Array =  [78 67 88 54 12 81 42 88 66 37 80 48 99 11 27]
Normalized Array =  [[0.31193512 0.26794427 0.35192681 0.21595509 0.04799002 0.32393263
  0.16796507 0.35192681 0.26394511 0.14796923 0.31993346 0.19196008
  0.39591766 0.04399085 0.10797754]]
```

