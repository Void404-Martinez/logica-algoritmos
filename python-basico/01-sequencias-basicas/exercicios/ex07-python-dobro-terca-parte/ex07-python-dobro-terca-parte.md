## 📝 Exercício 7

### 📌 Enunciado

> Crie um programa que leia um número real e mostre na tela o seu dobro e a sua terça parte.

### 💻 Código

```python id="jv8q9n"
num = float(input('Digite um número: '))

dobro = num * 2
tercaParte = num / 3

print(f'O dobro de {num} é {dobro}')
print(f'A terça parte de {num} é {tercaParte}')
```

### 📖 Explicação

Este programa utiliza comandos de entrada e saída para solicitar um número real ao usuário, calcular o seu dobro e a sua terça parte e exibir os resultados na tela.

### 🔎 Fluxo do programa

* `input('Digite um número: ')` → solicita que o usuário digite um número
* `float(...)` → converte o valor digitado para um número decimal
* `dobro = num * 2` → calcula o dobro do número digitado
* `tercaParte = num / 3` → calcula a terça parte do número digitado
* `print(...)` → exibe o dobro do número
* `print(...)` → exibe a terça parte do número


