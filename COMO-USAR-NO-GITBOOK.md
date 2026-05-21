# Como usar no GitBook

Este pacote já está organizado para GitBook.

## Opção 1: Enviar para GitHub e usar Git Sync

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para o repositório.
3. No GitBook, conecte o espaço ao repositório.
4. O GitBook vai usar o `SUMMARY.md` para montar a barra lateral.

## Opção 2: Copiar manualmente

1. Crie um Space no GitBook.
2. Crie as páginas principais.
3. Copie o conteúdo dos arquivos `.md` para cada página correspondente.
4. Organize as subpáginas dentro da página principal de cada script.

## Sobre subcategorias escondidas

No GitBook, as subpáginas ficam dentro da página principal. Isso deixa a sidebar mais organizada e evita que tudo fique solto na navegação principal.

## Arquivo principal

O arquivo que controla a ordem da documentação é:

```txt
SUMMARY.md
```
