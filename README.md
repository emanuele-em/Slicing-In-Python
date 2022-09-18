# Slicing In Python
Use slicing notation `s[start:stop:step]` to access every *step-th* element starting from index start (included) and ending in index stop (excluded). All three arguments are optional, so you can skip them to use the default values
```python
(start=0, stop=len(lst), step=1)
```
Examples:

```python
cars = ["Ford", "Volvo", "BMW", "Fiat", "Toyota", "Ferrari"]

cars[::2] #['Ford', 'BMW', 'Toyota']

cars[::3] #['Ford', 'Fiat']

cars[::4] #output: ['Ford', 'Toyota']

cars[2::2] # ['BMW', 'Toyota']

cars[2::3] # ['BMW', 'Ferrari']

cars[3::2] # ['Fiat', 'Ferrari']

cars[2::] # ['BMW', 'Fiat', 'Toyota', 'Ferrari']

cars[:3:] # ['Ford', 'Volvo', 'BMW']

cars[:4:2] # ['Ford', 'BMW']

cars[:4:3] # ['Ford', 'Fiat']

cars[2:4:] # ['BMW', 'Fiat']

cars[2:5:2] # ['BMW', 'Toyota']

cars[::] # ['Ford', 'Volvo', 'BMW', 'Fiat', 'Toyota', 'Ferrari']
```

Same result with `string`:

```python
ex_str = "Python string slicing"

ex_str[::2] # Pto tigsiig

ex_str[::3] # Ph rgli

ex_str[::4] # Potgig

ex_str[2::2 # to tigsiig

ex_str[2::3] # tntnscg

ex_str[3::2] # hnsrn lcn

ex_str[2::] # thon string slicing

ex_str[:3:] # Pyt

ex_str[:4:2] # Pt

ex_str[:4:3] # Ph

ex_str[2:4:] # th

ex_str[2:5:2] # to

ex_str[::] # Python string slicing
```
