# SetRegPerms

VB6 SetRegPerms (`SetRegPerms.exe`) UI that grants a username an ACE on a registry path via the SetACL ActiveX control (`SetACL.ocx`; `runme.bat` registers the OCX). Open `SetRegPerms.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SetRegPerms` (`SetRegPerms.vbp`) | VB6 | WinForms exe | Set registry path permissions for a user via SetACL |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `SetRegPerms.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `SetACL.ocx` (see `runme.bat`)

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/SetRegPerms`.
Company names in `.vbp` files: Empired Limited.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
