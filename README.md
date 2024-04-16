# Somat-rio-

# Somatório dos Números Pares de 1 a 500

Este programa em C calcula o somatório dos números pares no intervalo de 1 a 500 e exibe o resultado.

## Como usar o programa

1. Compile o código-fonte usando um compilador C, como o gcc:

```
gcc -o somatorio_pares somatorio_pares.c
```

2. Execute o programa compilado:

```
./somatorio_pares
```

3. O programa exibirá o somatório dos números pares no intervalo de 1 a 500.

## Exemplo de Uso

```
O somatório de 1 até 500 é: 125250
```

## Como funciona

1. O programa utiliza um laço de repetição for para iterar de 1 a 500.
2. Para cada número no intervalo, verifica se é par utilizando o operador de módulo (%).
3. Se o número for par, é adicionado ao somatório 's'.
4. Após iterar por todos os números no intervalo, o programa exibe o somatório calculado.

## Observações

- O programa utiliza a função `setlocale` para configurar a localidade para "Portuguese", permitindo a exibição correta de caracteres especiais em português.
- O programa presume que números pares são aqueles divisíveis por 2 sem deixar resto.
