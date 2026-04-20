🇬🇧 [English version](./README.en.md)

# Cześć, jestem Radosław (AronDaron) 👋

**Specjalista IT, który buduje aplikacje desktopowe z AI.** Buduję narzędzia, których sam chcę używać. Po 10+ latach w IT wsparciu przekuwam tę wiedzę domenową w realne produkty na nowoczesnym stacku z LLM-ami.

---

## 🛠️ Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-FF6B35?style=flat)

**Mój domyślny stack:** Electron + React + TypeScript + SQLite + OpenRouter API

Wszystko działa lokalnie. Bez chmury, bez subskrypcji, bez telemetrii. Dane należą do użytkownika.

---

## 📦 Projekty

### 📈 [Finance Portfolio Tracker](https://github.com/AronDaron/priv-finance-app)
Desktopowa aplikacja do śledzenia akcji, ETF-ów, złota i polskich obligacji skarbowych — z analizą AI opartą na **architekturze Map-Reduce z wieloma agentami**.

- **Agenty Worker** (Gemini Flash) analizują każdą pozycję równolegle
- **Agent Manager** (Gemini Pro) syntetyzuje wszystkie raporty w jedną ocenę ryzyka portfela
- Deterministyczna detekcja reżimu rynkowego (Tryb Paniki, Szok Obligacyjny...) — bez AI
- Pełna obsługa 8 typów obligacji MF z danymi NBP/GUS CPI w czasie rzeczywistym
- Macierz korelacji, benchmark, Sharpe ratio, max drawdown
- 100% lokalnie — SQLite na dysku, klucz OpenRouter nigdy nie opuszcza komputera

`Electron` `React` `TypeScript` `SQLite` `OpenRouter` `Yahoo Finance` `Map-Reduce`

---

### 🎮 [Anime & Games Tracker](https://github.com/AronDaron/anime-search-app)
Osobisty tracker anime i gier — zbudowany na własny użytek, ale publiczny.

`Electron` `React` `TypeScript`

---

### 🏥 Analizator dokumentów medycznych *(Prywatne)*
Analiza dokumentów medycznych przez OCR z wieloma personami AI-specjalistów i funkcją "konsylium" — synteza wszystkich specjalistów w jedną ocenę. Zbudowany z dokładnym przeglądem prawnym: EU MDR, EU AI Act, RODO — z obowiązkowym aktywnym potwierdzeniem przy starcie.

`Electron` `React` `TypeScript` `Gemini Flash` `OCR`

---

### 💪 FitRPG *(w trakcie rozwoju)*
Tracker fitness z mechanikami RPG — 11 statystyk, 21 rang, system zmęczenia i rdzewienia. Opcjonalna integracja AI przez OpenRouter.

`Electron` `React` `TypeScript` `SQLite` `OpenRouter`

---

### 🌐 Narzędzie do lokalizacji gier Owlcat *(w trakcie rozwoju, prywatne)*

Desktopowy pipeline do tłumaczenia gier Owlcat Games (Pathfinder, Rogue Trader) z angielskiego na polski. Przetwarza pliki lokalizacyjne `.json` z rygorystycznym zachowaniem kluczy silnika, tagów i tokenów formatowania — AI odpowiada za naturalnie brzmiący polski, narzędzie pilnuje poprawności strukturalnej.

* Wsadowe tłumaczenie plików `.json` z walidacją integralności kluczy
* Osobny pass korekty gramatycznej na wyjściu AI — płynność bez łamania składni silnika
* **Semantyczny cache** przez LanceDB — wcześniej przetłumaczone frazy dopasowywane embeddingami, nie tylko dokładnym stringiem, co ogranicza zbędne wywołania API
* System checkpointów w SQLite — zadania są wznawialne, raz przetłumaczone frazy nie są przetwarzane ponownie
* Podgląd tłumaczenia na żywo w trybie deweloperskim (`npm run dev:web`)
* Docelowy build jako Electron `.exe` — po ustabilizowaniu logiki

`React` `TypeScript` `Node.js` `SQLite` `LanceDB` `OpenRouter`

---

## 🧠 Jak pracuję

Vibe coduję z Claude Code. To znaczy: projektuję architekturę, modeluję dane, myślę o edge case'ach — a implementację zostawiam AI. Dzięki temu mogę wypuszczać realne aplikacje desktopowe ze złożonymi funkcjami (pipelines wieloagentowe, natywne integracje API, lokalna persystencja danych) bez tradycyjnego tła CS.

Uważam, że to legitymna i niedoceniana umiejętność. Rzemiosło polega na tym, żeby wiedzieć *co* i *dlaczego* budować — nie na tym, żeby szybciej pisać.

---

## 📍 Łódź

Otwarty na zdalne możliwości w obszarze narzędzi AI, integracji LLM i product developmentu.

[![Ko-fi](https://img.shields.io/badge/Ko--fi-FF5E5B?style=flat&logo=ko-fi&logoColor=white)](https://ko-fi.com/arondaron)
