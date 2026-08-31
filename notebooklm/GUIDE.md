# Google NotebookLM — Cloud Developer Studerande Guide

> Ingen AI-CLI? Inget problem. NotebookLM är ett gratis webbverktyg från Google där du laddar upp dokument och chattar med dem. Perfekt för studerande som inte vill installera något.

---

## Vad är NotebookLM?

[NotebookLM](https://notebooklm.google.com) är ett gratis AI-verktyg från Google. Du laddar upp dokument som "källor" och kan sedan ställa frågor, få sammanfattningar och föra samtal baserade på innehållet.

Kräver: ett Google-konto. Inget kreditkort. Inget att installera.

---

## Kom igång på 5 minuter

### Steg 1 — Öppna NotebookLM

Gå till: https://notebooklm.google.com  
Logga in med ditt Google-konto (skolkonto fungerar).

### Steg 2 — Skapa ett nytt notebook

Klicka **"+ Nytt anteckningsbokblock"** (eller "New Notebook").

Ge den ett namn, t.ex. `Cloud Developer — Virtuell Marcus`.

### Steg 3 — Ladda upp källorna

Klicka **"+ Lägg till källa"** → **"Ladda upp fil"**.

Ladda upp dessa filer från mappen `sources/` (en i taget, eller alla på en gång):

| Fil | Vad den innehåller |
|-----|-------------------|
| `virtuell-marcus-persona.md` | Vem Marcus är och hur han undervisar |
| `kursplan-och-kontext.md` | Hela kursplanen + studentprofil |
| `regler-och-integritet.md` | Akademisk integritet + sokratisk metod + välmående |
| `projektideer.md` | Projektinspiration per kursnivå |
| `bokmarken.md` | Kurslänkar kurs 1–12 |

### Steg 4 — Aktivera Virtuell Marcus

Skriv i chatten:

```
Du är Virtuell Marcus, AI-lärarassistent för Cloud Developer på Campus Mölndal.
Jag läser kurs 1. Presentera dig.
```

Marcus svarar och är redo.

---

## Hur du använder det

NotebookLM är ett samtal, inte ett kommandosystem. Skriv naturlig svenska.

**Bra sätt att börja en session:**
```
Jag är tillbaka. Jag läser fortfarande kurs 2 och jobbar med SQL-uppgiften om JOINs.
```

**Be om hjälp med ett problem:**
```
Jag förstår inte varför min JOIN inte returnerar rätt rader. Kan vi gå igenom det?
```

**Brainstorma innan du kodar:**
```
Jag ska bygga en kontaktbok i C#. Kan du hjälpa mig planera stegen?
```

---

## Begränsningar jämfört med CLI-versionerna

| Funktion | CLI (claude/codex/gemini/open-code) | NotebookLM |
|----------|-------------------------------------|------------|
| Slash-kommandon | Ja (`/kurs`, `/start` m.fl.) | Nej — skriv naturlig text |
| Kör kod | Ja | Nej |
| Minns föregående session | Ja (via filer) | Nej — börja om varje gång |
| Uppdaterar filer | Ja | Nej |
| Gratis | Kräver abonnemang/API-nyckel | Ja, helt gratis |

NotebookLM är utmärkt för att **förstå koncept, planera och reflektera** — men inte för att köra kod. För koduppgifter, kombinera gärna NotebookLM med en vanlig AI-chatt som Gemini (gemini.google.com) eller ChatGPT.

---

## Tips

- Ladda upp nya kurskällfiler när du byter kurs — Marcus anpassar sig automatiskt
- Berätta alltid vilken kurs du läser i din första mening varje session
- Klistra in uppgiftsbeskrivningen direkt i chatten när du ber om hjälp

---

## Kontakt

- **IRL Marcus:** marcus.medina@nionit.com
- **Utbildningsledare:** anna-clara.wallen@educ.goteborg.se
