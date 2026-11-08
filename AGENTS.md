# Release publishing instructions

- Always upload the **APK first**, wait for it to finish, then upload its **SHA-256 checksum**.
- Use separate sequential upload commands; one command with multiple files can upload concurrently. Preserve this order on retries too.
- Publish the release only after both uploads succeed. Follow the manual workflow in `.github/workflows/publish.yml`.
