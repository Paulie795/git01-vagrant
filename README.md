# Git a Vagrant – první Linux server

Úvodní samostatná práce z předmětu **Operační systémy (OSY)** pro **3. I** na [SPOŠ Dvůr Králové nad Labem](https://www.sposdk.cz/).

## Moje řešení

- **Distribuce a verze:** Debian GNU/Linux 13.1 (trixie)
- **Použitý Vagrant box:** bento/debian-13 (1024 MB RAM, 1 CPU, VM `debian`, hostname `debian13`)
- **Adresář serveru:** srv01
- **Výsledek spuštění :** `vagrant up` proběhl bez chyb, `vagrant status` hlásí running, přihlášení přes `vagrant ssh` funguje, `cat /etc/os-release` potvrzuje Debian GNU/Linux 13 (trixie)
- **Kontrolní kód a záznam ze serveru:**

**Kontrolní kód:** `SPOS-3I-638ee63abe65942b07c7c52e3bb28a20f9a71f7d5680b3b2119b7e856c43f2d2`

text
Úloha: git-vagrant / SPOŠ / 3. I / v1
Distribuce: Debian GNU/Linux 13 (trixie)
Hostname: debian13
Kernel: 6.12.48+deb13-amd64
Virtualizace: oracle

