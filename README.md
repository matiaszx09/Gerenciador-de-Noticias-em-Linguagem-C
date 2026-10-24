# Gerenciador de Noticias - Lista Encadeada (C)

Trabalho pratico desenvolvido em Linguagem C focado na implementacao de estruturas de dados dinamicas, especificamente Listas e Pilhas, aplicadas ao gerenciamento de noticias.

---

## Tecnologias e Ferramentas Utilizadas

* Linguagem C
* Make / Makefile (para automacao da compilacao)
* Estruturas de Dados Dinamicas (Ponteiros e Alocacao Dinamica)

---

## Estrutura do Projeto

O projeto esta modularizado da seguinte forma:

* `Noticia.h` / `Noticia.c`: Define a estrutura de dados (struct) e as operacoes basicas referentes a uma noticia.
* `ListaEncadeada.h` / `ListaEncadeada.c`: Implementacao da logica de manipulacao da lista encadeada simples.
* `ListaCabCau.h` / `ListaCabCau.c`: Implementacao de variacoes da lista com cabeca/cabecalho.
* `main.c`: Arquivo principal contendo os testes e o fluxo de execucao do programa.
* `makefile`: Arquivo de configuracao para compilacao automatizada via terminal.

---

## Pre-requisitos

Para compilar e executar este projeto, voce precisara ter em sua maquina:
* Um compilador de C compativel (como GCC).
* A ferramenta Make.

---

## Como Compilar e Rodar o Projeto

Clone ou abra a pasta do projeto no seu terminal e siga os comandos abaixo:

1. Compilar o projeto utilizando o Makefile:
   ```bash
   make
   ```

2. Executar o programa:
   ```bash
   ./main
   ```

3. Limpar os arquivos binarios (opcional):
   ```bash
   make clean
   ```

---

## Autor

Trabalho desenvolvido por **Cauan Matias de Oliveira**.
