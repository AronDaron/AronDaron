🇬🇧 [English version](https://github.com/AronDaron/AronDaron/blob/main/README.md)
 
# Cześć, jestem Radosław (AronDaron) 👋
 
**Specjalista IT, który stał się twórcą aplikacji AI.** Buduję aplikacje desktopowe oparte o LLM — takie, z których sam chcę korzystać. Po ponad 10 latach w IT support wykorzystuję tę wiedzę domenową do tworzenia realnych narzędzi z wykorzystaniem nowoczesnych stacków AI.
 
**Domyślny stack:**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![Pywebview](https://img.shields.io/badge/Pywebview-2B2B2B?style=flat)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-FF6B35?style=flat)

Wszystko działa lokalnie. Bez chmury, bez subskrypcji, bez telemetrii. Użytkownik jest właścicielem swoich danych.
 
---
 
## 📦 Projekty
 
### 🎯 [Dataset Generator](https://github.com/AronDaron/dataset-generator) — projekt flagowy
 
Desktopowa aplikacja bez kodowania do generowania wysokiej jakości syntetycznych datasetów do fine-tuningu LLM-ów. Trzyetapowy pipeline (tematy → outline'y → przykłady) z kontrolą jakości przez LLM Judge, deduplikacją opartą o embeddingi i integracją z HuggingFace Hub.
 
* **Mierzalne wyniki:** +4.5pp na HumanEval, +5.0pp na HumanEval+ (Qwen2.5-Coder-7B-Instruct, średnia z 5 uruchomień, słupki błędów się nie pokrywają)
* **Silnik Plan-then-Execute** — zróżnicowane, spójne datasety bez powtarzalnych wzorców
* Dashboard w czasie rzeczywistym przez SSE, eksport do ShareGPT / Alpaca / ChatML, integracja z HuggingFace Hub
* **Licencja AGPL-3.0** — open source z silną ochroną copyleft

`Next.js 16` `FastAPI` `Python` `SQLite` `OpenRouter` `Pywebview`
 
---
 
### 📈 [Finance Portfolio Tracker](https://github.com/AronDaron/priv-finance-app)
 
Aplikacja desktopowa do śledzenia akcji, ETF-ów, złota i polskich obligacji skarbowych — z analizą AI opartą o **architekturę wielu agentów Map-Reduce**.
 
* **Agenci Worker** (Gemini Flash) analizują każdą pozycję równolegle
* **Agent Manager** (Gemini Pro) syntetyzuje wszystkie raporty w jedną ocenę ryzyka portfela
* Deterministyczne wykrywanie reżimów rynkowych (Panic Mode, Bond Shock, Oil Shock...) — bez AI
* Pełne wsparcie dla wszystkich 8 typów polskich obligacji MF z aktualnymi danymi NBP/GUS CPI
* Macierz korelacji, porównanie z benchmarkiem, wskaźnik Sharpe'a, max drawdown

`Electron` `React` `TypeScript` `SQLite` `OpenRouter` `Yahoo Finance` `Map-Reduce`
 
---
 
## 🧠 Jak pracuję
 
Vibe-koduję z Claude Code. To znaczy, że projektuję architekturę, modele danych, analizuję przypadki brzegowe — a AI zajmuje się implementacją. Dzięki temu mogę dowozić działające aplikacje desktopowe ze złożonymi funkcjami (pipeline'y wieloagentowe, integracje z natywnymi API, odpowiednia lokalna persystencja danych) bez tradycyjnego wykształcenia CS.
 
Uważam, że to legalna i niedoceniana umiejętność. Rzemiosło polega na tym, żeby wiedzieć *co* zbudować i *dlaczego* — nie na szybkości pisania.
 
---
 
## 📍 Łódź, Polska
 
Otwarty na zdalne oferty związane z narzędziami AI, integracją LLM-ów i rozwojem produktu.
 
[![Ko-fi](https://img.shields.io/badge/Ko--fi-FF5E5B?style=flat&logo=ko-fi&logoColor=white)](https://ko-fi.com/arondaron)
 
