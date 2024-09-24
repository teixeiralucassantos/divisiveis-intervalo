# Contador de Números Divisíveis por 7 ou 13

Este projeto tem como objetivo contar quantos números entre 1 e 1.000.000 são divisíveis por 7 ou 13. O programa utiliza um loop para verificar cada número no intervalo e mantém um contador para aqueles que atendem à condição.

## Como Funciona

O programa percorre todos os números de 1 a 1.000.000 e verifica se cada número é divisível por 7 ou 13. Se for, o contador é incrementado. Ao final da execução, o programa imprime o total de números que são divisíveis por pelo menos um dos dois números.

### Código

```python
divisiveis_por_7_ou_13 = 0

for i in range(1, 1000001):
    if i % 7 == 0 or i % 13 == 0:
        divisiveis_por_7_ou_13 += 1

print(f"Existem {divisiveis_por_7_ou_13} números divisíveis por 7 ou 13 no intervalo de 1 a 1000000.")
