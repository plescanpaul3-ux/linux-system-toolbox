Bash

#!/bin/bash
echo "=== SYSTEM HEALTH REPORT ==="
echo "Data: $(date)"
echo "-----------------------------------"
echo "[+] Utilizatori conectați:"
who
echo "-----------------------------------"
echo "[+] Spațiu disponibil pe disc:"
df -h / | awk 'NR==1 || NR==2'
echo "-----------------------------------"
echo "[+] Utilizarea memoriei RAM:"
free -m
