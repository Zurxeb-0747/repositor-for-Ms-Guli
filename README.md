# Sakinah
A static, mobile-friendly tasbeeh with Arabic recitations, Uzbek and English meanings, daily device-local progress, counters, personal goals, and source references. No accounts, analytics, backend, or external assets.

## Run locally
From this checkout: `python3 -m http.server 8000 --bind 127.0.0.1`.
Open the server with your local browser. No dependency installation or build is required.

## Publish with GitHub Pages
Push these files to `main`. In the repository's Settings → Pages, set Source to **GitHub Actions**. The included workflow publishes only the three site files. When deployment succeeds, GitHub displays the public URL. For this repository the expected URL is `https://zurxeb-0747.github.io/repositor-for-Ms-Guli/`; it is not live until deployment succeeds. Public access to source/API may require environment network permission. Publishing a private repository via Pages depends on the account's plan.

## Religious content
This is a small curated collection, not an exhaustive scholarly review. References point to Qur'an passages and Sahih al-Bukhari/Muslim. Uzbek and English text are meaning summaries, not named published translations. Hadith references and the cited Qur’an passages were checked against Sunnah.com and Quran.com during development. This is not a scholar-reviewed translation or collection.
Prescribed daily counts and personal goals are visibly distinguished. Personal goals are adjustable and never imply special religious merit. No guaranteed wealth, fertility, or other worldly outcome is claimed. Counts of 4,444 Salat Nariya and 1,001 Al-Ikhlas are not presented as established Sunnah.

Progress is stored in localStorage per browser/origin and resets at the local calendar date; it does not sync across devices. Clearing browser storage removes progress. No secret is needed to run the site.

## Marriage & family additions
The family category includes Qur’an 25:74, the existing prayer for children (3:38), and a personal Yasin reading goal. All 83 Arabic verses of Yasin were retrieved from Quran.com, with consecutive verse numbers verified. The reader links to Muhammad Sodiq Muhammad Yusuf’s Uzbek meaning (translation 55, verified on Quran.com). One Yasin count means one completed reading. No special marriage benefit, guaranteed outcome, or superiority for marriage is claimed.

## Combined bedtime tasbeeh
The single 100-recitation plan follows Sahih al-Bukhari 5361: 33 Subhanallah, 33 Alhamdulillah, then 34 Allahu akbar at bedtime. The counter displays each stage, switches automatically, preserves progress, and stops at 100. Undo crosses stage boundaries correctly. Counts are fixed for this plan; resetting starts a new complete sequence.

## Optional personal practices
Includes separate 40- and 80-repeat istighfar plans and a 4,444-repeat Salatun Nariya plan. The formula of Nariya and its interpretation are disputed; neither its wording nor 4,444 is attributed to an authentic prophetic prescription. Qur’an 33:56 is linked only for salawat generally. Evidence notices appear on cards and before the counter. Yasin is labeled as a personal reading plan while hoping to marry, without a claimed authentic special marriage benefit. No worldly outcome is guaranteed.
