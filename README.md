# Projeto de Aula: Listas em Python

## 🚀 Sobre o Projeto

Este repositório documenta a aula sobre **Listas em Python** que foi a base para minha aprovação no processo seletivo de trainees do **Introcomp**.

## 🌟 O Que é o Introcomp?

O **Introcomp (Introdução à Computação)** é um projeto de extensão que, desde 2011, oferece um curso de programação totalmente gratuito para alunos de escolas públicas do Espírito Santo. A missão do projeto vai além de ensinar código; trata-se de inspirar jovens e abrir portas para o futuro através da tecnologia.

## 🎯 Análise da Aula:

O notebook `aula_lista_introcomp.ipynb` é um exemplo da abordagem do Introcomp e foi um pilar na minha preparação.

### 1. **A "Dinâmica da Caixa": Aprendizado na Prática**
Em vez de apenas apresentar a teoria, o material começa com um projeto prático e divertido: um jogo de roleta.

**Aspectos técnicos e didáticos notáveis:**
* **Listas Paralelas:** No código há múltiplas listas (`nomes_jogadores`, `numeros_apostados`, `saldos_iniciais`, etc.) que se correlacionam pelos índices. Esta é uma excelente forma de ensinar como estruturar dados relacionados antes de introduzir conceitos mais complexos como dicionários ou objetos.
* **Manipulação Dinâmica:** O uso do método `.append()` para adicionar informações de novos jogadores em tempo real demonstra a natureza dinâmica das listas.
* **Lógica e Controle de Fluxo:** A verificação de vencedores com `if len(indices_vencedores) > 0:` e o uso de laços `for` para percorrer as listas e calcular os resultados reforçam conceitos fundamentais de programação.

### 2. **Cobertura dos Fundamentos de Listas**
* **Criação e Acesso:** `minha_lista = [item1, item2]` e `minha_lista[0]`.
* **Adição e Remoção:** `.append()`, `.insert()`, `.pop()` e `.remove()`.
* **Funções Utilitárias:** `len()`, `max()`, `min()` e o operador `in`.

### 3. **Foco em Boas Práticas e Erros Comuns**
Uma seção inteira é dedicada a preparar o aluno para problemas reais, como os erros `IndexError` (índice fora do alcance) e `ValueError` (tentar remover um item que não existe). O exercício de fixação do "Joãozinho" é um exemplo prático que ensina a importância de verificar a existência de um item antes de tentar removê-lo, uma habilidade crucial para qualquer desenvolvedor.