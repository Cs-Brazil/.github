# ✍️ Writing Guide

# Como criar conteúdo didático na Cs-Brazil

A Cs-Brazil não é apenas um lugar para armazenar informações.

Nosso objetivo é transformar conhecimento técnico em material que ajude outra pessoa a realmente aprender.

Um bom conteúdo não responde apenas:

> "O que isso faz?"

Ele também responde:

> "Por que isso existe?"
>
> "Quando eu usaria isso?"
>
> "Como eu penso sobre esse problema?"

Este guia apresenta algumas práticas para criar materiais claros, didáticos e úteis.

---

# 🧠 1. Explique o conceito antes da ferramenta

Evite começar mostrando comandos, APIs ou código sem contexto.

Antes de apresentar uma solução, explique o problema.

Exemplo:

❌ Ruim:

```bash
grep "erro" arquivo.log
```

"Esse comando procura uma palavra dentro de um arquivo."

---

✅ Melhor:

"Imagine que você possui um arquivo de log com milhares de linhas e precisa encontrar rapidamente todas as mensagens relacionadas a erros. Ler tudo manualmente seria inviável. O `grep` existe para resolver exatamente esse problema."

Depois apresente o comando.

A pessoa primeiro entende a necessidade, depois aprende a ferramenta.

---

# 🎯 2. Ensine o raciocínio, não apenas a resposta

Um conteúdo forte mostra o caminho até a solução.

Explique:

* quais problemas existiam;
* quais alternativas foram consideradas;
* por que uma decisão foi tomada;
* quais consequências existem.

Em Engenharia de Software, muitas vezes a decisão é mais importante que o código final.

---

# 🧩 3. Use analogias com cuidado

Analogias ajudam a criar conexões.

Uma boa analogia:

* simplifica um conceito;
* mantém a ideia principal;
* ajuda a visualizar algo abstrato.

Mas uma analogia não deve substituir a explicação técnica.

Exemplo:

"Um processo é como um programa em execução."

Essa comparação ajuda.

Mas depois explique:

* memória;
* recursos;
* isolamento;
* estados.

A analogia abre a porta. A explicação técnica entra na sala.

---

# 📖 4. Conte a história do aprendizado

A Cs-Brazil valoriza o processo de aprender.

Não esconda dificuldades.

Inclua no `Diario-de-Estudo.md`:

* onde você travou;
* quais conceitos pareciam confusos;
* quais pesquisas fez;
* quais erros cometeu;
* qual explicação finalmente ajudou.

Uma dúvida real de uma pessoa pode ser exatamente a dúvida de milhares de outras.

---

# 📝 5. Crie exercícios progressivos

Exercícios devem acompanhar a evolução do aluno.

Evite começar com desafios muito difíceis.

Uma progressão comum:

## 🟢 Nível básico

Testar o conceito principal.

Exemplo:

"Liste os arquivos de um diretório."

---

## 🟡 Nível intermediário

Combinar conceitos.

Exemplo:

"Liste apenas arquivos `.log` modificados recentemente."

---

## 🔴 Nível avançado

Resolver problemas próximos da realidade.

Exemplo:

"Crie um script que monitore novos arquivos de log e gere um relatório."

---

# 🔗 6. Conecte capítulos e conceitos

Conhecimento funciona como uma rede.

No final de cada capítulo, indique:

## Você aprendeu:

* conceito A;
* conceito B;
* conceito C.

## Próximo passo:

* conceito D;
* conceito E.

Isso ajuda o estudante a entender onde está na jornada.

---

# ⚠️ 7. Mostre erros comuns

Um bom professor não mostra apenas o caminho correto.

Ele mostra armadilhas.

Inclua quando possível:

* erros frequentes;
* soluções que parecem funcionar mas possuem problemas;
* decisões ruins comuns;
* confusões de iniciantes.

Aprender com erros evita repetir os mesmos caminhos.

---

# 💻 8. Código deve funcionar

Todo exemplo de código deve ser:

* executável quando possível;
* testado;
* acompanhado de explicação.

Evite exemplos artificiais que apenas mostram uma sintaxe.

Prefira exemplos que representem situações reais.

---

# 🖼️ 9. Crie seus próprios diagramas

Diagramas ajudam conceitos complexos.

Use ferramentas como:

* Mermaid;
* Excalidraw;
* Draw.io;
* Graphviz;
* ASCII Art.

O objetivo é criar uma explicação visual própria.

---

# 🤖 10. Use IA como ferramenta, não como autor

IA pode ajudar com:

* ideias;
* revisão;
* organização;
* geração de exercícios;
* encontrar pontos confusos.

Mas o colaborador deve:

* entender o conteúdo;
* verificar informações;
* testar exemplos;
* revisar a explicação.

O resultado final deve representar conhecimento humano validado.

---

# 👥 11. Escreva pensando em uma pessoa

Antes de publicar, imagine alguém lendo seu material.

Pergunte:

* Essa pessoa sabe o pré-requisito necessário?
* Eu expliquei os termos novos?
* Existe algum salto de raciocínio?
* Eu deixei claro o motivo das coisas?

Conteúdo técnico bom conversa com o leitor.

---

# ✅ Checklist antes de publicar

Antes de abrir um Pull Request:

* [ ] Expliquei o problema antes da solução.
* [ ] Usei minhas próprias palavras.
* [ ] Os exemplos foram testados.
* [ ] Criei exemplos ou analogias próprias.
* [ ] Incluí exercícios quando fizer sentido.
* [ ] Registrei dificuldades no Diário de Estudo.
* [ ] Revisei o conteúdo.
* [ ] Outra pessoa consegue entender sem contexto adicional.

---

# 🌱 Nossa meta

Um bom material da Cs-Brazil não deve apenas informar.

Ele deve fazer alguém pensar:

> "Agora eu finalmente entendi."

Esse é o padrão que buscamos construir juntos.
