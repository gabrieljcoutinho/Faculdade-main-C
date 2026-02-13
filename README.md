# Exercícios de Lógica em C - Menu Interativo

Este projeto consiste em um sistema de menu desenvolvido em linguagem C para resolver desafios clássicos de lógica de programação e manipulação de strings. O trabalho foi realizado como parte das atividades acadêmicas da matéria.

---

## Funcionalidades

O programa oferece um menu interativo onde o usuário pode escolher entre quatro operações distintas:

### 1. Sequência de Fibonacci
Calcula e exibe a sequência de Fibonacci até um número de termos definido pelo usuário (limite de 50).
* **Exemplo:** Se a entrada for 5, o retorno será `0 1 1 2 3`.

### 2. Cálculo de Fatoriais
Gera uma lista de fatoriais de 1 até o número fornecido pelo usuário (limite de 20). Utiliza `unsigned long long` para garantir precisão em números maiores.
* **Exemplo:** `5! = 120`.

### 3. Verificador de Palíndromos
Analisa uma palavra e identifica se ela é um palíndromo (se a leitura é idêntica de frente para trás e de trás para frente).
* **Exemplo:** `RADAR` é um palíndromo.

### 4. Verificação de Substring
Verifica se uma determinada sequência de caracteres (segunda string) está contida dentro de outra palavra principal (primeira string).
* **Exemplo:** "roupa" dentro de "guarda-roupa".

---

## Colaboradores

* **Gabriel Jorge Coutinho** (RM: 565441) - [GitHub](https://github.com/gabrieljcoutinho)
* **Guilherme Ferraz de Medeiros** (RM: 564743) - [GitHub](https://github.com/bufungo)
* **Roberto Marques Moreira** (RM: 564935) - [GitHub](https://github.com/rmoreirafiap)

---

## Como Executar

1.  Certifique-se de ter um compilador C (como GCC) instalado.
2.  Compile o arquivo principal:
    ```bash
    gcc main.c -o menu_exercicios
    ```
3.  Execute o programa:
    ```bash
    ./menu_exercicios
    ```

---

> **Nota de Experiência:** Esta atividade foi realizada via Microsoft Teams, proporcionando uma experiência de colaboração superior à de outras plataformas, permitindo um foco maior no desenvolvimento prático da lógica de programação.
