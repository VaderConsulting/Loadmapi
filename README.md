# Loadmapi

VB6 LoadMAPI (`LoadMAPI.exe`) that walks Exchange/MAPI address-book folders via Microsoft CDO 1.21 into a TreeView. Toggles show Global Address List, users, custom recipients, distribution lists, and address-book views; optional DN tags and LDAP path conversion. Uses `comctl32.ocx` and `netmgr.RES` icons.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Loadmapi.vbp`) | VB6 | WinForms exe | Exchange/MAPI address-book TreeView via CDO |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Loadmapi.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Microsoft CDO 1.21 Library (`cdo.dll`)
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `comctl32.ocx`
- Built resource `netmgr.RES`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Loadmapi`.
Company names in project files: n/a.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
