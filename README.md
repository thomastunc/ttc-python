# Python Programmeren - The Trainee Company

Welkom bij de introductie van Python programmeren! In deze gids helpen we je stap voor stap met het opzetten van je Python-omgeving. Je leert hoe je Python en PyCharm installeert, hoe je Jupyter Notebook kunt gebruiken en hoe je een Git-repository kunt clonen om je eerste project te starten.

## 1. Installatie van Python

### Windows
1. Ga naar de officiële [Python-website](https://www.python.org/downloads/).
2. Klik op de knop **Download Python 3.x.x**.
3. Open het gedownloade bestand en zorg ervoor dat je het vinkje zet bij **Add Python to PATH**. Klik daarna op **Install**.
4. Nadat de installatie is voltooid, open je de opdrachtprompt (cmd) en voer je `python --version` in om te controleren of Python correct is geïnstalleerd.

### macOS
1. Open een Terminal en voer de volgende opdracht in om Homebrew te installeren (als je het nog niet hebt):
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Installeer Python met Homebrew:
   ```bash
   brew install python
   ```
3. Controleer of Python correct is geïnstalleerd door het volgende commando in de terminal te typen:
   ```bash
   python3 --version
   ```

### Linux
De meeste Linux-distributies hebben Python al geïnstalleerd. Je kunt dit controleren met het volgende commando:
```bash
python3 --version
```
Als je Python nog moet installeren:
```bash
sudo apt update
sudo apt install python3
```

## 2. Installatie van PyCharm

PyCharm is een populaire Integrated Development Environment (IDE) voor Python. Volg de onderstaande stappen om PyCharm te installeren.

### Windows & macOS & Linux
1. Ga naar de officiële [JetBrains-website](https://www.jetbrains.com/pycharm/download/).
2. Kies de **Community Edition** (gratis) en download de juiste versie voor jouw besturingssysteem.
3. Installeer de software door de instructies op het scherm te volgen.
4. Open PyCharm en stel het in met de standaardinstellingen.

## 3. Installatie van Jupyter Notebook

Jupyter Notebook is een veelgebruikte tool voor het schrijven en uitvoeren van Python-code in interactieve cellen.

### Installatie via PyCharm Terminal
1. Open PyCharm.
2. Klik rechtsonder op **Terminal** (of gebruik `Alt + F12` om de terminal te openen).
3. Installeer `pip` (indien nog niet geïnstalleerd) met het volgende commando:
   ```bash
   python -m ensurepip --upgrade
   ```
4. Installeer Jupyter met pip:
   ```bash
   pip install notebook
   ```
5. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Dit opent je webbrowser, waarin je Jupyter kunt gebruiken.

## 4. Git installeren en repository clonen

We gaan nu een repository van GitHub clonen waarin je Python-oefeningen kunt vinden. Git is een versiebeheersysteem waarmee je eenvoudig projectbestanden kunt downloaden, bewerken en bijwerken.

### Git installeren
1. Download Git vanaf de [officiële Git-website](https://git-scm.com/download) en installeer het.
2. Controleer of Git correct is geïnstalleerd door het volgende commando in je terminal of command prompt te typen:
   ```bash
   git --version
   ```

### Repository clonen
1. Open PyCharm en kies **New Project**.
2. Selecteer **Get from Version Control** in het welkomstscherm of ga naar **VCS > Get from Version Control** in het menu.
3. Plak de volgende URL in het veld voor de Git-repository:
   ```
   https://github.com/thomastunc/ttc-python
   ```
4. Kies een locatie waar je het project wilt opslaan en klik op **Clone**.
5. PyCharm downloadt nu de bestanden van de repository.
6. Open nu de Jupyter webinterface en navigeer naar de map van het geclonede project.
7. Open de eerste notebook en begin met programmeren!