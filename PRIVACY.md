# Privacy policy — Notion Weekly Backup

This is a personal backup application for its account owner, not a public backup service.

## Access and use

The app uses the Google Drive `drive.file` scope to create a backup folder, upload weekly ZIP archives, find prior archives created by the app and verify their size and checksum. It does not request general access to existing Drive files, Gmail or Google Photos.

Archives are generated from the owner's existing private Notion backup repository. They contain only the pages already authorized to the read-only Notion integration. The workflow does not expand that integration's page access.

## Storage and sharing

Backup files are stored in the owner's Google Drive. Backup source files remain in the owner's private GitHub repository. The Google OAuth client information and refresh authorization are stored in encrypted GitHub repository Secrets and made available to the backup workflow when it runs. Credentials are not included in archives or this public information repository.

The app does not make backups public, share them with other users, sell data, use data for advertising, or use data to train AI models. Google and GitHub process data to provide storage, authentication and workflow execution under their respective terms and privacy policies. Workflow logs contain archive names, sizes, checksums, commit IDs and links; they do not intentionally include archive contents or credentials.

## Retention and control

Archives are retained until the owner deletes them. The owner can disable the GitHub workflow, remove the repository Secret and revoke the app's Google access through Google Account settings. Revoking access stops future uploads but does not delete existing archives. The owner can delete archives through Google Drive and remove source snapshots through GitHub.

## Limited use

Use and transfer of information received from Google APIs will adhere to the Google API Services User Data Policy, including the Limited Use requirements.

For this personal app, configuration and deletion are controlled by the account owner through Google Account settings and the private backup repository.
