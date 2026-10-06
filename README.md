# PlacaFácil — V6 Fotográfica Realista

Esta versão mantém a lógica e as funções da V5 e altera principalmente a **aparência visual**.

## O que mudou na V6

- Fundos da prévia agora usam **imagens fotográficas** derivadas da referência real do usuário.
- As bases usam **texturas fotográficas reais** de:
  - aço escovado
  - madeira
  - base preta
  - acrílico/reflexivo
- O showroom das 6 placas usa **seis fotos reais de referência**, separadas em cartões individuais.
- Clicar em uma foto continua aplicando formato, base e paleta ao editor.
- Todo o restante foi preservado:
  - upload de logo
  - QR Code
  - textos
  - cores
  - fontes
  - editor de posição X/Y e escala
  - checkout
  - painel admin
  - PostgreSQL / Render

## Publicar no GitHub / Render

1. Extraia o ZIP.
2. Envie todo o conteúdo para a raiz do repositório `placas-personalizadas`.
3. Faça `Commit changes` na branch `main`.
4. O Render deve publicar automaticamente; se não publicar, use `Manual Deploy > Deploy latest commit`.
5. Depois abra o site com `Ctrl + F5`.
