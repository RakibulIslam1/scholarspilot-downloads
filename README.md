<div align="center">
  <img src="assets/app-icon.png" width="76" alt="ScholarsPilot app icon" />
  <h1>ScholarsPilot</h1>
  <p><strong>Student money, made understandable.</strong></p>
  <p>An Android money companion for clearer spending, purposeful records and a practical monthly plan.</p>
  <p>
    <a href="https://github.com/RakibulIslam1/scholarspilot-downloads/releases/download/pilot-1.0.0-9/ScholarsPilot-Pilot-Android-v9.apk"><img alt="Download Android pilot 1.0.0 · build 9" src="https://img.shields.io/badge/Download_Android-1.0.0_%C2%B7_build_9-EA1E63?style=for-the-badge&amp;logo=android&amp;logoColor=white" /></a>
    <a href="docs/ScholarsPilot_Public_Report.pdf"><img alt="Read the product case study" src="https://img.shields.io/badge/Read_the_Case_Study-PDF-5991FD?style=for-the-badge" /></a>
  </p>
</div>

![ScholarsPilot: record your money, understand your spending, plan your month. Actual app screens with private values hidden.](assets/portfolio-cover.png)

## A balance is only the beginning

Tuition, rent, everyday purchases and an expected allowance all compete for a student's money. The useful question is: **what can I spend today while protecting what matters this month?**

ScholarsPilot brings selected financial messages, reviewed wallet alerts and personal entries into one native Android experience. Students add the reason behind a payment, see where their money goes and plan around education and living costs. Bank login credentials are not required for this recording workflow.

**Built by [Rakibul Islam](https://github.com/RakibulIslam1)** · Android pilot · Bangladesh first

## Capture → understand → review → plan

| Capture useful evidence | Make records meaningful | Plan the month |
|---|---|---|
| Choose supported financial SMS senders, review wallet alerts or enter spending yourself. | Speak or type a reason. AI improves the wording and suggests a category for you to review. | Protect tuition, housing and a cushion before calculating everyday spending room. |

### Designed around the student's day

- **Four clear destinations:** Home, Money, Assistant and Settings.
- **A practical monthly plan:** education, housing, living costs, other spending and expected income stay understandable.
- **Less repetitive recording:** supported SMS capture, multiple senders, current-month import and duplicate handling.
- **Your voice, your reason:** Bangla and English speech entry, remembered speech choice and editable AI wording.
- **Your preferred currency:** keep original transaction amounts while viewing dated reference conversions for reporting.
- **A small home-screen companion:** choose balance, today's spending, daily allowance or a combination.
- **Student-focused assistance:** ask money-management questions, explore hypothetical budgets and understand recorded spending—even with no account balance.

## Inside the app

These are actual Pixel 6a / Android 16 captures. Personal financial values are hidden; the description example was left unsaved.

| Home | Monthly plan | AI description review |
|:---:|:---:|:---:|
| <img src="assets/screens/home.png" width="230" alt="Home: daily allowance, account summary and recent activity" /> | <img src="assets/screens/monthly-plan.png" width="230" alt="Monthly plan protecting essentials and separating expected income" /> | <img src="assets/screens/ai-review.png" width="230" alt="Unsaved demonstration entry with AI-prepared wording and category" /> |

| Budgets | Android widget settings | Money assistant |
|:---:|:---:|:---:|
| <img src="assets/screens/budgets.png" width="230" alt="Money tab with category budgets and reporting tools" /> | <img src="assets/screens/widget.png" width="230" alt="Choose what the compact money widget displays" /> | <img src="assets/screens/assistant.png" width="230" alt="Student-focused money-management guidance" /> |

[Explore the screen gallery](docs/Screen_Gallery.md) · [Read the public report](docs/ScholarsPilot_Public_Report.md) · [Download the PDF](docs/ScholarsPilot_Public_Report.pdf)

## The engineering behind the experience

![ScholarsPilot component architecture](assets/architecture.png)

| Layer | Implementation |
|---|---|
| Native application | Expo, React Native and Expo Router; Kotlin financial-alert and widget integration |
| Authenticated API | Next.js and TypeScript over HTTPS |
| Records and identity | PostgreSQL on Neon, Prisma and Firebase authentication |
| AI assistance | Groq-hosted model for language tasks, bounded tools and request controls |
| Financial calculations | Deterministic minor-unit arithmetic, dated reporting rates and transactional journals |

AI helps explain and organize. Financial calculations and stored amounts are handled by deterministic services. Expected income is kept separate from money already available; AI suggestions remain reviewable.

This public repository contains the product showcase, documentation and release information. Application implementation and server credentials are private; there is no source-code distribution here.

## Try the Android pilot

**[Download the signed APK](https://github.com/RakibulIslam1/scholarspilot-downloads/releases/download/pilot-1.0.0-9/ScholarsPilot-Pilot-Android-v9.apk)** · [Release notes](https://github.com/RakibulIslam1/scholarspilot-downloads/releases/tag/pilot-1.0.0-9) · [Installation guide](docs/Install_Android.md)

| Version | Build | Platform | Last documented verification |
|---|---|---|---|
| 1.0.0 | 9 | Android 7.0+ · ARM64 | 20 October 2026 |

Install the APK on a compatible Android phone. To update an existing installation, choose **Update** over the existing app. A PC server is not needed. Verify your email, complete the applicable consent steps and set up your monthly plan. SMS, microphone and notification access are optional, separate permissions.

**Current scope:** a pilot for students in Bangladesh aged 13+, with guardian approval required under 18. ScholarsPilot records and suggests; it does not hold funds or initiate payments. Some sideloaded phones restrict message permissions. Supported alerts may omit amounts, and records are not a bank-verified live balance. Manual entry remains available. Free hosting can sleep and AI quotas apply.

## Verified work

The 20 October 2026 verification recorded **188 passing automated tests across 28 files**, **eight controlled financial scenarios** and **one complete browser workflow**. The existing v9 APK passed signature and native-packaging checks. These cover defined local financial, authorization and workflow behavior; they do not imply an independent audit or acceptance on every phone.

The controlled tuition scenarios belong to a separate practice prototype with fictional funds. They are not live transfer features in the downloadable Android app. [Verification scope](docs/ScholarsPilot_Public_Report.md#verification-and-release-status)

## Project notes

- [Public product and engineering report](docs/ScholarsPilot_Public_Report.pdf)
- [Version 1.0.0 · build 9](releases/1.0.0-build-9.md)
- [Install and update](docs/Install_Android.md)
- [Privacy and data controls](docs/Privacy_and_Permissions.md)
- [Artifact checksum](releases/SHA256SUMS.txt)

**Next:** broader device/message-format validation, accessibility improvements, stronger operational monitoring and independent privacy/security review.

---

**Rakibul Islam** · [GitHub](https://github.com/RakibulIslam1) · [Support](mailto:rakibul.rir06@gmail.com)  
[Privacy policy](https://scholarspilot-rir06.onrender.com/privacy) · [Account deletion](https://scholarspilot-rir06.onrender.com/delete-account)

© 2026 Rakibul Islam. [Public content and app rights](NOTICE.md).
