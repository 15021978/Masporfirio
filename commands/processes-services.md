---

## `commands/processes-services.md`

# Processes and Services (ps, top, systemctl)

Notes and examples for checking processes and managing services (systemd).

---

## Quick Reference

| Command | Purpose | Example |
|--------|---------|---------|
| `ps` | Show running processes | `ps aux` |
| `top` | Real-time process view | `top` |
| `htop` | Improved process viewer (if installed) | `htop` |
| `systemctl` | Manage systemd services | `systemctl status ssh` |
| `journalctl` | View logs (systemd) | `journalctl -u ssh` |

---

## Processes

### `ps`
List all processes:
```bash
ps aux
