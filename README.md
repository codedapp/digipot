# DIGIPOT 0.4.16 browser release

Browser-accessible build reconstructed from the verified DIGIPOT `0.4.16-pilot` APK supplied on 3 September 2026.

## Live application

After GitHub Pages deployment, open: `https://codedapp.github.io/digipot/`

The interface is responsive for phones and tablets and can continue working offline after the first successful load.

## Data and privacy

DIGIPOT is offline-first. Client records, drafts, signatures, audit metadata and generated PDFs are stored locally in the current browser using localStorage and IndexedDB. They are not uploaded to this repository or synchronized between devices.

Use **Postavke → Izvezi sigurnosnu kopiju** before clearing browser storage, changing device or reinstalling the browser.

## Important limitations

- Browser data is separate from data inside the Android APK.
- Browser private/incognito mode may remove data automatically.
- Location capture requires HTTPS, browser permission and device location services.
- Sharing and printing use the browser or operating system facilities.
- DIGIPOT signatures are not qualified electronic signatures (QES).

## Integrity baseline

- Source APK SHA-256: `b1b4e6919b69a05cb86275428000861cdab76e99ea1f7dc702a39ef5bf0b61d3`
- Embedded source SHA-256 before browser-only additions: `03aee1edd8b90d533efe4724903d881a54367dd45396a163feb1f444f7775612`
- DUX legal wording and seller signature coordinates are unchanged.

Author and owner: Mladen Tićak. DIGIPOT © 2026 Mladen Tićak.
