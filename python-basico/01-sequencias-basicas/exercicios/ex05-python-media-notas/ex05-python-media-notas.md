## 📝 Exercício 5

### 📌 Enunciado

> Faça um programa que leia as duas notas de um aluno e mostre a média entre elas.

### 💻 Código

```python
nota1 = float(input('Digite a primeira nota: '))
nota2 = float(input('Digite a segunda nota: '))

media = (nota1 + nota2) / 2

print(f'A média entre {nota1} e {nota2} é igual a {media}.')
```

### 📖 Explicação

Este programa solicita duas notas de um aluno, calcula a média aritmética entre elas e exibe o resultado na tela.

### 🔎 Fluxo do programa

* `input('Digite a primeira nota: ')` → solicita a primeira nota do aluno
* `float(...)` → converte o valor digitado para um número decimal
* `input('Digite a segunda nota: ')` → solicita a segunda nota do aluno
* `float(...)` → converte o valor digitado para um número decimal
* `media = (nota1 + nota2) / 2` → calcula a média das duas notas
* `print(...)` → exibe o resultado da média na tela
