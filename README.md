# Introdução ao Python: Variáveis e Tipos de Dados

Este repositório contém um script introdutório em Python focado na exibição de mensagens no terminal e na declaração de variáveis com diferentes tipos de dados primitivos.

## Conceitos Abordados

- **Saída de Dados (`print`):** Utilizado para exibir mensagens e valores formatados diretamente no console.
- **Tipos de Dados Primitivos:**
  - **`str` (String):** Armazena sequências de caracteres (texto).
  - **`int` (Inteiro):** Armazena números inteiros.
  - **`bool` (Booleano):** Armazena valores lógicos (`True` ou `False`).
  - **`float` (Ponto Flutuante):** Armazena números decimais.
- **Interpolação de Strings (`f-string`):** Permite inserir variáveis diretamente dentro de strings de forma limpa e legível utilizando chaves `{}`.

## Código do Projeto

```python
# Exibe uma mensagem simples na tela
print("Olá Mundo!!!")

# Declaração de variáveis armazenando diferentes tipos de dados
nome = "Kaio"        # Tipo string (texto)
idade = 24           # Tipo int (número inteiro)
temCNH = True        # Tipo bool (booleano: verdadeiro ou falso)
altura = 1.76        # Tipo float (número decimal)

# Exibe os dados formatados usando f-string (permite inserir variáveis diretamente dentro das chaves {})
print(f"Meu nome é {nome}, tenho {idade} anos, minha altura é {altura} metros")