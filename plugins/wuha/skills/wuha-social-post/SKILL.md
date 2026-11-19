---
name: wuha-social-post
description: Social-Posts für WUHA schreiben, prüfen und automatisch über den Velocity-Connector (https://www.velocity.li/mcp) einplanen. Nutzen bei „Post für WUHA“, „WUHA Wochenplan“, „Content für Instagram/TikTok/YouTube“, „über Velocity posten“.
---

# WUHA – Social-Post-Workflow (Velocity)

Vorher Skill `wuha-brand` laden. Antworten an Nutzer: Deutsch, kurz. Alle Posts: **Englisch**.

## 0. Verbindung prüfen
- Velocity-Tools vorhanden? (ToolSearch „velocity“)
- Fehlen sie: Nutzer bitten, unter claude.ai → Settings → Connectors → *Add custom connector* `Velocity` mit URL `https://www.velocity.li/mcp` hinzuzufügen, einloggen, Zugriff erlauben, neue Session starten. Bis dahin Texte + Plan als Datei liefern.
- Im Velocity-Account müssen die WUHA-Kanäle verbunden sein (Instagram, Facebook, TikTok, YouTube, ggf. LinkedIn).

## 1. Standard-Wochenplan (12 Posts)
| Kanal | Posts/Woche | Format |
|---|---|---|
| Instagram @wuha_music | 3 | 1 Reel, 1 Carousel, 1 Foto/Quote |
| Facebook /wuhamusic | 3 | Video, Foto, Text+Link |
| LinkedIn | 2 | Behind the scenes Produktion / Studio Abracadabra, Release-News |
| TikTok @wuha_music | 2 | Kurzvideo 9:16, 15–30 s, Hook in 1 s |
| YouTube @wuha_music | 2 | Shorts 9:16 (oder 1 Video + 1 Short) |

LinkedIn ist kein Brand-Kanal im Guide → Profil/Seite beim Nutzer erfragen, nichts erfinden.

## 2. Zeiten (Wiener Zeit, nach Zielmarkt rotieren)
- Südostasien (ID, PH, MY): 12–14 Uhr
- Europa (IT, AT, ES): 18–20 Uhr
- Amerika (US, BR, CO): 1–3 Uhr → immer vorplanen
- Pro Woche jede Region mind. 1× pro Kanal treffen. Prioritär: ID, AT, ES, US; dazu IT, PH (Hörer → Fans).

## 3. Content-Mix
- 40 % Musik (Snippet, Release, Club Mix)
- 25 % Mood (Neon, Nacht, Drive, Schwarz-Weiß)
- 20 % Behind the scenes (Wolfgang, Andreas, Studio)
- 15 % Fans/Länder („Terima kasih, Indonesia“) + Album-CTA: "Be the first to know when our album is released"

## 4. Text-Regeln
- Zeile 1 = Hook, kurze Bildsätze, einfaches Englisch
- Keine Serien-Nummern im Text („Postcard #2“ → „Postcard from Vienna to Manila“)
- Max. 1–2 Emojis, keine „Check out our new song!!!“, keine Superlative
- Sign-off optional: "Feel the Groove."
- Link: Spotify-Link zum jeweiligen Song (Liste in `wuha-brand`), nicht Artist-Link
- Hashtags: **immer `#wuha #musiclovers` dazu** (auf jedem Kanal), plus Instagram 3–5, TikTok 3–4, YouTube 3, Facebook 1–2, LinkedIn 3 thematische. Pool: `#synthpop #synthwave #80smusic #newmusic #postcardsfromvienna`
- Fehlendes Datum/Info → Platzhalter `[RELEASE DATE]`, nachfragen

## 5. Medien
- Design nach `wuha-brand` (Schwarz-Weiß, Akzent Pink `#FF2E88`)
- Animation/Video → Hyperframes
- TikTok/YouTube brauchen Video. Ohne Datei: Nutzer fragen oder in Hyperframes bauen.

## 6. Check vor Freigabe
- [ ] Englisch, einfach
- [ ] Hook Zeile 1
- [ ] Emoji ≤ 2, Hashtags passen
- [ ] Gastsänger korrekt („Marc Voc“, kein echter Name)
- [ ] Zeit passt zum Zielmarkt

## 7. Einplanen via Velocity
1. Plan + alle Texte dem Nutzer als Tabelle zeigen.
2. Erst nach „ok/freigeben“ über Velocity planen. Nie ohne Freigabe veröffentlichen.
3. Danach Kalender in Velocity prüfen und Liste (Kanal, Datum, Uhrzeit, Status) ausgeben.

## 8. Auswerten (wöchentlich)
- Velocity-Analytics: Views, Watch time, Saves, Shares pro Post
- Top-Post → Variante für anderen Kanal / anderes Land
- Neue Hörerzahlen → Tabelle in `wuha-brand` aktualisieren
