# Data Visualisation with Python (matplotlib) - City Tech Society workshop

![](https://raw.githubusercontent.com/eydandash/CityTechSoc-WebDev-101/master/Logo.png)

Welcome to the Data Visualisation with Python workshop 💻📈

### Overview

This workshop talks about how to create basic visualisations using python's matplotlib library.
In particular we will use the matplotlib.pyplot module.

### Why Python?

* It is a general purpose language
* Easy to learn
* Many data visualisation libraries (including matplotlib)

### Why Data Visualisation?
* First step of data analysis work
* Give intuitive understanding (find patterns that are hard to see)
* Explore data
* Communicate data

### Why matplotlib? 🤔
* It is one of the most popular
* Other libraries are based on matplotlib e.g. seaborn

### The Basics

**Syntax**

![](https://i.redd.it/7v0a4ldssdq11.png)

* No ";" at the end of each statement
* No "{}", just ":" and indentation
* No declaration of variables

Happy days 😎

```
x = 0
y = 3.14
s = "I am a string"
t = 'I am a string too'
```

**Modules**

```
import matplotlib
from matplotlib import pyplot as plt
import matplotlib.pyplot as plt
```

**Arithmetic**

```
x = 5
y = 2

a = x + y # 7
s = x - y # 3
m = x * y # 10
d1 = x / y # 2.5
d2 = x // y # 2
p = x ** y # 25
```
**Functions**

```
def squared(x):
  return x ** 2
  
 # or
  
 squared = lambda x: x **2
```

**Lists**

```
l = list(range(0, 11)) # [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
l[5] # 5
l[0:5] # [0, 1, 2, 3, 4]
l[:5] # [0, 1, 2, 3, 4]
l[-1] # 10

even = [num for num in l if num%2 == 0] # [0, 2, 4, 6, 8, 10]
```

**Loops**
```
l = list(range(0, 11))

for i in range(len(l)):
  print(l[i])
```

![](https://imgflip.com/s/meme/Picard-Wtf.jpg)

```
for i in range(0, 11):
  print(i)

words = 'Do you know the way'

word_count = 0
for word in words:
  word_count += 1 # 5
                  # no ++word_count or word_count++ (sorry guys)
```

## Now let's visualise some data!!! 👌🏼🍕
