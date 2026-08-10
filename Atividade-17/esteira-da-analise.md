# Esteira da Análise — BiblioTech

**Estudante:** Gustavo Maciel da Silva

## Funcionalidade 1: Reservar Livro

- **1.1. Fala do cliente:** "Quando um livro não esta disponivel, eu gostaria de reservalo para que eu possa empresta-lo quando ele for devolvido "
- **1.2. História de usuário:** Como leitor, quero poder reservar um livro, para que mesmo quando ele não esteja disponivel, eu possa empresta-lo quando estiver.
- **1.3. Requisito:** RF01 — O sistema deve permitir a reserva de um livro
- **1.4. Caso de uso (RF01):** Ator Leitor → "Reservar livro" (verbo + objeto)

## Funcionalidade 2: Emprestar Livro

- **2.1. Fala do cliente:** "Quando o aluno vem emprestar um livro, eu preciso saber com quem esta e qual livro é"
- **2.2. História de usuário:** Como leitor, quero poder emprestar um livro, para poder levar pra casa e ler.
- **2.3. Requisito:** RF02 — O sistema deve permitir o emprestimo de um livro 
- **2.4. Caso de uso (RF02):** Ator Bibliotecario → "Emprestar livro" (verbo + objeto)

## Rastreabilidade
'
| Elipse no diagrama | Veio do requisito | Que veio da fala |
|---|---|---|
| Reservar livro | RF01 | 1.1 |
| Emprestar livro | RF02 | 2.1 |

<!-- Nível A: conte o caminho completo de cada funcionalidade,
     da fala do cliente até o que está desenhado no diagrama. -->

## Relacionamento entre casos de uso (nível A)

- Tipo: «include»
- Entre: Emprestar livro e Reservar livro
- Por que é esse e não o outro: É um include pois quando você vai emprestar um livro é necessario ver se ninguém reservou o livro antes

## Autoavaliação

**Conceito pretendido:** _A_ (A / B / C)

- Conversei sobre esta atividade com: Cauã (ou "ninguém")
- Esteira da análise: A (nas duas esteiras) (diga onde)
- Diagrama e notação: A
- Rastreabilidade: B
- Organização da entrega: B