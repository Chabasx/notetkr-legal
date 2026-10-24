# NoteTkr Privacy Policy

Effective date: October 24, 2026

NoteTkr is an iPhone app that records conversations and turns them into transcripts,
summaries and to-dos on your iPhone. It is published by Carlos Mera
("we", "us").
Contact: notetkr01@gmail.com.

## In short

- NoteTkr has no account, no sign-in, no ads, no analytics and no tracking.
- Transcription, summaries, chat, speaker labels and search run on your iPhone. Your
  recordings, notes and chats are never sent to us or to any AI service.
- If iCloud sync is on (it is on by default for new installations), your notes and recordings
  are stored in your own private iCloud account, which we cannot access.
- NoteTkr is free to try: your first 3 notes are free, and the one-time in-app purchase NoteTkr
  Full unlocks unlimited new notes. Apple processes the payment; we never see your card or other
  payment details.
- We receive something only when you choose to send it to us: a support email or a diagnostic
  report.
- We do not sell personal information or share it for targeted advertising, and we do not send
  recordings, transcripts, notes or chats to any third-party AI service. When you download the AI
  models, Hugging Face and the content-delivery services it uses receive technical request
  information such as your IP address. Apple processes purchases and iCloud data under its own
  terms, and our email provider processes what you send to support.

## What stays on your iPhone

NoteTkr keeps the following in its storage on your iPhone:

- your recordings, transcripts, summaries, decisions, to-dos, bookmarks, folders, tags and
  categories, and the notes you write;
