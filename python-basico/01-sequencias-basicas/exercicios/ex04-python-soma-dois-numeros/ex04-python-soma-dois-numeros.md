## 📝 Exercício 4

### 📌 Enunciado

> Faça um programa que leia dois números inteiros e mostre a soma entre eles.

### 💻 Código

```python
num1 = int(input('Digite um número: '))
num2 = int(input('Digite um número: '))

soma = num1 + num2

print(f'A soma entre {num1} e {num2} é igual a {soma}.')
```

### 📖 Explicação

Este programa solicita ao usuário dois números inteiros, calcula a soma entre eles e exibe o resultado na tela.

### 🔎 Fluxo do programa

* `input('Digite um número: ')` → solicita que o usuário digite um número
* `int(...)` → converte o valor digitado para um número inteiro
* `num1` → armazena o primeiro número informado
* `num2` → armazena o segundo número informado
* `soma = num1 + num2` → calcula a soma dos dois números
* `print(...)` → exibe o resultado da soma na tela
