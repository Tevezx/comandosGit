# 💻 Git Commands

Repositório pessoal com os principais comandos Git para consulta rápida.

---

## 🚀 Inicialização

### Criar repositório
```bash
git init
```

### Clonar repositório
```bash
git clone <url>
```

---

## 📄 Versionamento

### Status
```bash
git status
```

### Adicionar arquivos
```bash
git add nome-arquivo
git add .
```

### Commit
```bash
git commit -m "mensagem"
```

### Histórico
```bash
git log
git log --oneline
```

---

## 🌿 Branch

### Listar
```bash
git branch
```

### Criar
```bash
git branch nome-branch
```

### Trocar
```bash
git checkout nome-branch
# ou
git switch nome-branch
```

### Criar e trocar
```bash
git checkout -b nova-branch
git switch -c nova-branch
```

---

## 🔄 Remoto

### Ver remoto
```bash
git remote -v
```

### Adicionar remoto
```bash
git remote add origin <url>
```

### Push
```bash
git push origin nome-branch
```

### Pull / Fetch
```bash
git pull origin nome-branch
git fetch
```

---

## 🔀 Integração

### Merge
```bash
git merge nome-branch
```

### Rebase
```bash
git rebase nome-branch
```

---

## 🧰 Utilidades

### Diff
```bash
git diff
```

### Stash
```bash
git stash
git stash pop
```

### Reset
```bash
git reset nome-arquivo
git reset --soft HEAD~1
```

### Revert
```bash
git revert <id-commit>
```

---
