# Pessoas de Bolso

Web app pessoal (PWA) para iPhone e Mac: o painel do banco local de pessoas no celular — aniversários,
fichas, árvore genealógica de cada pessoa, mapa e descobertas.

- Sem servidor e sem conta: os dados ficam no aparelho (IndexedDB) e, se ligado, num cofre criptografado
  (AES-256-GCM, chave derivada da senha com PBKDF2) num repositório **privado** do GitHub do dono.
- Este repositório tem **só o código**. Nenhum dado de pessoa fica aqui.
- A base vem do banco do Mac trancada com a chave pública do app (caixa de entrada); o que é mudado no
  celular volta trancado com a chave pública do Mac (caixa de saída). Nem o GitHub lê.

Publicação: GitHub Pages, branch `main`, pasta raiz. No iPhone: Safari › Compartilhar › Adicionar à Tela de Início.
