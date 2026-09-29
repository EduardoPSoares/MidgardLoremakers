# MidgardLoremakers

Plugin Paper com painel web embutido para a equipe de lore escrever, organizar e entregar livros no jogo.

## Destaques

- Servidor HTTP embutido no plugin, com acesso por token temporário (`/loremaker token`).
- Editor de livros no navegador; os livros ficam em SQLite.
- Importação de livros e entrega a jogadores (`/loremaker give <jogador> <id>`).

## Stack

Java 21 · Maven · Paper API · SQLite · Gson

## Como compilar

```bash
mvn package
```
