⚡ rsync (Remote Sync)
What it does

Synchronizes files and directories

Transfers only modified data

Faster and more efficient

Syntax
`rsync [options] source destination
`
Example
```
rsync -av test.txt user@server:/home/user/
```
## 🔧 Common Options

| Option | Meaning |
|------|---------|
| `-a` | Archive mode (preserves permissions, ownership) |
| `-v` | Verbose output |
| `-z` | Compress data during transfer |
| `--delete` | Delete files on destination that are not present in source |


🧠 Key Takeaway
Use rsync for backups, synchronization, and large data transfers.