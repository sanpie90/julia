## Julia install

### 1. Download Julia

From [julia website](https://julialang.org/downloads/), download tar.gz for linux

### 2. Decompress Julia

```
tar -xzvf julia-1.1.1-linux-x86_64.tar.gz
```

### 3. Create symlink

```
sudo ln -s <where-you-decompressed-your-julia-directory>/bin/julia /usr/local/bin/julia
```

### 4. Add julia to jupyter with iJulia

Run from terminal : `julia`

And then, from julia terminal, run :
```
julia>using Pkg
julia>Pkg.add("IJulia") 
```

## Jupyter Extensions

### From pip

```
pip install jupyter_contrib_nbextensions
```

```
jupyter contrib nbextension install --user
```

And now start your notebook, go into _Nbextensions_ tab and activate :
- Exercice 2
-  Table of Contents (2)

![jupyter screenshot](https://cdn-images-1.medium.com/max/2400/1*hRhdOuS-4NxEyd4Yqlzwxg.png)

## ENJOY !

