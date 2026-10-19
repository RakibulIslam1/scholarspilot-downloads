# ScholarsPilot Android pilot

**[Download the Android APK](https://github.com/RakibulIslam1/scholarspilot-downloads/releases/download/pilot-1.0.0-5/ScholarsPilot-Pilot-Android-v5.apk)**

Version 1.0.0 (5), ARM64 Android 7+, approximately 44 MB.

![Scan to download the signed Android APK](install-qr.png)

This is a **pilot acceptance release**, not a completed general student launch.
Code 5 was installed over the previous app on a Pixel 6a / Android 16; SMS grants
were retained, and widget settings/placement were checked. Real bank SMS formats,
voice/background, recovery, guardian-device and final policy review remain.

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

## New in code 5

- **Monthly plan:** Home → Set my monthly plan. Two short steps cover whole-month
  tuition/education, housing, living and other costs, a protected cushion and income
  still expected. Current account money is included automatically. A daily remaining
  allowance protects unpaid tuition/housing and does not spend future income early.
  New records recalculate costs and shortfalls. Saving requests AI suggestions;
  free-limit failures have an explicitly labelled calculated fallback.
- **Android widget:** Settings → Home-screen widget. Select balance, today's
  expenses, today's remaining allowance, or any combination; add it to the home
  screen. Each widget has its own choices and ScholarsPilot colors. It displays
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

SHA-256: `97b08ba5345ace6b8f904091ad3137a1e2aaa5e0272a30814585bf995f4b0a94`

The source repository is private. This repository distributes signed binaries,
checksums and release notes. Publisher: **Rakibul Islam**.
Support: **rakibul.rir06@gmail.com**.
[Privacy](https://scholarspilot-rir06.onrender.com/privacy) ·
[Support](https://scholarspilot-rir06.onrender.com/support) ·
[Delete account](https://scholarspilot-rir06.onrender.com/delete-account)

Policy resources remain drafts pending release review. Do not send passwords,
PINs, OTPs, account numbers or raw bank messages in support requests.
