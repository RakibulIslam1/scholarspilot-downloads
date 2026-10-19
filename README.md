# ScholarsPilot Android pilot

**[Download version 9](https://github.com/RakibulIslam1/scholarspilot-downloads/releases/download/pilot-1.0.0-9/ScholarsPilot-Pilot-Android-v9.apk)**

Version 1.0.0 (9), ARM64 Android 7+. This is a pilot acceptance release.

![Scan to download the signed Android APK](install-qr.png)

## Install or update

Open the APK on your phone and choose Install/Update. Install over the existing
ScholarsPilot app; do not uninstall. The signing identity is unchanged. Its
hosted API is configured, so a PC server is unnecessary. Free hosting can need
about a minute to wake up. APK updates are manual; this pilot does not silently
install new Android versions.

First audience: Bangladesh, age 13+, with verified guardian approval under 18.
Email verification is required before entering the workspace. No fictional money
is added and no bank password or payment PIN is needed.

## What is new

- Bangla and English dictation remembers language and speech-service consent.
  Offline recognition is chosen only for an installed matching language. The
  phone speech service can require internet processing; the app saves no audio.
- One voice button handles dictation. AI prepares the description and category
  automatically. Typed text is prepared on Review; check it before Save. No
  separate AI/tidy switch is needed. Resetting speech consent is available in
  Settings → Account and privacy, away from recording. Saved-entry editing
  changes reviewed wording without changing its amount.
- Settings → bKash app alerts offers separate opt-in notification capture for
  supported official-bKash Cash Out, Send Money and Payment cues. Android
  notification access is required. It cannot read private wallet history.
- If an alert has no amount, enter the actual amount and fee after checking bKash.
  Review the voice/text purpose, category, receiving account and balance choice
  before saving. Missing figures are never invented by AI.
- Cash Out transfers the principal to your cash account and records only the
  actual fee as spending. Both legs and fee commit together. Use History only if
  balances already include the event; Adjust balances is for a new deduction.
- Reminder taps open the review form directly. Unfinished descriptions stay in
  the app. Android 14+ can still allow swiping away ongoing notifications.
- Assistant history excludes unrelated description/monthly tasks. Hypothetical
  budgets use the question's figures rather than replacing them with real
  account balances. Zero-money student guidance remains available.

## Money tracking

Use Home for the monthly plan and daily allowance, Money → Activity for recorded
spending, Assistant for student money questions and Settings for profile and
capture permissions. Manual accounts, manual expenses, reviewed messages and
statement imports do not require live bank access. Preferred currency drives
reporting with dated reference conversions; original currency records remain.

Bank messages supports multiple senders, current-month import with consent,
rescan recovery, carrier-name filtering and automatic clear new SMS records on
sync. A single wallet needs no account digits; shared senders can use distinct
last-three-digit account identifiers. The compact white Android widget can show
balance, today's spending and/or today's calculated allowance.

## Permissions and limitations

An APK cannot guarantee SMS or notification permission on every Android phone.
Some sideloaded installations restrict these permissions. Developer options are
not a normal student setup requirement; use manual entry or reviewed messages
if access is blocked. Notification access does not unlock restricted SMS access.

Android grants broad inbox/notification access. The app filters selected SMS
senders and checks the official bKash package before reading its notification
extras. OTP/security messages and promotions are excluded where recognized.
Encrypted device queues are bounded to 50 cues and seven days. Capture stops on
sign-out/session expiry. Original notification text is not sent to AI/server;
selected financial SMS reaches the server for parsing but raw bodies are not
stored there or sent to AI. Reviewed financial records are stored in your account.

SMS/notification records can be delayed, incomplete or forged. They are not a
verified live balance. Matching source overlaps are held for review, and you
must still check whether a manual/SMS record already exists. Free hosting and
Groq have quotas; calculations and manual records remain usable without AI.
ScholarsPilot records and suggests; it does not hold funds or initiate payments.

Publisher: Rakibul Islam · Support: rakibul.rir06@gmail.com

[Privacy policy](https://scholarspilot-rir06.onrender.com/privacy) ·
[Account deletion](https://scholarspilot-rir06.onrender.com/delete-account)
