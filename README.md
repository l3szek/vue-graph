# Zadanie rekrutacyjne — Senior Frontend Engineer

**Wiki Knowledge Graph** — przeglądarka wiedzy oparta na grafie, napisana w Vue 3 + Vite. Aplikacja wizualizuje sieć pojęć (węzły) i powiązań między nimi (krawędzie) z zakresu obsługi ekspresu do kawy. Dane są mock'owane lokalnie w `src/data/mock.js`.

---

## Uruchomienie projektu

```bash
npm install
npm run dev
```

Aplikacja startuje pod adresem `http://localhost:5173`.

---

## Struktura projektu

```
src/
├── style.css          # globalny arkusz stylów (ciemny motyw)
├── App.vue            # główny komponent — header, zakładki, panel detali
├── main.js            # punkt wejścia aplikacji
├── data/
│   └── mock.js        # dane: 16 węzłów, 20 krawędzi, 3 źródła, transkrypty
├── components/
│   ├── Graph.vue       # wizualizacja grafu (force-graph)
│   ├── ChunkPanel.vue  # panel szczegółów węzła
│   ├── SourcesView.vue # lista źródeł z częściami
│   └── PartPanel.vue   # panel szczegółów części źródła
├── locales/            # (do utworzenia w Zadaniu 1c)
│   ├── en.json
│   └── pl.json
└── utils/              # (do utworzenia w Zadaniu 1a/1b)
    ├── format.js
    └── types.js
```

---

