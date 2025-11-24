# 🔢 Projeto: Calculadora de Estatísticas de Notas Avançada (Linguagem C)

## 💡 Sobre o Projeto

Este projeto consiste na implementação de uma **Calculadora de Estatísticas de Notas** utilizando **Linguagem C**. Foi desenvolvido como um exercício para aplicar e consolidar conceitos de programação estruturada, funções modulares e manipulação de entrada de dados.

O programa permite o cadastro de múltiplas notas (até 100) e, em seguida, oferece um menu interativo para exibir as estatísticas solicitadas.

---

## ✨ Funcionalidades Chave

* **Cadastro Interativo:** Permite o cadastro sequencial de notas entre 0.0 e 10.0.
* **Tratamento de Vírgula:** O programa trata automaticamente a entrada, convertendo a vírgula (`,`) para ponto (`.`), garantindo a correta leitura de decimais em ambientes em português.
* **Análise Modular:** Utiliza funções separadas para calcular a média, a maior nota e a menor nota, promovendo a organização do código.
* **Menu de Estatísticas:** Exibe um menu (`[1] Média`, `[2] Maior Nota`, `[3] Menor Nota`, etc.) para que o usuário escolha quais resultados visualizar.

---

## 🛠️ Conceitos de C Aplicados

* **Estruturas de Dados:** Uso de `array` (`float notas[MAX_NOTAS]`) para armazenar as notas.
* **Funções Modulares:** Implementação de `calcularMedia()`, `maiorNota()`, e `menorNota()`.
* **I/O e Strings:** Utilização de `scanf()` junto com `strchr()` e `atof()` para manipulação robusta da entrada do usuário.
* **Controle de Fluxo:** Laços `do-while` para menus e laços `for` para iteração e cálculo.

---

## 🚀 Como Executar

Para rodar este programa no seu sistema, você precisará de um compilador C (como o GCC):

1.  **Compile o Código:**
    ```bash
    gcc main.c -o calculadora_notas
    ```
2.  **Execute o Programa:**
    ```bash
    ./calculadora_notas
    ```
3.  **Instruções:** Siga as instruções no console para cadastrar as notas e navegar pelo menu de estatísticas.
