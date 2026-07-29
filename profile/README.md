## Hi there! Welcome to Cs-Brazil 👋 🇧🇷

<div align="center">
  <img src="https://external-preview.redd.it/poland-cannot-into-html-space-v0-iF2Mish73a40hSYnCNopFmVwnBeydSfJLMvjmPHadd4.png?auto=webp&s=9d2411ce776afa16f707bbec833aa10f60b98c1a" width="250" height="320" alt="Cs-Brazil HTML tag meme" />
  <br/>
</div>

---

### 🌎 Our Mission

Our goal is simple: make Computer Science accessible to Brazilian devs by breaking the language barrier and creating focused learning paths. No literal translations here. We create original, easy-to-digest content based on classic CS books to avoid copyright issues and focus on what actually matters: learning.

**We operate on two main pillars:**

* **1. Chapter-by-Chapter Breakdowns:** We take high-level CS books that lack PT-BR editions and explain their core concepts. We synthesize the material using our own words, analogies, and a practical approach.
* **2. Goal-Oriented Learning Paths:** We use reference books (in any language) to build focused learning journeys. Example: *Using a comprehensive Linux book exclusively to extract and teach the necessary foundation for DevOps.*

---

### 🇧🇷 Nossa Missão

Nosso objetivo é tornar a Ciência da Computação mais acessível para a comunidade brasileira, quebrando a barreira do idioma e criando trilhas de aprendizado diretas. Nós não fazemos tradução literal. Criamos conteúdo original e didático baseado em grandes obras para evitar problemas com direitos autorais e focar no que realmente importa: o aprendizado.

**Como trabalhamos:**

* **1. Descomplicando livros (com nossas palavras):** Pegamos livros avançados que não têm versão em PT-BR e explicamos a essência de cada capítulo. Zero tradução literal! Nós lemos, entendemos e repassamos o conhecimento com o nosso vocabulário, usando analogias e uma linguagem clara.
* **2. Trilhas focadas na prática:** Usamos livros (em qualquer idioma) como base para ensinar um caminho específico. Exemplo: *extrair de um livro abrangente sobre Linux apenas o necessário para aprender DevOps.*

---

### 🗂️ Estrutura dos Repositórios

Cada repositório no **Cs-Brazil** representa um livro ou uma trilha. Para manter a organização e facilitar a navegação, o formato padrão é este:

```text
📚 Nome-do-Livro-ou-Trilha/
├── 📝 README.md (Apresentação do livro/trilha, sumário e objetivo)
│
├── 📂 Capitulo-01-Nome-do-Capitulo/
│   ├── 📄 README.md (Sua explicação autoral e didática do capítulo)
│   ├── 📂 assets/ (Diagramas e imagens EXCLUSIVAS deste capítulo)
│   └── 📂 exercicios/
│       ├── 📄 questao-01.md (Sua resolução autoral)
│       └── 📄 questao-02.md
│
├── 📂 Capitulo-02-Nome-do-Capitulo/
│   ├── 📄 README.md (Sua explicação autoral e didática do capítulo)
│   ├── 📂 assets/
│   └── 📂 exercicios/
│       └── 📄 questao-01.md
│
└── 📂 assets/ (Opcional: Apenas para a capa da trilha/livro no README principal)
```

---

### 🌈 Como Contribuir

O projeto é movido pela comunidade e Pull Requests (PRs) são muito bem-vindos. Quer ajudar a democratizar o conhecimento?

* **Escolha seu projeto:** Pegue um clássico da computação para explicar ou crie uma trilha focada em uma tecnologia específica.
* **A regra de ouro:** Traduza o *conceito*, não a palavra. Pense que você está explicando o assunto para um colega de trabalho. Use sua didática e faça analogias!
* **Avise antes (Issue):** Antes de iniciar um livro inteiro, abra uma Issue com a sua ideia. Assim, sabemos o que está em andamento e evitamos trabalho duplicado.
* **Mande o PR:**
  * Faça o fork do repositório (ou avise a administração para criar um novo para você).
  * Crie sua branch (`git checkout -b cap-03-algoritmos`).
  * Abra o PR explicando o que foi feito. A comunidade vai revisar, aprender junto e aprovar o conteúdo para a branch principal.

---

### 🚨 Regras do Projeto (Direitos Autorais e Segurança)

Para que a iniciativa dure e não tenhamos problemas legais com direitos autorais (*copyright*), algumas regras são **inegociáveis**:

1. **🛑 Zero pirataria:** Não faça upload do PDF, EPUB ou MOBI do livro original. O repositório deve conter apenas o material que você mesmo produziu.
2. **✍️ Sem Ctrl+C / Ctrl+V:** Não copie trechos do livro. A ideia não é traduzir literalmente, mas sim explicar. Escreva com as suas palavras e crie seus próprios exemplos de código.
3. **🎨 Gráficos e Diagramas Próprios:** Não tire print dos esquemas originais do livro. Crie os seus próprios diagramas. Você pode usar Excalidraw, Mermaid.js, ASCII art ou outras ferramentas gratuitas.
4. **📝 Exercícios repaginados:** Caso queira incluir os exercícios do final do capítulo, altere o contexto e o enunciado. Não os copie de forma idêntica.
5. **🖼️ Capa do repositório:** Para evitar problemas com a marca da editora, não use a capa comercial do livro como banner do projeto. Utilize ícones, ilustrações livres ou faça sua própria arte.
6. **🧠 Revisão humana obrigatória:** O uso de IA (ChatGPT, Claude, etc.) é permitido para ajudar na estruturação, mas você deve ler, validar e revisar. PRs com textos robóticos, alucinações de IA ou explicações superficiais serão recusados.
7. **🔒 Cuidado com dados sensíveis:** Ao enviar exemplos práticos ou exercícios, verifique se não deixou passar chaves de API, tokens ou senhas reais por engano.

> ⚠️ **Atenção:** Qualquer PR que contiver PDF pirata, cópia literal de texto ou vazamento de credenciais será fechado imediatamente. Nosso objetivo é proteger a comunidade e manter o repositório no ar.

---

### 🤝 Precisamos de Revisores (Ninguém sabe tudo)

Nosso objetivo é cobrir diversas áreas da computação: Rust, Go, C++, Sistemas Distribuídos, Kernel, Compiladores... E a realidade é que ninguém domina todos esses assuntos sozinho.

Para garantir que a qualidade técnica continue alta e não deixar passar erros, **precisamos de desenvolvedores com experiência em tópicos específicos para revisar os PRs da comunidade**.

**Como funciona o papel do Revisor:**
* **Validação Técnica:** Verificar se a explicação está correta e se os exemplos de código realmente funcionam.
* **Apoio Didático:** Sugerir formas mais claras de explicar algo que possa ter ficado confuso.
* **Aprovação:** Dar o *Approve* para que o conteúdo possa ser integrado à branch principal.

👉 **Tem experiência em algum assunto e quer ajudar?** Abra uma *Issue* no repositório principal com o título `[REVISOR] Seu Nome - Sua Área` (exemplo: `[REVISOR] Ana - Rust / Sistemas Distribuídos`) informando em qual tópico você pode contribuir com revisões.
