# View and Search (Linux)

Notes and examples for viewing file contents and searching for text or files.

---

## Quick Reference

| Command | Purpose | Example |
|--------|---------|---------|
| `cat` | Print file contents | `cat file.txt` |
| `less` | View file page-by-page | `less /var/log/syslog` |
| `head` | Show first lines | `head -n 20 file.txt` |
| `tail` | Show last lines | `tail -n 50 file.txt` |
| `grep` | Search text patterns | `grep -i error file.log` |
| `find` | Find files by name/criteria | `find . -name "*.log"` |

---

## View File Contents

### `cat`
Good for small files:
```bash
cat notes.txt
