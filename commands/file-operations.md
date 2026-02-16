# File Operations (Linux)

Notes and examples for creating, copying, moving, and removing files and directories.

---

## Quick Reference

| Command | Purpose | Example |
|--------|---------|---------|
| `ls` | List files/directories | `ls -lah` |
| `touch` | Create empty file / update timestamp | `touch notes.txt` |
| `mkdir` | Create directory | `mkdir projects` |
| `cp` | Copy files/directories | `cp file1 file2` |
| `mv` | Move/rename files/directories | `mv old new` |
| `rm` | Remove files/directories | `rm file.txt` |
| `rmdir` | Remove empty directory | `rmdir emptydir` |

---

## Commands Explained

### `ls` — List Directory Contents
Common options:
- `-l` long format
- `-a` show hidden files
- `-h` human-readable sizes
```bash
ls -lah
