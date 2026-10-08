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
