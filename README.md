# Arrays Project

Este projeto demonstra como trabalhar com arrays em Python utilizando o módulo `array`. O foco principal é manipular e analisar dados numéricos de forma eficiente, com exemplos que frequentemente aparecem em entrevistas de emprego e processos seletivos.

## Funcionalidades

- **Soma dos Elementos**: Calcula a soma de todos os elementos em um array.
- **Maior e Menor Valor**: Identifica o maior e o menor valor em um array.
- **Média dos Valores**: Calcula a média dos valores armazenados em um array.

## Tecnologias Utilizadas

- **Linguagem**: Python 3.x
- **Biblioteca**: array

## Exemplo de Uso

Aqui está um exemplo de como o código pode ser utilizado:

```python
import array as arr

# Suponha que temos uma sequência de números
numeros = arr.array('i', [15, 3, 9, 12, 6, 18, 1, 10, 7, 2])

# 1. Soma de todos os elementos
soma = sum(numeros)

# 2. Encontrar o maior valor no array
maior_valor = max(numeros)

# 3. Encontrar o menor valor no array
menor_valor = min(numeros)

# 4. Média dos valores no array
media = soma / len(numeros)

# 5. Exibir os resultados
print(f"Array de Números: {numeros[:]}")
print(f"Soma dos elementos: {soma}")
print(f"Maior valor: {maior_valor}")
print(f"Menor valor: {menor_valor}")
print(f"Média dos valores: {media:.2f}")
