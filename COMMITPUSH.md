# Git Commit & Push Commands

A log of the successful git commands used to build and manage the Design Museum repository.

## Initial Commit (Master)
```bash
git add CURATOR_NOTES.md && git commit -m "Add CURATOR_NOTES.md"
git remote add origin https://github.com/ae459/Design-Museum.git && git push -u origin master
```

## Switch to Main Branch
```bash
git branch -M main
git pull --rebase origin main && git push -u origin main
```

## Commit AGENTS.md
```bash
git add AGENTS.md && git commit -m "Add AGENTS.md with design history discussion prompts and constraints"
git push
```

## Commit Website & Style Changes
```bash
git add index.html && git commit -m "Add curator cards website with blue and white design" && git push
```

## Refactor CSS and Push
```bash
git add . && git commit -m "Refactor: Separate CSS from HTML" && git push
```

## Organize Files into Docs Folder
```bash
git mv index.html style.css prompt-pack.html docs/
git commit -m "Feat: organize files into docs folder" && git push
```

## Log Final Commit
```bash
git add COMMITPUSH.md && git commit -m "Docs: add commit and push command log" && git push
```
