# Como participar — hypercode-java25

1) Criando sua pasta de participante
- Crie `users/<seu-github-username>/`.
- Adicione `profile.md` e `progress.md` (exemplos abaixo).
- Coloque soluções em `users/<seu-username>/solutions/` dentro de subpastas nomeadas pelo id do desafio (ex: `basic-001/Solution.java`).

2) Exemplo de `profile.md`
```md
---
username: seu-username
name: Seu Nome
bio: Estudante/Dev Java
joined: 2026-01-05
---
# Seu Nome (@seu-username)

Breve apresentação.
```

3) Exemplo de `progress.md` (formato esperado)
```md
---
username: seu-username
points: 0
completed: []
---

# Progress — seu-username

- [ ] basic-001 — Introdução a Java (1 pt)
- [ ] basic-002 — Variáveis (1 pt)
```

4) Fluxo de contribuição
- Faça fork, crie branch `add-user-<username>`, faça commit e abra PR para `main`.
- Use título: `Add user <username>` ou `Update progress for <username>`.
- Mantenedores revisarão; PR aprovado entra no repo.

5) Política de solução
- Soluções devem ser colocadas em `users/<username>/solutions/<challenge-id>/`.
- Se quiser, inclua um arquivo `explain.md` explicando a solução.