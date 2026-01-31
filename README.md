# 🚀 Kubuntu Beast: The 100+ Apps OMEGA

Tento nástroj slouží k interaktivnímu výběru a automatizované instalaci softwaru pro Kubuntu a další Debian-based distribuce. Pomocí HTML rozhraní si uživatel nakliká potřebné aplikace a vygeneruje si vlastní instalační skript `run_install.sh`.

## ✨ Klíčové vlastnosti
* **Široký výběr:** Více než 100 aplikací rozdělených do přehledných kategorií (Hry, Internet, Video, Audio, Vývoj, Grafika atd.).
* **Inteligentní skriptování:** Automaticky přidává potřebná PPA, klíče pro Microsoft repozitáře (Edge) a specifické zdroje (Thincast).
* **Systémová příprava:** Skript sám nastavuje 32-bitovou architekturu a instaluje základní nástroje jako `curl`, `ffmpeg` nebo `unrar`.
* **Moderní vzhled:** Temné UI optimalizované pro rychlou navigaci v kategoriích.

## 🛠 Jak projekt použít
1. Otevřete soubor `instalace.html` v prohlížeči.
2. Vyberte aplikace, které chcete nainstalovat.
3. Klikněte na tlačítko **VYGENEROVAT TOTÁLNÍ SKRIPT**.
4. V terminálu spusťte stažený soubor:
   ```bash
   chmod +x run_install.sh && ./run_install.sh
   Kategorie,Popis
   
🍷 Wine/Gaming,"Steam, WineHQ, Lutris, emulátory a herní utility."
🌐 Internet,"Prohlížeče (Edge, Chrome, Brave) a komunikátory."
🎬 Video/Audio,"Editory (Kdenlive, Audacity) a přehrávače (VLC, MPV)."
🟦 Dev/MS,"VS Code, Docker, Python, Git a virtualizace."
🎨 Grafika,"Krita, GIMP, Blender a správa fotek."
⚙️ Systém,"Stacer, BTOP, Timeshift a správa disků."
