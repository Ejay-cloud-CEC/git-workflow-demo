# Git Workflow Demo 🌳

Demonstrates professional Git workflow used in DevOps teams to keep `main` branch clean.

## 🌿 Branching StrategyGit Workflow Demo

## 🔄 Workflow Steps Demonstrated
1. `git checkout -b feature/name` - Create feature branch from develop
2. Commit changes with conventional commits: `feat:`, `fix:`
3. `git rebase -i HEAD~3` - Squash messy commits before PR
4. `git checkout develop && git merge feature/name` - Merge clean history
5. `git branch -d feature/name` - Delete merged branch

## ✅ Git Commands Mastered
**Branching:** `checkout -b`, `merge`, `branch -d`  
**History:** `rebase -i`, `reword`, `squash`, `push --force`  
**Remote:** `push origin`, `push --delete`

## 🎯 Why This Matters
Prevents "WIP", "fix typo", "asdf" commits from polluting main branch.  
Used by companies like Google, Netflix, Facebook for clean Git history.

Part of 42-Day DevOps Journey - Week 1: Git Mastery ✅
