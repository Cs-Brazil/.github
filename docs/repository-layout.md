# 📁 Repository Layout

# Estrutura Oficial dos Repositórios

Para manter todos os projetos da **Cs-Brazil** organizados e fáceis de navegar, utilizamos uma estrutura comum para cada tipo de repositório.

Seguir esse padrão facilita a colaboração, a revisão e a experiência de quem está estudando.

Cada repositório pertence a um dos três pilares da comunidade:

* 📚 Livros
* 🛤️ Trilhas de Aprendizado
* 🛠️ Projetos Reais

---

# 📚 Livros

Cada repositório representa um livro.

O objetivo é explicar seus conceitos utilizando conteúdo original produzido pela comunidade.

Estrutura recomendada:

```text
📚 Nome-do-Livro/
│
├── README.md
├── assets/
│
├── Capitulo-01-Nome/
│   ├── README.md
│   ├── Diario-de-Estudo.md
│   ├── assets/
│   └── exercicios/
│       ├── questao-01.md
│       └── questao-02.md
│
├── Capitulo-02-Nome/
│   ├── README.md
│   ├── Diario-de-Estudo.md
│   ├── assets/
│   └── exercicios/
│
└── ...
```

## O README principal

O `README.md` da raiz deve apresentar:

* objetivo do livro;
* público-alvo;
* referência utilizada;
* sumário dos capítulos;
* progresso do projeto.

---

## README de cada capítulo

Cada capítulo deve explicar o conteúdo utilizando suas próprias palavras.

Sempre que possível inclua:

* analogias;
* exemplos próprios;
* diagramas;
* referências complementares;
* exercícios.

---

## Diario-de-Estudo.md

O diário registra o processo de aprendizado do autor.

Exemplos de tópicos:

* Onde travei
* O que pesquisei
* O que aprendi
* Analogias que funcionaram
* Erros cometidos

---

## Exercícios

Os exercícios ajudam a consolidar o conteúdo.

Sempre que possível explique:

* resposta;
* raciocínio;
* dificuldades;
* alternativas consideradas.

---

# 🛤️ Trilhas de Aprendizado

Uma trilha organiza conhecimentos de diferentes fontes para atingir um objetivo específico.

Exemplo:

* Linux para DevOps
* Git para Iniciantes
* Redes para Back-end

A estrutura é praticamente a mesma utilizada para livros.

```text
🛤️ Nome-da-Trilha/
│
├── README.md
├── assets/
│
├── Modulo-01/
│   ├── README.md
│   ├── Diario-de-Estudo.md
│   ├── assets/
│   └── exercicios/
│
├── Modulo-02/
│   ├── README.md
│   ├── Diario-de-Estudo.md
│   └── exercicios/
│
└── ...
```

A principal diferença é que uma trilha pode utilizar diversas referências ao mesmo tempo.

---

# 🛠️ Projetos Reais

Projetos têm uma organização diferente.

Em vez de capítulos, dividimos o conteúdo em partes do software que façam sentido serem estudadas separadamente.

Estrutura recomendada:

```text
🛠️ Nome-do-Projeto/
│
├── README.md
├── Diario-de-Estudo.md
├── Decisoes.md
├── assets/
│
├── Trecho-01/
│   ├── README.md
│   ├── assets/
│   └── exercicios/
│
├── Trecho-02/
│   ├── README.md
│   ├── assets/
│   └── exercicios/
│
└── exercicios/
```

---

## README principal

O README deve apresentar:

* o que é o projeto;
* objetivo;
* tecnologias utilizadas;
* conhecimentos prévios;
* link para o repositório original (quando aplicável);
* licença do projeto original.

---

## Decisoes.md

Este arquivo registra decisões importantes encontradas durante o estudo.

Exemplos:

* por que determinada arquitetura foi utilizada;
* vantagens e desvantagens;
* possíveis alternativas;
* impactos dessas escolhas.

---

## Dividindo um projeto

Um "trecho" não precisa seguir a ordem do código.

Você pode organizar por assuntos.

Exemplo:

```text
Trecho-01 - Arquitetura

Trecho-02 - Sistema de Rotas

Trecho-03 - Banco de Dados

Trecho-04 - Autenticação

Trecho-05 - Cache
```

O objetivo é facilitar o aprendizado.

---

# 📂 Pasta assets

A pasta `assets/` deve conter apenas arquivos utilizados naquele nível da documentação.

Exemplo:

```text
Livro/
│
├── assets/
│     banner.png
│
├── Capitulo-01/
│
│   ├── assets/
│   │      memoria-virtual.png
│   │      cpu.svg
```

Isso evita que imagens de um capítulo sejam reutilizadas em outro sem necessidade.

---

# 📝 Nome dos arquivos

Utilize nomes simples e consistentes.

Exemplos:

```text
README.md

Diario-de-Estudo.md

Decisoes.md

questao-01.md

questao-02.md
```

Evite:

```text
Novo Documento (12).md

capitulo final.md

arquivo novo.md
```

---

# 📖 Ordem sugerida para um capítulo

Uma estrutura recomendada é:

1. Introdução
2. Problema
3. Conceito
4. Exemplos
5. Analogias
6. Erros comuns
7. Exercícios
8. Referências

Essa sequência ajuda o leitor a construir entendimento de forma gradual.

---

# 🎯 Objetivo da estrutura

Esta organização não é obrigatória em todos os casos.

Ela existe para manter uma experiência consistente entre os repositórios da comunidade.

Quando todos seguem um padrão semelhante:

* o conteúdo fica mais fácil de navegar;
* novos colaboradores aprendem mais rápido;
* revisões ficam mais simples;
* estudantes sabem exatamente onde encontrar cada informação.

Consistência também faz parte da qualidade do material.