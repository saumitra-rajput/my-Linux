# 🌐 Linux Networking & Utility Commands – Quick Guide (Part 2)

Short explanations and examples of commonly used Linux networking and system utility commands.

---

## 1️⃣ route
Displays or modifies the IP routing table.

```bash
route -n
```
### ⚠️ Deprecated — replaced by ip route.

## 2️⃣ nmap

Network scanner used to discover hosts, open ports, and services.
```
nmap google.com
nmap -p 80,443 192.168.1.0/24
```

Used for security auditing and network discovery.

## 3️⃣ wget

Downloads files from the internet using HTTP, HTTPS, or FTP.
```
wget https://example.com/file.zip
```

Best for non-interactive downloads.

## 4️⃣ watch

Runs a command repeatedly and displays the output.
```
watch df -h
```

Used to monitor real-time changes.

## 5️⃣ iptables

Configures Linux firewall rules.
```
iptables -L
```

Used for packet filtering and traffic control.
⚠️ Advanced command — handle with care.

## 6️⃣ traceroute

Shows the path packets take to reach a destination.
```
traceroute google.com
```

Used to diagnose network routing issues.

## 7️⃣ curl vs wget
```
curl
```

Transfers data and supports APIs, headers, and multiple protocols.
```
curl -X GET https://example.com

```
```
curl -I https://example.com
```
```
wget
```
Focuses on downloading files.
```
wget https://example.com/file.zip
```
## 🔍 Comparison: curl vs wget

| Feature | curl | wget |
|------|------|------|
| API support | ✅ Yes | ❌ No |
| File download | ✅ Yes | ✅ Yes |
| Headers control | ✅ Yes | ❌ Limited |
| Recursive download | ❌ No | ✅ Yes |

## 🔄 Upgrade for More Features

Install common networking tools:
```
sudo apt install nmap traceroute curl wget iptables
```

## 🧠 Key Takeaway

These commands are essential for network analysis, security, monitoring, and DevOps workflows.

