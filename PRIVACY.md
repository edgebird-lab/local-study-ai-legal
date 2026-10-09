# Privacy policy – Local Study AI (Android)

Date: 2026-10-08 · Deutsche Fassung: [DATENSCHUTZ](DATENSCHUTZ)

**Provider and controller:** edgebird-lab (Robin Olbricht – Olbricht Digital) · **Contact:** kontakt@olbricht-digital.de

**In short:** The app processes everything on your device. There is no account, no server run by the provider, no tracking and no advertising. Your documents, questions and cards do not leave the device unless you share, save or report them yourself (see below).

## What data does the app process?

The app stores data only locally in its private storage: imported documents together with their original (PDF, image, text file; for photos and scans a PDF of the pages) and their text sections, your subjects and chapters and the order of your sources, search data computed from them (embeddings), summaries with their settings and your own templates, chat histories (several chats per subject), flashcards with learning state, results of quizzes and Q&A sessions (per topic) and the focus sessions of the timer. The AI (language model and embedding model), text recognition for photos (Tesseract) and speech output run entirely on the device.

## Network access

The app needs the "Internet" permission solely to download the AI models from GitHub (repository `edgebird-lab/lernsystem-modelle`) on first start and for updates, and to fetch the model list (`manifest.json`). No content from the app is transmitted. Like any web server, GitHub technically sees your IP address and the time of the request; GitHub's privacy policy applies to that.

## Disclosure

No personal data is passed on to the provider or to third parties. No analytics, crash-reporting or advertising SDKs are included. Data leaves the device only when you trigger it:

- **Share, print, save, open in another app:** the app or printer you choose receives the file or text. Their terms apply.
- **Exchange file for friends:** If you “share with friends” a subject or a summary, the app creates a file (`.lsai`) with the content you chose (never chats or learning progress) and opens your device's share menu; where it goes (Quick Share, Bluetooth, messenger …) is up to you. Received files are only added after you confirm and as a new copy. The app itself does not connect to the internet for this.
- **Feedback and reporting AI content:** the app opens an email draft to kontakt@olbricht-digital.de (with app version, device model and Android version and, for a report, the reported text). Nothing is sent until you tap "Send" in your email app; you can review and change everything beforehand. We use the email only to handle your request and delete it once we no longer need it.

## AI content

Answers, summaries, quiz questions and Q&A are produced by a language model on your device. They can be wrong or contain inappropriate content. The app bases answers on your sources and names the passage; check important statements there. You can send inappropriate or wrong content to the provider with "Report" (chat, Q&A, summary).

## Permissions

- Notifications: progress of import and download, focus timer reminders and the optional daily study reminder.
- Microphone (optional): for voice input. Recognition uses the device's speech recognition **on the device**; the app records nothing and sends nothing. If the language pack is missing, Android may download it once.
- Photos: to take pictures the app opens the device's camera app (no camera permission needed). The photo and the recognised text are saved as a source; the temporary images are deleted afterwards.
- Share: you can share PDFs, texts and images from other apps with Local Study AI; they are imported only after you choose a subject.
- Reading aloud: the app uses your device's speech output and picks only **offline voices** (voices that need an internet connection are never used). If an offline voice for the language is missing, the app points you to your device's settings where you can download it. Reading aloud and creating audio files run on the device.
- Exact alarms (optional): so that the end of a focus phase is announced on time.
- Start after reboot: restores a running focus timer.
- Foreground service (data synchronisation): keeps import, indexing, summaries and downloads running while the display is off.

## Your rights

In the app under *Menu → Privacy* you can **export** all your data as JSON (data portability) and **delete** it completely (right to erasure). Uninstalling the app also removes all data. The app is excluded from Android backup (`allowBackup=false`) so that no content ends up in cloud backups. Since the provider stores no data about you, there is nothing to give information about there; for access, correction or deletion of emails you sent us, write to kontakt@olbricht-digital.de. You have the right to complain to a data protection supervisory authority.

## Copyright and licences

The app is protected by copyright (© 2026 edgebird-lab, all rights reserved). It contains third-party components under permissive licences; their notices are in the app under *Menu → About the app and licence*.

## Changes

We update this policy when the app changes. The current version is at https://edgebird-lab.github.io/local-study-ai-legal/ and in the app.

## Contact

edgebird-lab (Robin Olbricht – Olbricht Digital), kontakt@olbricht-digital.de
