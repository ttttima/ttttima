
# 👋 Hey, I'm Tima!

## Git Cheat Sheet

### 1. Git Configuration

Run on every computer:

```bash
git config --global user.name "Jan Kowalski"
git config --global user.email "jan@example.com"
```

### 2. First Project Upload

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USER/REPO.git
git push -u origin main
```

### 3. Upload Changes

```bash
git add .
git commit -m "Added new feature"
git push
```

### 4. Download Changes

```bash
git pull
```

### 5. Check Repository Status

```bash
git status
```

### 6. Check Git Configuration

```bash
git config --global --list
```

### 7. Check Remote Repository

```bash
git remote -v
```

### 8. Create a New Branch

```bash
git switch -c feature-name
```

### 9. Switch Branch

```bash
git switch main
```

### 10. View Commit History

```bash
git log --oneline
```

---

*Happy coding! 🚀*
