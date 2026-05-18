# FastRechnen.de — Kostenlose Online-Rechner für Deutschland

## Stack
Static HTML/CSS/JS — kein Framework, kein Backend.

## Deploy
```bash
git init
git add .
git commit -m "initial: 10 Rechner, Apple-Design, #008f7a"
git remote add origin https://github.com/yassinsanab/fastrechnen.git
git push -u origin main
```
Vercel: New Project → Import yassinsanab/fastrechnen → Framework: Other → Deploy

## Nach dem Deploy
- Ersetze `G-XXXXXXXXXX` in allen HTML-Dateien mit deiner echten GA4-ID
- Vercel → Settings → Domains → `fastrechnen.de` hinzufügen

## Rechner (alle aktuell 2024/2025)
- Netto-Brutto-Rechner (§32a EStG, GKV/PKV, alle Steuerklassen)
- Lohnsteuerrechner (mit Kinderfreibetrag, Werbungskosten)
- Mehrwertsteuerrechner (19%/7%, Netto↔Brutto)
- Kreditrechner (Annuitätendarlehen, Wunschrate)
- Rentenrechner (Entgeltpunkte, Rentenwert 37,60€)
- Abfindungsrechner (Fünftelregel §34 EStG)
- Kindergeldrechner (250€/Kind, 2024)
- Pendlerpauschale (0,30€/0,38€, bis Ende 2026)
- Urlaubsrechner (BUrlG, anteiliger Anspruch)
- BMI-Rechner (WHO-Klassifikation)
