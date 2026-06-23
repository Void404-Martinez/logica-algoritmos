## 📝 Exercício 6

### 📌 Enunciado

> Faça um programa que leia um número inteiro e mostre o seu antecessor e seu sucessor.

### 💻 Código

```python
num = int(input('Digite um número: '))

antecessor = num - 1
sucessor = num + 1

print(f'O antecessor de {num} é {antecessor}')
print(f'O sucessor de {num} é {sucessor}')
```

### 📖 Explicação

Este programa solicita ao usuário um número inteiro, calcula seu antecessor e seu sucessor e exibe os resultados na tela.

### 🔎 Fluxo do programa

* `input('Digite um número: ')` → solicita que o usuário digite um número
* `int(...)` → converte o valor digitado para um número inteiro
* `antecessor = num - 1` → calcula o antecessor do número digitado
* `sucessor = num + 1` → calcula o sucessor do número digitado
* `print(...)` → exibe o antecessor do número
* `print(...)` → exibe o sucessor do número

