# CLO26Helper — Virtuell Lärare

**Cloud Developer (CLO26) på YRGO / Campus Mölndal**

Persona-promptar för AI-verktyg. Syftet: AI:n hjälper studerande att *tänka*, inte att göra deras uppgifter åt dem.

---

## Sätt upp det en gång — gäller i alla projekt

De flesta verktyg har **globala inställningar** för AI-instruktioner. Sätt det där och det fungerar automatiskt i varje projekt du öppnar.

### GitHub Copilot (rekommenderas — gratis för studerande)
1. Gå till [github.com/settings/copilot](https://github.com/settings/copilot)
2. Under **Personal custom instructions** — klistra in innehållet från `copilot/copilot-instructions.md`

### Cursor
1. `Cursor Settings` → `Rules for AI` → klistra in innehållet från `cursor/.cursorrules`
2. Eller: kopiera `cursor/.cursorrules` till roten av varje projekt

### Windsurf
1. `Settings` → `Cascade` → `Global Rules` → klistra in innehållet från `windsurf/.windsurfrules`
2. Eller: kopiera `windsurf/.windsurfrules` till roten av varje projekt

---

## Övriga verktyg

### Claude Code
```
Läs /path/to/clo26helper/claude/CLAUDE.md och agera utifrån det.
```
Eller kopiera `claude/CLAUDE.md` till roten av ditt projekt — Claude Code läser den automatiskt.

### Codex CLI
```
Läs /path/to/clo26helper/codex/AGENTS.md och agera utifrån det.
```
Eller kopiera `codex/AGENTS.md` som `AGENTS.md` till ditt projekt.

### Gemini CLI
```
Läs /path/to/clo26helper/gemini/GEMINI.md och agera utifrån det.
```

### NotebookLM
Se `notebooklm/GUIDE.md` för instruktioner.

---

## Filer

| Fil | Verktyg | Sätt upp |
|-----|---------|---------|
| `claude/CLAUDE.md` | Claude Code | Kopiera till projektroten |
| `codex/AGENTS.md` | OpenAI Codex CLI | Kopiera till projektroten |
| `gemini/GEMINI.md` | Gemini CLI | Kopiera till projektroten |
| `cursor/.cursorrules` | Cursor | Global inställning eller kopiera |
| `copilot/copilot-instructions.md` | GitHub Copilot | Global inställning på github.com |
| `windsurf/.windsurfrules` | Windsurf | Global inställning eller kopiera |
| `notebooklm/GUIDE.md` | NotebookLM | Läs guiden |

---

## Vad Virtuell Lärare gör

- Frågar vad du jobbar med och läser uppgiften
- Ställer sokratiska frågor istället för att ge svar
- Påminner om 15-minutersregeln: fastnat → fråga gruppen → Virtuell Lärare → IRL Marcus
- Håller dig bort från lärandefällor: brainstorma och planera *innan* du kodar
- Eskalerar till rätt person vid stress, kris, eller när AI inte räcker

## Vad Virtuell Lärare inte gör

- Skriver din inlämning
- Ger dig lösningskod att klistra in
- Säger "Vilken fantastisk fråga!"

---

**Läraren (IRL):** din lärare på plats
