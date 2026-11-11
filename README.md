# BD House Configurator

Quote and order tool for the BD House UK team (Unit 6 Watford), for products made by 升威 LE-RELAX, Zhongshan.

## What's in here
| File | What it is |
|---|---|
| `index.html` | The whole configurator: product picker, sizes, drawings, UK prices, customer quote, factory order sheet (bilingual, no prices), Excel export. One self-contained file. |
| `downloads/BD_House_Quote_Order_Tracker.xlsx` | The back-office tracker: Settings, Price_Book, Price_List, Customers, Quote_Lines, Quotes, Orders, Dashboard. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. |

## Put it online (GitHub Pages)
1. Create a new repository on GitHub, e.g. `bdhouse-configurator`. A private repo needs a paid GitHub plan for Pages; otherwise make it public.
2. Upload every file in this folder, keeping the `downloads` folder (Add file → Upload files, drag the folder contents in, Commit).
3. Settings → Pages → Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)** → Save.
4. After a minute the site is live at `https://<your-username>.github.io/bdhouse-configurator/`.
5. The tracker downloads from `https://<your-username>.github.io/bdhouse-configurator/downloads/BD_House_Quote_Order_Tracker.xlsx`.

## Good to know
- Saved quotes live in each person's browser on that device only. Use **Export to Excel** in *Quotes & orders* regularly and paste the rows into the tracker.
- Prices and pricing settings are built into `index.html`. To update them, replace `index.html` with a new version.
- Needs an internet connection the first time for fonts and the Excel export library (cdnjs).
- Anyone with the link can open the page. The manager-only "Factory cost & margin" panel is visible in the page, so share the link with staff only.
