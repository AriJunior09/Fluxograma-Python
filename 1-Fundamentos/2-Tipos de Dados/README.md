
#  Tipos de Dados Primitivos em Python

| Tipo  | Exemplo       | Descrição                            |
|-------|---------------|----------------------------------------|
| `int` | `10`          | Número inteiro                         |
| `float` | `3.14`      | Número com ponto flutuante (decimal)   |
| `str` | `"Olá"`       | Texto (cadeia de caracteres)           |
| `bool` | `True` ou `False` | Valor lógico (booleano)          |

🧪 Exemplos de uso em código:
```python
# int
idade = 25
print("Idade:", idade)

# float
altura = 1.75
print("Altura:", altura)

# str
nome = "Maria"
print("Nome:", nome)

# bool
tem_carteira = True
print("Tem carteira?", tem_carteira)
```




# 🔁 Conversões de tipos (Type Casting)
```python
# str para int
numero = int("10")

# int para str
texto = str(123)

# float para int (arredonda para baixo)
inteiro = int(3.99)

# int para float
decimal = float(5)

# qualquer valor para bool
print(bool(""))        # False
print(bool("texto"))   # True
print(bool(0))         # False
print(bool(1))         # True