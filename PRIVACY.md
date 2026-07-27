# Chronicle — Privacy Policy

**Last updated: 27 July 2026**

**ChronicleAI** ("we", "us") makes Chronicle, available as a macOS application
and as a browser extension for Chrome, Edge and Firefox. This policy covers
both, and says which is which wherever they differ. It explains what happens to
your data. It is written to be read, not to be impenetrable.

---

## The short version

- Your conversations are stored **on your own machine**, not on our servers.
- The **text** of your conversations is sent to **xAI** to generate replies and
  speech. That is how the app works.
- We hold almost nothing: a licence key, an anonymous install ID, and a monthly
  character counter.
- The extension can read the page you are on, but **only if you switch that on** —
  it is off by default.
- We do not sell your data. We do not run ads. We do not build a profile of you.

---

## What stays on your machine

Stored locally, never transmitted to us:

- **Your conversations.** In the Mac app, as plain JSON in
  `~/Library/Application Support/Chronicle/`. In the extension, in the
  browser's own extension storage, which is sandboxed to Chronicle — ordinary
  web pages cannot read it. Delete them any time from Settings ▸ Data.
- **Your licence key.** In the Mac app, in your macOS login Keychain. In the
  extension, in that same sandboxed extension storage.
- **Your preferences**, alongside the above.

## What is sent to xAI

To answer you at all, Chronicle sends to xAI's API:

- The text of your question and the recent conversation for context
- Chronicle's system instructions
- For spoken replies, the text to be read aloud, along with your chosen voice
  and language

xAI processes this on their servers and returns the reply or audio. Their
handling of it is governed by **xAI's privacy policy and terms**, which we do not
control. If you would rather your text not go to xAI, do not use Chronicle.

**Do not enter information you would not want processed by a third-party AI
service.** Treat it as you would any online service: not the place for
passwords, financial details, medical records or anyone else's private
information.

## What passes through our relay

If you use a licence key, requests travel through our server on the way to xAI.
It holds:

- **Your licence key**, and which plan it belongs to
- **An anonymous install identifier** — a random ID created on first launch, used
  only to count how many machines a licence is active on. It is not derived from
  your hardware, your name, or anything about you.
- **A monthly character count** per licence, for fair-use limits
- **The email address** you used at checkout, supplied by Stripe

We do **not** store the content of your conversations. Requests are forwarded and
not retained.

If you use your own xAI API key instead, nothing touches our servers at all.

## Payments

Payments are handled by **Stripe**. We never see or store your card details.
Stripe provides us with your email address and whether the payment succeeded.
Stripe's own privacy policy governs what they hold.

## Microphone and speech

If you use dictation or voice mode:

- **In the Mac app**, audio is transcribed by **Apple's speech recognition**, on
  your device where your Mac supports it.
- **In the browser extension**, audio is transcribed by your **browser's** speech
  recognition. In Chrome and Edge this means **audio is sent to Google's servers**
  for transcription, under Google's terms, not ours. Firefox does not support
  speech recognition at all, so dictation is unavailable there.
- We never receive your audio in either case, and no recording is stored by us.
- Only the resulting text follows the normal path described above.

Microphone access is only active while you are dictating.

If you would rather no audio leave your machine, use the Mac app, or type
instead of dictating.

## Reading the page you are on (browser extension only)

The extension can read the page you are currently viewing, so you can ask about
an article without pasting it.

- **This is off by default.** You must turn it on in Settings ▸ Data.
- Your browser asks for permission the first time you enable it. Turning the
  setting back off revokes that permission.
- Page text is read **only at the moment you send a message** — never in the
  background, and never while the setting is off.
- What is read is the visible text of that one page, truncated to 12,000
  characters. It goes to xAI along with your question so the reply can address
  it.
- **We do not store page content**, and we do not record which pages you visit.
  There is no browsing history on our side to keep.

Because page text is sent to xAI, do not use this feature on pages containing
information you would not want processed by a third-party AI service — banking
pages, medical portals, private documents, or anyone else's personal data.

## What we do not do

- We do not sell or rent your data
- We do not show advertising
- We do not track your usage for analytics or marketing
- We do not use your conversations to train anything

## How long we keep things

- Licence records: while your licence is active, plus 12 months
- Usage counters: about 70 days, then deleted automatically
- Conversations: on your own machine, for as long as you keep them

## Your rights

Depending on where you live, you may have the right to access, correct, export
or delete the personal data we hold, or to object to its processing. Since what
we hold is limited to a licence key, an install ID, a counter and an email
address, most requests are quick. Email **spufarobud@gmail.com** and we will
respond within 30 days.

To delete everything on your side: Settings ▸ Data ▸ Delete All Inquiries, then
remove Chronicle. To have your licence record deleted, email us — note this
deactivates the licence.

## Children

Chronicle is not intended for anyone under 13, and we do not knowingly collect
data from children.

## Changes

We will post material changes here and update the date at the top. If the change
is significant, we will email licence holders.

## Contact

**ChronicleAI**
spufarobud@gmail.com