- speaker labels and any names you give speakers;
- your chat conversations with your notes;
- the search index of your notes;
- your settings;
- the AI models you download;
- your free-note record and your NoteTkr Full purchase record (see [Purchases and free
  notes](#purchases-and-free-notes)).

These are processed by AI models that run on your iPhone. While a recording is being labeled by
speaker, temporary voice comparison data stays on your iPhone, outside device backups and iCloud
sync. It is deleted when the labels are final, when processing is canceled, or when the audio or
the note is deleted, and otherwise once it is about 24 hours old, the next time NoteTkr runs; if
NoteTkr is not opened, it stays until then. Nobody is identified, and voices are not recognized
or compared across notes.

Chat conversations stay on your iPhone: they are not synced to iCloud and are not part of
exports.

### Device backups

A backup is a copy of what is on this iPhone, taken by iOS; it is separate from iCloud sync. Your
notes and recordings are included in your iPhone's backups (iCloud Backup or a computer),
according to your device settings, and so are the free-note record and the purchase record: an
iPhone restored from a backup keeps its count of free notes. The downloaded AI models, temporary
processing files, sync caches, temporary exports and diagnostic data are excluded from backups.

## iCloud sync

New installations of NoteTkr sync notes and recordings through iCloud by default. An existing
library is uploaded only after you choose to. Sync uses the private database of your own Apple
Account (Apple's CloudKit service). We cannot read, access or delete this data; Apple stores it
under the terms and privacy policy of your Apple Account. If you are not signed in to iCloud,
NoteTkr works only on your iPhone.

You can turn sync off at any time in NoteTkr's **Settings → iCloud & Backup**. There you can also
delete a recording from iCloud (**Delete from iCloud**) or delete your whole NoteTkr library from
iCloud (**Delete Entire iCloud Library**).

Separately from note sync, when you are signed in to iCloud NoteTkr keeps a copy of the free-note
record in iCloud Key-Value storage, a small store in your iCloud account for this app's data, so
your other devices count the same free notes. It holds only the identifiers described under
[Purchases and free notes](#purchases-and-free-notes); turning off note sync does not remove it.

## Purchases and free notes

NoteTkr is a free download. Your first 3 new notes are free in total: recordings, imported audio
files and typed notes count. After that, the one-time in-app purchase NoteTkr Full unlocks
unlimited new notes. Your existing notes stay available either way.

**Payment.** Apple processes the purchase through the App Store under its own terms and privacy
policy. We never receive your card or other payment details, your name or your Apple Account
email. Apple gives us the sales and payment reports it gives every developer.

**What the app receives and keeps.** When you buy or restore NoteTkr Full, or when NoteTkr checks
your purchase, Apple's StoreKit gives the app the transaction information on your iPhone. NoteTkr
keeps only a purchase record on your iPhone: the product, the original transaction identifier,
whether the purchase was made in the App Store or in a test environment, and when NoteTkr last
verified it. It is used only to keep NoteTkr Full unlocked while your iPhone cannot confirm the
purchase with the App Store. To show the price, the unlock screen asks the App Store for the
product and your storefront country; Apple answers that request.

**Free-note record.** To count the 3 free notes, NoteTkr keeps the identifiers of the notes that
used one: the random identifiers NoteTkr gives each note, at most 64 of them, with no titles,
text or audio. This list is stored:

- in NoteTkr's storage on your iPhone;
- in your iPhone's Keychain, for this device only (it does not move to another iPhone), so that
  deleting and reinstalling NoteTkr usually keeps the count;
- when you are signed in to iCloud, in your iCloud Key-Value storage, so your devices share the
  count.

NoteTkr also keeps, in its storage on your iPhone (and so in its backups) but never in iCloud
Key-Value storage, the notes being made right now and at most 64 notes that gave their free note
back (for example a recording without speech, or a note deleted before it counted), each with its
kind (recording, import or typed note) and a time.

None of it is sent to us, and we cannot read it. Deleting notes does not reset your free notes.
**Restore Purchases**, on the unlock screen and in **Settings → About**, asks the App Store to
sync your purchases; NoteTkr does that only when you tap it.

## Downloading the AI models

NoteTkr's AI models are downloaded once, only after you choose **Download now** (or later from
the setup card or Settings). They come from Hugging Face (huggingface.co) over HTTPS, without
cookies or any account, and a download may be served through the content-delivery services
Hugging Face uses. Like any website, Hugging Face and those services receive your IP address and
standard request information (such as the time and the file requested) and handle them under
Hugging Face's privacy policy (https://huggingface.co/privacy). No recording, note or other
content of yours is sent. Each downloaded file is checked against a fingerprint built into the
app.

## Sharing and exporting

NoteTkr shares or exports something only when you choose to: sharing a note as text, Markdown,
audio or subtitles, exporting a library archive, or sharing a diagnostic report. You choose where
it goes, and the receiving app or person handles it under their own terms.

## Diagnostic reports

To help find problems without seeing your content, NoteTkr keeps a small diagnostic log on your
iPhone:

- **App events:** what started, finished or failed and when, with durations, counts, error codes
  (fixed words and numbers that name a failure) and a scrambled form of a note's identifier that
  cannot be turned back into the note. Free-note and purchase events (a free note used, a
  purchase or restore that failed) are recorded the same way, as counts and fixed codes, never
  with a price or a transaction identifier. There is no field for text: no titles, transcripts,
  chat text, speaker names or file names.
- **Crash and hang reports** that iOS provides to apps (through Apple's MetricKit), with any
  free-text messages removed.

This data stays on your iPhone, uses at most about 1.5 MB, is excluded from backups and is never
sent automatically. You can delete it at any time with **Clear diagnostic data**.

When you open **Share diagnostic report** in Settings, or **Report this problem** on a note whose
processing failed, NoteTkr builds a report and shows you exactly what it contains before you
share it. A report contains: the app version and build, the iOS version, the iPhone model, its
memory, whether it supports on-device AI, the iCloud sync status, the app events, the crash and
hang reports, a random report ID, and for a failed note its processing state, error code,
recording length, number of audio parts and transcript lines, and language. It does not contain
your notes, transcripts, audio or chat text.

For a failed note you can turn on **Also attach this note's transcript**. It is off by default,
and the app warns you that the transcript may contain personal information about you and others.
The transcript is included only if you turn it on and then share the report.

If you send a report or an email to us, we receive it together with your email address and
anything you write. We use it only to answer you and to fix problems in NoteTkr, keep it for
12 months, and delete it sooner if you ask, unless the law requires us to keep it. Email
to us is handled by Google LLC (Gmail), United States.

## Permissions

- **Microphone:** used only while you record, after you tap Start. You can change this in
  iOS Settings at any time.
- **Notifications:** NoteTkr asks when your first recording starts, and uses them only to tell
  you when a recording needs attention (for example after an interruption).
- **Live Activity:** while you record, the Lock Screen and Dynamic Island show the recording
  status and timer.

## Deleting your data

- Delete a note: it moves to **Recently Deleted** for 30 days, then it is deleted. You can also
  delete it permanently there right away.
- **Delete from iCloud** removes a recording's iCloud copy; **Delete Entire iCloud Library**
  (Settings → iCloud & Backup) removes your NoteTkr library from iCloud.
- **Delete all chats** removes your chat conversations from your iPhone.
- Turning off the Gemma agreement in Settings turns off search by meaning and removes that model.
- **Clear diagnostic data** deletes the diagnostic log and crash reports.
- Deleting NoteTkr removes its files from your iPhone. Data in your iCloud account stays until
  you delete it from NoteTkr or in iOS Settings (your name → iCloud → Manage Storage).
- Two copies of the free-note record can stay after you delete NoteTkr: the one in your iPhone's
  Keychain and, if you used iCloud, the one in your iCloud Key-Value storage. They hold only note
  identifiers, and they are what keeps the free-note count when NoteTkr is reinstalled, so
  NoteTkr has no control that deletes them.
- A NoteTkr Full purchase stays with your Apple Account; deleting the app does not cancel it,
  and **Restore Purchases** brings it back. For refunds, use Apple's Report a Problem
  (reportaproblem.apple.com).
- To delete a report or email you sent us, write to notetkr01@gmail.com.
- Deleting something in NoteTkr does not remove copies that already exist elsewhere: in an older
  device backup, in an export you made, or with a person or app you shared it with.

## Children

NoteTkr is intended for people aged 13 and older. Between 13 and 17 you must have permission from
a parent or legal guardian, who reviews and agrees to the End User License Agreement on your
behalf. NoteTkr is not directed at children under 13, and we do not knowingly receive personal
information from them. If we learn that a child under 13 has sent us a report or an email, we
delete it, subject to any legal requirement to keep it; if you believe that has happened, contact
us.

## Your rights

Because your notes, recordings and chats stay on your iPhone and in your own iCloud account, and
Apple, not us, processes purchases, we hold no personal information about you unless you send us
a report or an email. Depending on
where you live (for example under the GDPR or US state privacy laws), you may ask us to access,
correct, delete or stop using what you sent us, and you may complain to your data protection
authority. Write to notetkr01@gmail.com; we answer within 30 days.

If you are in the European Economic Area, the United Kingdom or Switzerland: the only personal
data we process is what you send us in a report or an email. We process it to answer you and to
fix problems in NoteTkr, on the basis of our legitimate interest in supporting the app and, where
you ask us for something, of taking the steps you requested. Its only recipient is our email
provider, Google LLC (Gmail), United States; it may be stored and processed outside your country under
that provider's safeguards for international transfers. You have the rights of access,
rectification, erasure, restriction, portability and objection, and the right to complain to
your supervisory authority.

## Changes

If this policy changes, we update the effective date above and describe significant changes in
the app's release notes.

## Contact

Carlos Mera. Email: notetkr01@gmail.com. Support: https://github.com/Chabasx/notetkr-legal/blob/main/support.md.
