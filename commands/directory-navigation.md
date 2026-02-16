# Directory Navigation (Linux)

Notes and examples for navigating the Linux filesystem using the command line.

---

## Quick Reference

| Command | Purpose | Example |
|--------|---------|---------|
| `pwd` | Show current directory (full path) | `pwd` |
| `cd <path>` | Change directory | `cd /etc` |
| `cd` / `cd ~` | Go to home directory | `cd` |
| `cd ..` | Go to parent directory | `cd ..` |
| `cd .` | Stay in current directory (no-op) | `cd .` |
| `cd -` | Go back to previous directory | `cd -` |
| `ls` | List directory contents | `ls -la` |

---

## Commands Explained

### `pwd` — Print Working Directory
Displays the full path of your current working directory.
```bash
pwd

