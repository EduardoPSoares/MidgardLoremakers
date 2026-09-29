# MidgardLoremakers

[![Build](https://github.com/EduardoPSoares/MidgardLoremakers/actions/workflows/build.yml/badge.svg)](https://github.com/EduardoPSoares/MidgardLoremakers/actions/workflows/build.yml)
![Java](https://img.shields.io/badge/Java-21-E76F00?logo=openjdk&logoColor=white)
![Paper](https://img.shields.io/badge/Paper-1.21-2F80ED)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![License](https://img.shields.io/github/license/EduardoPSoares/MidgardLoremakers)

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
