# Adaptive Disclosure Gateway — UX Prototype

Protótipo navegável da interface voltada a possíveis orientadores e revisores do projeto **Adaptive Disclosure Gateway**.

## Objetivo

A interface foi desenhada para alguém que entende software/IA, mas não conhece previamente B0–B4, policy matrix, runner ou audit schema. O conceito é explicado enquanto o usuário percorre um teste.

## Fluxo

1. **Entender** — análise local → divulgação controlada → reconstrução local.
2. **Documento** — arquivo próprio, exemplo sintético ou texto colado + tarefa em linguagem natural.
3. **Revisar** — mostra o que permaneceria local e o que seria removido, pseudonimizado, generalizado ou mantido **antes** da chamada externa.
4. **Resultado** — resposta final como foco, com comparação B0–B4 e detalhes técnicos disponíveis sob demanda.

## UX

- Português (Brasil) por padrão; inglês opcional.
- Tema claro e escuro, com preferência persistida no navegador.
- Fluxo novice-first; B0–B4 são uma camada de aprofundamento.
- Layout responsivo.
- Upload/drag-and-drop como parte do fluxo principal.

## Importante

Este repositório contém **somente o protótipo de interface**. O upload e a execução são simulados no navegador; nenhum arquivo é enviado e nenhuma chamada de LLM é realizada.

A implementação real será conectada ao core Python por meio da T20 (application/HTTP boundary), com ingestão estruturada pela T12 e provider real pela T22.

## GitHub Pages

O deploy está definido em `.github/workflows/pages.yml` e publica o conteúdo estático da raiz do repositório no GitHub Pages.
