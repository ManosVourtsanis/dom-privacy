# DOM Quiz — Privacy Policy

**Last updated: 22 November 2026**

DOM Quiz is a quiz game. This page describes exactly what the app stores, where it is
stored, and how to have it deleted. It is written against what the code actually does,
not against what a template assumes.

## Who is responsible

DOM Quiz is an independent app made by one developer. For any question about your data,
or to ask for it to be deleted or exported, write to the contact address at the bottom
of this page.

## What the app stores about you

An account is a **username and a password**. Nothing more is required.

| What | Why | When |
|---|---|---|
| Username | So other players can see who they are playing | Always |
| Email address | **Optional.** Only so a forgotten password can be reset | Only if you choose to give one |
| Password | To sign you in. Stored only as a hash, by Supabase Auth; never in readable form | Always |
| Quiz results (topic, subcategory, language, questions answered, correct answers, date) | Your statistics screen | Each time you finish a quiz |
| Match records (opponent, chosen topics, score, answer times) | Online matches and their results | Each online match |
| Presence (whether you are idle, searching or in a match, and when you were last seen) | Matchmaking, and ending matches that were abandoned | While you use online mode |
| Reports about a question | So broken questions can be corrected | Only when you report one |

If you continue as a guest, an anonymous account is created with the nickname you choose.
It has **no email address** and is not linked to your identity in any way. If you later
turn it into a full account, it keeps the same records.

## What the app does not do

- **No advertising, and no advertising identifiers.**
- **No analytics or tracking SDKs.** Nothing profiles you or follows you between apps.
- **No location, contacts, photos, microphone or camera.** The app never asks for them.
- **Nothing is sold or shared** with anyone for marketing.

## Crash reports

When the app hits an unexpected error it sends a crash report to Sentry so the bug can
be fixed. These reports are configured not to carry personal information: the option
that would attach user details is switched off, and the app's own log messages are
deliberately excluded from them, because those can mention a username. A report contains
the error, where in the code it happened, and the device model and operating system
version.

## Where your data is stored

- **Database and accounts:** Supabase, in the EU (Frankfurt, `eu-central-1`).
- **Crash reports:** Sentry, in the EU (Germany).

Both are data processors acting on instructions from DOM Quiz.

## How long it is kept

Your account and its records are kept until you delete them. Presence and matchmaking
rows are short-lived and cleaned up automatically within minutes. Crash reports are kept
for 90 days by Sentry's default retention.

## Deleting your account

Open the app, go to **Profile → Edit Profile → Delete account**, and type your username
to confirm.

This removes your profile, your statistics, your match history, your presence and your
password, immediately and permanently. Reports you filed about broken questions are
kept, because the question is still broken, but the record of who filed them is erased.

Deleting cannot be undone, and an online match in progress ends when the account goes.

## Your rights

If you are in the EU or the UK, you have the right to access your data, correct it, have
it deleted, and object to how it is handled. Deletion is built into the app, as described
above. For anything else, write to the contact address below and you will get an answer
within 30 days.

## Children

DOM Quiz is not directed at children under 13 and does not knowingly collect anything
from them. If you believe a child has made an account, write to the address below and it
will be removed.

## Changes to this policy

If this policy changes, the date at the top changes with it. A change that materially
affects how your data is handled will be announced in the app.

## Contact

Write to **manosvourtsanis7@gmail.com** with any question about your data, to ask for a copy of it, or to have it deleted.
