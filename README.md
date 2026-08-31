# Documentação da Calculadora Básica em Python

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)

  Esta documentação detalha o funcionamento, as estruturas de controle e as instruções de uso para o script *`calculadora.py`*

## 1. Visão Geral
  O script consiste em uma aplicação de terminal interativa desenvolvida em Python que realiza quatro operações aritméticas básicas entre dois números reais fornecidos pelo usuário:
  - Soma
  - Subtração
  - Multiplicação
  - Divisão

## 2. Requisitos do Sistema
  - Linguagem: Python 3.x
  - Dependências: Nenhuma biblioteca externa é necessário (utiliza apenas funções nativas).

## 3. Estrutura e Sequência de Execução
  O script é estruturado em uma única função principal chamada `calculadora()`, acionada pelo bloco de inicialização padrão do Python(if__nome__ == "__main__":).

### Fluxo de Exercução
  1. Exibição do Menu: O programa imprime as opções disponíveis para o usuário.
  2. Entrada Opção: Lê a escolha do usuário como texto via `input()`.
  3. Validação da Opção:
     - Se a opção for válida (`1`, `2`, `3` ou `4`), prossegue para a leitura dos números.
     - Se a opção for inválida, exibe uma mensagem de erro e encerra a função.
  4. Entrada dos Dados Numéricos: Solicita dois números e converte as entradas de texto em valores de ponto flutuante `(float)`.
  5. Processamento da Operação:
     - Opção 1 (Soma): Executa `num1 + num2`
     - Opção 2 (Subtração): Executa `num1 - num2`
     - Opção 3 (Multiplicação): Executa `num1 * num2`
     - Opção 4 (Divisão): Valida se `num2 != 0`. Se for diferente de zero, calcula `num1 / num2`; caso contrário, trata a exceção e exibe uma mensagem informando que a divisão por zero não é permitida.
  6. Exibição do Resultado: Imprime a expressão e o resultado formatado no terminal.

## 4. Detalhamento de Funções e Métodos
  `calculadora()`
  - Descrição: Função responsável por toda a interface de terminal, leitura de dados, validação e exibição de resultados.
  - Parâmetros: Nenhum
  - Retorno: `None` (Apenas imprime dados no console).

## 5. Exemplo de Uso













