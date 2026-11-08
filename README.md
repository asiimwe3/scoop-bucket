# DeryCode Scoop bucket

Install DeryCode Windows apps with Scoop. No account, no store approval queue.

## Add the bucket

```powershell
scoop bucket add derycode https://github.com/asiimwe3/scoop-bucket
```

## Install School Report Maker

```powershell
scoop install derycode/school-report-maker
```

## Update

```powershell
scoop update
scoop update school-report-maker
```

## Uninstall

```powershell
scoop uninstall school-report-maker
```

Requires an elevated shell for install and uninstall, because the app installs machine-wide into Program Files.

## Notes

- The installer is the same signed MSI published on GitHub Releases, verified by SHA-256 on download.
- Runs fully offline. All school data lives in one local file with rotating backups.
- Manifest lives at `bucket/school-report-maker.json`.

Published by DeryCode Technologies, Kyenjojo, Uganda. https://derycode.online/app.html
