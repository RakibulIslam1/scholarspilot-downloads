# ScholarsPilot Android pilot

**[Download the Android APK](https://github.com/RakibulIslam1/scholarspilot-downloads/releases/download/pilot-1.0.0-7/ScholarsPilot-Pilot-Android-v7.apk)**

Version 1.0.0 (7), ARM64 Android 7+, approximately 44 MB.

![Scan to download the signed Android APK](install-qr.png)

This is a **pilot acceptance release**, not a completed general student launch.
Code 7 was installed over the previous app on Pixel 6a / Android 16; SMS grants
were retained. Default No, Yes/No account-digit field switching, a real wallet
rescan without account digits, and compact-widget retention passed. Earlier
real-inbox recovery, stated-balance capture, duplicate protection
and compact widget placement/editing passed on that phone. Code 5 pictures remain
historical. More bank formats, voice/background, recovery, guardian-device and
final policy acceptance remain before broad release.

## Install or update

1. Open the download on your Android phone and open the APK from Downloads.
2. If Android asks, allow installation from the browser/Files app you used.
3. For an upgrade, tap Update/Install over the existing ScholarsPilot app. Do not
   uninstall. The signing identity is retained to preserve records and sessions.
4. Open the app. Its HTTPS service is configured; no PC server is required. Free
   hosting can take about a minute to wake up.
5. Sign up with your email and student details. Verify the mailbox before entering
   the workspace. First audience: Bangladesh, age 13+; under 18 needs approval from
   a separate verified guardian account. Follow the optional three-step guide or
   go directly Home.

## Current fixes

- Account numbers are **optional**. Bank messages now offers **No · one wallet or
  account, no number needed** (the default) and **Yes · match my account’s last 3
  digits**. A single bKash wallet needs no account digits. Other people's account
  or phone numbers in received-money alerts are not your wallet identifier.
- A sole numbered account can switch back to no-number matching without deleting
  records or changing its balance. Accounts sharing a sender must retain distinct
  identifiers to keep their balances separate.

- Bank messages now has **Rescan this month** to recover earlier SMS after a
  skipped/empty import, without duplicate records or old-purpose prompts. Read
  the checked/recorded/duplicate/review/excluded counts afterward.
- Tick several sender names and save them together. Previously saved sender
  rules are retained. Common carrier names are hidden by default, with a
  show-hidden option; wallet names and unknown short codes remain visible.
- The widget defaults to a compact white **3 × 1** panel with dark text and an
  inline Edit action. Remove/re-add an older tall widget for the new dimensions.
  Android must confirm placement; the app now displays added/configured counts.

Code 7 passed 171 local tests, 17 hosted SMS/recovery checks and signed Android
package verification. On Pixel 6a / Android 16, the No/Yes controls and a real
wallet rescan without account digits passed. The rescan created no duplicates;
the prior recorded balance and compact widget were retained. Version 6's earlier
current-month recovery and one/all widget selection checks remain historical
evidence. Explicit zero fees are supported; positive/unclear fees need review.
Install code 7 for the new optional account-number controls.

## Included features

- **Monthly plan:** Home → Set my monthly plan. Two short steps cover whole-month
  tuition/education, housing, living and other costs, a protected cushion and income
  still expected. Current account money is included automatically. A daily remaining
  allowance protects unpaid tuition/housing and does not spend future income early.
  New records recalculate costs and shortfalls. Saving requests AI suggestions;
  free-limit failures have an explicitly labelled calculated fallback.
- **Android widget:** Settings → Home-screen widget. Select balance, today's
  expenses, today's remaining allowance, or any combination; add it to the home
  screen. Each widget has its own choices and a simple white appearance. It displays
  the last app sync and requests refresh after new alerts/new days/session expiry.
- **Shared SMS inboxes:** give accounts using the same sender different last-three-
  digit account identifiers. Only account-labelled matches route automatically.
  Missing/ambiguous identifiers need review, and equal endings cannot distinguish
  two accounts. Existing mixed records are not silently reassigned.
- **Assistant without money:** ask student money-management questions even with no
  balance or accounts. Explicit spending-history questions still use stored totals.
  Real zero-account conversation and monthly-plan advice passed hosted checks.

## Records and privacy

Settings → Bank messages asks for SMS access, lists sender identifiers on-device,
and lets you select a bank/wallet sender. Confirm this month's history/latest
explicit balance once. Clear new alerts create records on app sync and ask for a
voice/text purpose; old imported history does not ask for every description.
AI can tidy descriptions and suggest categories. Detected OTP/security messages
are excluded. Selected raw financial SMS reaches the server for deterministic
parsing but is not stored there or sent to the model. Android may restrict SMS
permissions on sideloaded apps; device/distribution permission acceptance remains.

SMS-derived balances can be incomplete, delayed or forged. They are not live
bank verification. Cash, manual payments, CSV history, budgets, original-currency
records and preferred-currency reporting remain available. No bank password,
payment execution or mobile-wallet API connection is added.

The widget exposes selected figures on your home screen. Its encrypted local
snapshot has no token or SMS body; it refreshes from app syncs, not a direct bank
connection. APK updates require Android confirmation; Settings → App updates
opens official releases. No silent automatic installation is performed.

AI uses free Groq access within provider/app limits. The current app cap is
20 shared model runs per UTC day and 30 per student; the shared cap is reached
first. Description/planning calls also consume it. Recording and calculations
continue when AI is unavailable. No student payment is required to ask questions.

SHA-256: `83a2284fe1634b3ac51a8783856ba807e9374e45207dc08925f1b2e4fb39117c`

The source repository is private. This repository distributes signed binaries,
checksums and release notes. Publisher: **Rakibul Islam**.
Support: **rakibul.rir06@gmail.com**.
[Privacy](https://scholarspilot-rir06.onrender.com/privacy) ·
[Support](https://scholarspilot-rir06.onrender.com/support) ·
[Delete account](https://scholarspilot-rir06.onrender.com/delete-account)

Policy resources remain drafts pending release review. Do not send passwords,
PINs, OTPs, account numbers or raw bank messages in support requests.
