# 1. Comentários
Comentários são ignorados pelo interpretador, usados para explicar o código.

```python
# Isso é um comentário de linha única, usamos o jogo da Velha

"""
Isso é um comentário
de várias linhas (docstring), usamos 3 aspas duplas.
"""
```

# 2. Variáveis e Tipos de Dados

```python
nome = "João"           # String
idade = 25              # Inteiro (int)
altura = 1.75           # Ponto flutuante (float)
tem_carteira = True     # Booleano (bool)

Você não precisa declarar o tipo — o Python faz isso automaticamente.
```

# 3. Função print() e input()
```python
print("Olá, mundo!")
nome = input("Qual seu nome? ")
print("Olá, " + nome)
```

# 4. Indentação (Muito importante no Python!)
Em vez de chaves {} como em Java/C/C++, o Python usa espaços (indentação).

```python
if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")
```

# 5. Operadores
Aritméticos: +, -, *, /, //, %, **

Comparação: ==, !=, <, >, <=, >=

Lógicos: and, or, not

```python
a = 10
b = 3
print(a + b)     # Soma
print(a // b)    # Divisão inteira
print(a > b and b > 0)
```

# 6. Condicionais (if / elif / else)
python
Copiar
Editar
nota = 7

if nota >= 7:
    print("Aprovado")
elif nota >= 5:
    print("Recuperação")
else:
    print("Reprovado")
📌 7. Laços de Repetição (while e for)
python
Copiar
Editar
# while
contador = 0
while contador < 5:
    print(contador)
    contador += 1

# for
for i in range(5):
    print(i)
📌 8. Funções (def)
python
Copiar
Editar
def saudacao(nome):
    print(f"Olá, {nome}!")

saudacao("Maria")
