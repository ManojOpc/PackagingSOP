# Storage Packaging SOP

A mobile-friendly app for creating **Storage Packaging Standard Operating Procedures (SOPs)** for automotive parts.
It runs in the phone's browser, works offline after the first load, and keeps all data on the device.

**Open the app:** [https://manojshs.github.io/PackagingSOP/](https://manojshs.github.io/PackagingSOP/)

---

## Features

- **Master list** of all SOPs: search, edit, download PDF, duplicate, delete
- **Document history**: created, edited and PDF-downloaded timestamps for each SOP
- **Quick entry**: tap-to-select options, steppers for quantities, last-used names and locations filled in automatically
- **Packaging levels**: Primary, Secondary (box) and Storage Unit (pallet / bin / stillage)
- **Protection materials checklist**: VCI bag, desiccant, VCI emitter, RP oil, thread caps, cushioning, humidity indicator
- **Photos**: 4 per packaging level, from **Camera** or **Gallery**, with captions
- **CTQ check points** for each level, from presets or your own
- **Stacking**: Stackable (with max levels) or Non-stackable
- **4-page PDF** in a standard SOP format
- **Excel master list** of all SOPs, with a separate CTQ sheet
- **Backup / Restore** to move data between phones or keep a safe copy

## PDF layout

| Page | Content |
|---|---|
| 1 | Document details, part information, packaging hierarchy, storage instructions, approval |
| 2 | Primary packaging: specification, protection materials, 4 photos, CTQ check |
| 3 | Secondary packaging: specification, 4 photos, CTQ check |
| 4 | Storage unit: specification incl. stacking, 4 photos, CTQ check |

## Install on your phone

1. Open the app link above.
2. Add it to the home screen:
   - **iPhone (Safari):** Share → **Add to Home Screen**
   - **Android (Chrome):** ⋮ menu → **Add to Home screen**
3. Open it from the home screen icon from then on.

## How to use

1. Tap **+ New SOP**.
2. Fill the tabs: **Document → Part → Primary → Secondary → Storage Unit**.
   A green dot on a tab means its key details are complete.
3. Add photos with **Camera** or **Gallery**.
4. Tap **Download PDF**.
5. From the home screen, tap **⬇ Excel** for the master list.

Everything saves automatically as you type.

## Data and privacy

- All SOPs and photos are stored **only on the device** that created them, in the browser's local storage.
- Nothing is uploaded to GitHub or any server.
- Each phone has its own list. To move SOPs, use **Backup** on one phone and **Restore** on the other.
- Clearing the browser's data deletes saved SOPs. **Take a Backup regularly.**
- On iPhone, adding the app to the home screen keeps Safari from clearing its storage.

## Requirements

- iPhone: Safari (iOS 14 or later)
- Android: Chrome
- An internet connection the first time a PDF or Excel file is created, to load the PDF and Excel engines

## Updating the app

1. Rename the new file to `index.html`.
2. In this repository: **Add file → Upload files** → upload → **Commit changes**.
3. Keep the same link. Saved SOPs on the phones stay intact.

## Files

| File | Purpose |
|---|---|
| `index.html` | The complete app |
| `README.md` | This guide |

---

Prepared by Manoj (Packaging Engineering).
