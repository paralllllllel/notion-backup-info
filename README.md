# Notion Weekly Backup

A personal backup application that archives previously authorized private Notion pages to the owner's Google Drive, using GitHub Actions once a week.

The application creates a private `Notion Backups` folder and dated ZIP archives in the authorized Google account. Archives contain Markdown, structured data and downloaded attachments from the existing private backup repository. Uploads are verified by size and checksum. Existing archives are retained until the owner removes them.

Google access is limited to `https://www.googleapis.com/auth/drive.file`: only files and folders created by, or explicitly opened with, this application. The application does not request access to the rest of the account's Drive, Gmail or Photos.

This repository contains application information only. It contains no backup content or credentials.

[Privacy policy](PRIVACY.md)
