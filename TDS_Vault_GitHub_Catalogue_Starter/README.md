# TDS Vault public sync catalogue starter

Upload only `catalog.json` from this archive to the root of a PUBLIC GitHub repository named `TDS-vault-docs`. Do not upload this README unless you want it.

The catalogue holds 10 existing product IDs, public identifying fields, and three Duratec manufacturer TDS links. It intentionally excludes internal notes, approvals, staff assignments and the bundled EA9396 PDF. The APK already holds the original EA9396 PDF offline.

Android app: Admin > Offline library & GitHub sync > paste:
https://raw.githubusercontent.com/YOUR-USERNAME/TDS-vault-docs/main/catalog.json
Tap Save URL then Sync catalogue now. New materials added to the JSON need unique stable IDs. Each PDF requires an HTTPS `tds_url`, and may be saved offline from the product screen.

Do not use a PUBLIC repository for confidential content. The current APK only supports a public raw GitHub catalogue without credentials.
