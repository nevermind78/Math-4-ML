---
title: 'Chapter 1'
description: 'Chapter description goes here.'
free_preview: true
---

## Introduction

```yaml
type: VideoExercise
key: 85c6832af0
xp: 50
```

`@projector_key`
805f9d203e6629132e5b1465b568c395

---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

This is an example exercise for computing a char polynomial

`@instructions`
1. import all from sympy 
2. define M=$\begin{bmatrix} 1 & 2 & 3 \\\ 3 & 1 & 2 \\\ 1 & 1 & 2 \end{bmatrix}$
3. compute the char polynomial of M

`@hint`


`@pre_exercise_code`
```{python}
from sympy import *
lamda = symbols('lamda')
M=Matrix([[1,2,1],[2,1,-1],[1,1,2]])
p=M.charpoly(lamda)

```

`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}

```
