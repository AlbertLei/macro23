---
format: 
 hugo-md:
   html-math-method: webtex
---

# Testing quarto

I have individual files that I want to render with Quarto,
as Pandoc has better support for TeX.

For example, this `index.qmd` is at
`content/hw/hw-quarto/index.qmd`.
I can generate the corresponding `index.md` file by running:

``` bash
quarto render content/hw/hw-quarto/index.qmd
```

## Math and code highhight

``` python
import numpy as np
np.array(1)
```

![\mu_0 \in \mathsf{supp} \\,\Delta \Omega](https://latex.codecogs.com/svg.latex?%5Cmu_0%20%5Cin%20%5Cmathsf%7Bsupp%7D%20%5C%2C%5CDelta%20%5COmega "\mu_0 \in \mathsf{supp} \,\Delta \Omega")
