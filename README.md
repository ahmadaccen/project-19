# Project 19 - Scheduled S3 Backup

## Goal

Automate backup routines using Linux cron jobs and Amazon S3.

## Files

- backup.sh
- app.log

## Tasks Completed

- Created log file
- Created backup script
- Uploaded logs to Amazon S3
- Configured cron job for automated backups
- Verified backup files in S3

## Backup Script

```bash
aws s3 cp ~/project19/app.log s3://ahmad-project19-backup-1795187214/
```

## Cron Schedule

```text
*/5 * * * * /home/clouduser/project*9/backup.sh
```

## Verification

*ackup file successfully uploaded t*:

```text
s3://ahmad-project19-ba*kup-1795187214/
```

File:

```tex*
app.log
```

## Deliverables

- C*on job screenshot
- S3 bucket scre*nshot showing backup file
