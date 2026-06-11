# Privacy Policy — Lostria Sewing

**Effective date:** 2026-05-25
**Last updated:** 2026-06-11

## Who we are

Lostria Sewing is a mobile application for managing sewing patterns, developed by Gabriela Dvorská.
Contact: lostria.apps@gmail.com

## What data the app handles

All your data — patterns, magazines, sewing logs, photos, hashtags, categories, locations, and notes — is stored **locally on your device only**. We do not operate any backend server, do not collect telemetry, and do not maintain user accounts.

## When data leaves your device

The app sends data to third-party services only in these specific cases, all initiated by your explicit action:

### AI extraction and translation

When you tap "AI Import" on a magazine page, "AI Fill from photo" on a pattern, share a URL into the app, or use the "Translate" button on a pattern detail, the relevant text and/or image is sent to one of the following services for processing:

- **Google Gemini API** — default provider for AI extraction and translation. The standard paid API (which Lostria uses by default) does **not** retain your data for model training.
- **Groq API (Meta Llama)** — alternative provider, used only if you configure your own Groq API key in Settings. Per Groq's privacy policy, data sent via their free tier **may be used by Groq to improve their services**. If you prefer not to share data this way, use the default Gemini provider or skip AI features.

Communication is always encrypted (HTTPS). Lostria itself does not retain the data after the API call returns.

- Google Gemini privacy: https://ai.google.dev/gemini-api/terms
- Groq privacy: https://groq.com/privacy-policy/

### Web page fetching (Share import)

When you share a URL into the app, the app fetches the HTML content of that page over HTTPS so it can pass the text to the AI for extraction. The page owner's server may log this request (your IP address, user agent, etc.) as it would for any visit from a web browser.

### Google Play in-app purchase

When you purchase the premium unlock, Google Play Billing processes the transaction. We do not see or store payment details — only the resulting "premium" status (a boolean flag) is saved locally on your device.

## Crash reports (opt-in)

To help us fix bugs, the app can send anonymous crash reports via **Firebase Crashlytics** (Google). **Automatic sending is off.** If the app crashes, on the next launch it asks whether you want to send the report — nothing is sent without your consent, and declining deletes the report from your device. Reports contain only technical data (stack trace, app version, device model, OS version) — **no patterns, photos, or personal data.** This data is processed by Google.

- Firebase/Crashlytics privacy: https://firebase.google.com/support/privacy

## What we DO NOT do

- We do **not** collect analytics or usage statistics.
- We do **not** send crash reports without your explicit consent (see above).
- We do **not** show advertisements.
- We do **not** require an account or sign-in.
- We do **not** track your location.
- We do **not** access your contacts, calendar, microphone, or other device data beyond what you explicitly grant for photo selection.
- We do **not** automatically back up to any cloud.

## Permissions

The app requests these Android permissions:

- **Photos / Storage** — to let you select existing photos from your phone for patterns, magazines, and sewing logs; and to save / open backup ZIP files you create.
- **Camera** — to take new photos from within the app.
- **Internet** — to call AI APIs and fetch web pages when you trigger an AI feature.

## Backup and data control

You can:

- Export your data as a ZIP backup at any time (Settings → Backup → Export). You choose where to save or share it.
- Import a previously saved ZIP backup.
- Delete individual items (patterns, magazines, logs, photos) at any time within the app.
- Uninstall the app to remove all local data — Android removes all app data on uninstall.

## Data deletion {#data-deletion}

Because Lostria Sewing stores all your data locally on your device and never on our servers, **you control deletion yourself at any time** — no request to us is needed.

### How to delete your data

1. **Delete individual items in the app:**
   - Pattern / magazine / sewing log → open detail → tap the delete icon (red trash)
   - Photo → open the photo → menu → Delete
   - Hashtag / category / target group / location → "Ostatní" tab → list → trash icon

2. **Delete all data at once:**
   - Open Android **Settings** → **Apps** → **Lostria Sewing** → **Storage** → **Clear data**
   - All patterns, magazines, sewing logs, photos, and settings will be deleted permanently
   - The app remains installed (you can start fresh)

3. **Uninstall the app:**
   - Long-press the app icon → **Uninstall**
   - Android removes the app and all its data

### Data sent to AI providers (Gemini / Groq)

When you use AI features, text and/or photos are sent to Google Gemini or Groq for processing. According to their standard paid API terms of service, this data is **not retained for model training** and is not stored long-term on their servers (only temporary processing logs for abuse prevention, typically a few days). There is no per-user account on our side to delete from.

For data retention questions on their side, see:
- https://policies.google.com/privacy
- https://groq.com/privacy-policy/

### Contact

If you need help with data deletion that the above options don't cover, email us at **lostria.apps@gmail.com**.

## Children

The app is intended for users 13 years of age and older. We do not knowingly process data from children under 13.

## Your rights (GDPR, EU users)

Because the app does not maintain any server-side user record, there is no data on our side to access, correct, or delete. You retain full control over your local data and can delete it at any time.

For data sent to Google Gemini or Groq during AI processing, please refer to their respective privacy policies linked above.

## Changes to this policy

If we update this policy, we will update the "Last updated" date above. Continued use of the app constitutes acceptance of the updated policy.

## Contact

