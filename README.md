# Git a Vagrant – první Linux server

Samostatná práce z předmětu Operační systémy (OSY), SPOŠ Dvůr Králové nad Labem.
Autor: Pavel Podzimek

## Moje řešení

- **Distribuce a verze:** Debian GNU/Linux 13.1 (trixie)
- **Použitý Vagrant box:** bento/debian-13 (1024 MB RAM, 1 CPU, VM `debian`, hostname `debian13`)
- **Adresář serveru:** srv01
- **Výsledek spuštění a přihlášení:** `vagrant up` proběhl bez chyb, `vagrant status` hlásí running, přihlášení přes `vagrant ssh` funguje, `cat /etc/os-release` potvrzuje Debian GNU/Linux 13 (trixie)
- **Případné problémy a jejich řešení:** První `git clone` vlastního repozitáře selhal kvůli špatné URL, proto jsem repozitář inicializoval lokálně (`git init -b main`) a remote přidal ručně. Push pak GitHub odmítl kvůli soukromému e-mailu (GH007), což jsem vyřešil nastavením noreply adresy a přepsáním autora commitů.
- **Kontrolní kód a záznam ze serveru:**

**Kontrolní kód:** `SPOS-3I-638ee63abe65942b07c7c52e3bb28a20f9a71f7d5680b3b2119b7e856c43f2d2`

```text
Úloha: git-vagrant / SPOŠ / 3. I / v1
Distribuce: Debian GNU/Linux 13 (trixie)
Hostname: debian13
Kernel: 6.12.48+deb13-amd64
Virtualizace: oracle
Čas UTC: 2026-09-25T06:17:12Z
Náhodné ID: 869ab909-6d9b-446a-a632-13041158a760
```

- **Bonus – AI obrázek a použitý prompt:** neplním
