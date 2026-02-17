---
## `commands/archive-and-compress.md`

# Archive and Compress (tar, gzip)

Notes and examples for archiving and compressing files (common for backups and transfers).

---

## Quick Reference

| Command | Purpose | Example |
|--------|---------|---------|
| `tar` | Create/extract archives | `tar -czf backup.tar.gz dir/` |
| `gzip` | Compress a file | `gzip file.txt` |
| `gunzip` | Decompress `.gz` | `gunzip file.txt.gz` |

---

## `tar` Basics

### Create a `.tar.gz` archive
- `c` create
- `z` gzip compression
- `f` filename
- `v` verbose (optional)

```bash
tar -czf backup.tar.gz myfolder/