Questions, concerns, or requests:

Gabriela Dvorská
Email: lostria.apps@gmail.com

---

# Zásady ochrany osobních údajů — Lostria Sewing

**Datum účinnosti:** 25. 5. 2026
**Aktualizováno:** 11. 6. 2026

## Kdo jsme

Lostria Sewing je mobilní aplikace pro správu šicích střihů. Vývojářka: Gabriela Dvorská.
Kontakt: lostria.apps@gmail.com

## Jaká data aplikace zpracovává

Všechna vaše data — střihy, časopisy, záznamy o ušití, fotky, hashtagy, kategorie, umístění a poznámky — jsou uložena **pouze lokálně ve vašem zařízení**. Neprovozujeme žádný server, nesbíráme telemetrii a nemáme uživatelské účty.

## Kdy data odcházejí ze zařízení

Aplikace posílá data třetím stranám jen v těchto případech a vždy na základě vaší explicitní akce:

### AI extrakce a překlad

Když kliknete „AI Import" na stránce časopisu, „AI doplnit z fotky" u střihu, sdílíte URL do aplikace, nebo použijete tlačítko „Přeložit" v detailu střihu, příslušný text a/nebo obrázek se odešle ke zpracování:

- **Google Gemini API** — výchozí poskytovatel AI extrakce a překladu.
- **Groq API (Meta Llama)** — alternativní poskytovatel, použije se jen pokud si v Nastavení nakonfigurujete vlastní Groq API klíč.

Tyto třetí strany data dočasně zpracují, aby vrátily odpověď. Komunikace je šifrovaná (HTTPS). Při přístupu přes placenou standardní API se data nepoužívají k trénování jejich modelů.

- Privacy Google Gemini: https://ai.google.dev/gemini-api/terms
- Privacy Groq: https://groq.com/privacy-policy/

### Načítání webové stránky (Sdílet odkaz → Import)

Když sdílíte URL do aplikace, aplikace přes HTTPS stáhne obsah stránky, aby ho mohla předat AI k extrakci. Provozovatel té stránky může requesty logovat (IP, user agent), stejně jako jakoukoli návštěvu prohlížečem.

### Google Play nákup uvnitř aplikace

Při zakoupení prémiové verze zpracovává transakci Google Play Billing. Nevidíme ani neukládáme platební údaje — uloží se jen výsledný stav „premium" (boolean) lokálně.

## Hlášení pádů (dobrovolné)

Abychom mohli opravovat chyby, aplikace umí odeslat anonymní hlášení o pádu přes službu **Firebase Crashlytics** (Google). **Automatické odesílání je vypnuté.** Když aplikace spadne, při dalším spuštění se zeptá, jestli hlášení chcete odeslat — bez vašeho souhlasu se nic neodešle a při odmítnutí se hlášení z vašeho zařízení smaže. Hlášení obsahuje jen technická data (stack trace, verzi aplikace, model zařízení a verzi systému) — **žádné střihy, fotky ani osobní údaje.** Tato data zpracovává Google.

- Privacy Firebase/Crashlytics: https://firebase.google.com/support/privacy

## Co NEděláme

- **Nesbíráme** analytics ani statistiky používání.
- **Neodesíláme** hlášení o pádech bez vašeho výslovného souhlasu (viz výše).
- **Nezobrazujeme** reklamy.
- **Nevyžadujeme** účet ani přihlášení.
- **Nesledujeme** vaši polohu.
- **Nečteme** kontakty, kalendář, mikrofon ani jiná data zařízení nad rámec toho, co explicitně povolíte při výběru fotky.
- **Nezálohujeme** automaticky do cloudu.

## Oprávnění

Aplikace požaduje tato Android oprávnění:

- **Fotky / úložiště** — abyste mohli vybírat existující fotky pro střihy, časopisy a záznamy o ušití; a uložit / otevřít ZIP zálohu.
- **Fotoaparát** — pořízení fotky přímo z aplikace.
- **Internet** — volání AI API a stahování webových stránek při AI funkcích.

## Zálohy a kontrola dat

Můžete:

- Kdykoli si exportovat všechna data jako ZIP zálohu (Nastavení → Záloha → Exportovat).
- Importovat dříve uloženou ZIP zálohu.
- Smazat jednotlivé položky (střihy, časopisy, ušití, fotky) kdykoli.
- Odinstalovat aplikaci — Android při odinstalaci smaže všechna data aplikace.

## Děti

Aplikace je určena pro uživatele od 13 let. Vědomě nezpracováváme data dětí mladších 13 let.

## Vaše práva (GDPR, uživatelé v EU)

Protože aplikace neprovozuje žádný server s uživatelskými daty, na naší straně nejsou žádná data k přístupu, opravě ani smazání. Kompletní kontrolu nad lokálními daty máte vy a můžete je kdykoli smazat.

Pro data odeslaná do Google Gemini nebo Groq během AI zpracování viz jejich privacy policy výše.

## Změny zásad

Pokud zásady aktualizujeme, upravíme datum „Aktualizováno" výše. Pokračováním v používání aplikace souhlasíte s aktualizovanými zásadami.

## Kontakt

Otázky, podněty, žádosti:

Gabriela Dvorská
E-mail: lostria.apps@gmail.com
