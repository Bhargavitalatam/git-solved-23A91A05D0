# Git Journey Log

## Student Info
- **Name:** Karunya
- **GitHub Repo:** https://github.com/Bhargavitalatam/git-solved-23A91A05D0
- **Date:** 26 October 2025

## Conflict Summary

### 1. config/app-config.yaml
- **Conflict:** Dev vs Prod environment settings
- **Resolution:** Merged both using `if` conditions for environment
- **Strategy:** Manual merge with environment-aware logic
- **Difficulty:** 4/5
- **Time Taken:** ~20 mins

### 2. config/database-config.json
- **Conflict:** Different DB credentials and ports
- **Resolution:** Used dev credentials with fallback to prod
- **Strategy:** JSON merge with comments
- **Difficulty:** 3/5
- **Time Taken:** ~15 mins

### 3. scripts/deploy.sh
- **Conflict:** Deployment steps diverged
- **Resolution:** Combined steps with conditional logic
- **Strategy:** Manual merge + tested locally
- **Difficulty:** 5/5
- **Time Taken:** ~30 mins

### 4. scripts/monitor.js
- **Conflict:** Monitoring logic vs AI enhancements
- **Resolution:** Preserved both with feature flag
- **Strategy:** Feature flag toggle
- **Difficulty:** 4/5
- **Time Taken:** ~25 mins

### 5. docs/architecture.md
- **Conflict:** Different diagrams and descriptions
- **Resolution:** Merged both with clear sectioning
- **Strategy:** Markdown merge with headers
- **Difficulty:** 3/5
- **Time Taken:** ~10 mins

### 6. README.md
- **Conflict:** Project description and feature list
- **Resolution:** Combined both, added experimental features under a new section
- **Strategy:** Manual merge with formatting
- **Difficulty:** 2/5
- **Time Taken:** ~10 mins

## Reflections
- Learned to resolve complex merge conflicts
- Understood how to use feature flags and environment-aware scripting
- Practiced advanced Git commands like `stash`, `cherry-pick`, `rebase`
- Gained confidence in managing real-world DevOps workflows
"- Always test after resolving conflicts" 
