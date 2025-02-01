# ejercicio_4

### main.py

```python
def fibonacci(n):
    secuencia = [0, 1]
    while len(secuencia) < n:
        secuencia.append(secuencia[-1] + secuencia[-2])
    return secuencia

if __name__ == "__main__":
    # Número de términos deseados
    n = int(input("Introduce el número de términos de la sucesión de Fibonacci: "))
    print("Sucesión de Fibonacci:", fibonacci(n))
```

### Rama 1: `funcion_fibonacci`

```python
def fibonacci(n):
    secuencia = [0, 1]
    while len(secuencia) < n:
        secuencia.append(secuencia[-1] + secuencia[-2])
    return secuencia
```

### Rama 2: `main_fibonacci`

```python
if __name__ == "__main__":
    def fibonacci(n):
        secuencia = [0, 1]
        while len(secuencia) < n:
            secuencia.append(secuencia[-1] + secuencia[-2])
        return secuencia

    # Número de términos deseados
    n = int(input("Introduce el número de términos de la sucesión de Fibonacci: "))
    print("Sucesión de Fibonacci:", fibonacci(n))
```

### Rama 3: `calculo_fibonacci`

```python
def fibonacci(n):
    secuencia = [0, 1]
    while len(secuencia) < n:
        secuencia.append(secuencia[-1] + secuencia[-2])
    return secuencia

if __name__ == "__main__":
    # Número de términos deseados
    n = int(input("Introduce el número de términos de la sucesión de Fibonacci: "))
    print("Sucesión de Fibonacci:", fibonacci(n))
```
