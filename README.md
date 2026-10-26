# MedRecall – Medicine & MR Manager

A single-file, offline HTML app (`MedRecall.html`) that helps a doctor remember medicine brands, their compositions, companies, medical representatives (MRs), managers, visit history, and a gifts and honorarium register. It also includes flashcards and quizzes for revision.

## How to open it

**Computer:** download `MedRecall.html` and double-click it. It opens in Chrome, Edge or Firefox.

**Android phone:**
1. Copy `MedRecall.html` to the phone (Downloads folder, Google Drive or WhatsApp-to-self).
2. Open the **Files** app, tap the file and choose **Chrome**.
3. Always open it the same way. Browser data is tied to the file's exact location, so if you move or rename the file, the app starts empty (restore from a backup).
4. More reliable: host the file at a fixed web address (for example GitHub Pages for this repo) and bookmark it or "Add to Home screen" in Chrome.

## Your data (please read)

- Everything is stored **only in this browser on this device** (localStorage). It is **not** synced across devices.
- Clearing browser data, private/incognito mode, uninstalling the browser or losing the device can **destroy your records**.
- Use **Backup & Settings → Download full backup** (JSON) regularly, and keep the file somewhere safe. Use **Restore** to move to another device.

## Bulk import

Medicines, companies, MRs and managers can be imported from CSV. In Excel, use *Save As → CSV UTF-8*, with column headers in the first row (download a template from Backup & Settings). Write combinations as `Telmisartan 40 mg + Amlodipine 5 mg`. Imported compositions are marked **unverified** unless a `verified` column says yes.

## Notes

- Demo records are fictional and marked **DEMO**. Their compositions are illustrative only. Remove them in Backup & Settings.
- Recording an item in the gifts register does not make it permissible. Review each item against the current NMC professional-conduct regulations, UCPMP and company policy.
