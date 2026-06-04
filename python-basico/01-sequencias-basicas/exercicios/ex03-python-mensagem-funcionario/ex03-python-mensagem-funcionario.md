## 📝 Exercício 3

### 📌 Enunciado

> Faça um programa que leia o nome e o salário de um funcionário e mostre uma mensagem no final.

### 💻 Código

```python
nome = input('Digite seu nome: ')
salario = int(input('Digite seu salário: '))

print(f'O funcionário {nome} tem um salário de {salario} no mês de junho.')
```

### 📖 Explicação

Este programa solicita o nome e o salário de um funcionário, armazena essas informações em variáveis e exibe uma mensagem contendo os dados informados.

### 🔎 Fluxo do programa

* `input('Digite seu nome: ')` → solicita e lê o nome do funcionário
* `input('Digite seu salário: ')` → solicita e lê o salário informado
* `int(...)` → converte o valor digitado para um número inteiro
* `print(...)` → exibe uma mensagem com o nome e o salário do funcionário

### 📋 Exemplo de execução

```text
Digite seu nome: João
Digite seu salário: 2500

O funcionário João tem um salário de 2500 no mês de junho.
```
