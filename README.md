# 📘 Git & GitHub Course

Este repositório contém anotações e comandos essenciais para aprender e dominar Git e GitHub. Ideal para quem está começando ou quer revisar os principais conceitos.

---

## 🧠 Comandos Fundamentais

### 🔹 `git add .`
Adiciona **todos os arquivos modificados ou novos** à área de preparação (staging area), prontos para serem commitados.

### 🔹 `git commit`
Salva as alterações no repositório local. Cria um **instantâneo** das mudanças preparadas.

- `--amend`: Permite **modificar o último commit**, seja para alterar a mensagem ou adicionar arquivos esquecidos.

### 🔹 `git remote`
Gerencia os **repositórios remotos**. Permite adicionar, remover e visualizar conexões com outros repositórios (como o GitHub).

### 🔹 `git push`
Envia os commits locais para o **repositório remoto** (ex: GitHub).

### 🔹 `git pull`
Atualiza seu repositório local com as alterações do repositório remoto. É uma combinação de `git fetch` + `git merge`.

### 🔹 `git revert`
Cria um novo commit que **desfaz** uma alteração anterior, sem alterar o histórico.

### 🔹 `git reset`
Remove commits ou arquivos da área de staging ou do histórico, dependendo das opções usadas (`--soft`, `--mixed`, `--hard`).

---

## 🔤 Status dos Arquivos
![Git Status](https://github.com/user-attachments/assets/fab95c8c-6a4e-460d-98e7-1ad2eda2c76d)

| Letra | Significado | Descrição |
|-------|-------------|-----------|
| `M`   | Modified     | Arquivo foi **modificado**, mas ainda não commitado. |
| `U`   | Untracked    | Arquivo **não rastreado** pelo Git, ainda não foi adicionado com `git add`. |

---

## 📄 Arquivo `.gitignore`

Usado para **ignorar arquivos ou pastas** que não devem ser rastreados pelo Git (ex: arquivos temporários, credenciais, dependências locais).

---