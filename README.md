# 🚀 Projekt: boot.sh + Minimalny System + AI

Ten projekt to rozwijana roadmapa do budowy minimalnego środowiska startowego w stylu "od zera do AI", w oparciu o:

- 🐧 Alpine Linux / minimalny Linux
- 📦 Docker / VirtualBox
- 🧠 Python, Bash, AI Tools
- 👾 GUI / emulacja / Roblox (dla edukacji z dzieckiem)

---

## 🧱 Struktura projektu

```
/boot.sh              # Skrypt startowy
/init/                # Własne skrypty init
/scripts/             # Bash / Python tools
/ai/                  # Proste AI/LLM narzędzia
/.github/ISSUE_TEMPLATE/
```

---

## 🎯 Co dalej?

> Rozwijamy krok po kroku, w formie checklisty + issue + roadmapy

### Etap 1: 🐧 Minimalny Linux
- [ ] Alpine / busybox jako podstawa
- [ ] boot.sh do uruchamiania init
- [ ] Emulacja przez Docker/VM
- [ ] Obsługa userów, SSH, sieci

### Etap 2: 🔧 Skrypty systemowe
- [ ] własny init (`init.sh`)
- [ ] logowanie, proste menu terminalowe
- [ ] instalacja narzędzi (`apk`, `pip`, `wget`, itd.)

### Etap 3: 🧠 AI / interakcje
- [ ] dodanie prostego chatbota w Pythonie
- [ ] integracja z lokalnym LLM (np. ollama, llama.cpp)
- [ ] bash+python do analizy plików / logów

### Etap 4: 🎮 GUI / edukacja
- [ ] GUI przez `xinit`, `fluxbox` lub inny minimalny manager
- [ ] uruchamianie Roblox Studio z Wine lub zdalnie
- [ ] wspólna zabawa z dzieckiem jako forma nauki Linuxa i AI

---

## 📬 Komunikacja – używaj `Issues` jak czatu

📝 **Masz tam ISSUE_TEMPLATE – zgłaszaj tematy**:

- „Jak odpalić Alpine w Dockerze z SSH?”
- „Chcę napisać prosty init w Bashu”
- „Jak zainstalować llama.cpp lokalnie?”

---

## 🛠️ Dev Notes

- Repo może być rozgałęzione (branches: `boot`, `ai`, `gui`)
- Kod trzymamy w folderach tematycznych
- Roadmapa aktualizowana tutaj i w `Projects`/`WIKI`

---

## ❤️ Podziękowania

Ten projekt ma też charakter osobisty – to droga nauki, testowania, a może też wspólnych godzin z dzieckiem nad czymś, co działa „od zera”.
