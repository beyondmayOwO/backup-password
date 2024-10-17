# backup-password
This is the final project for IBM DevOps and Software Engineering Professional Certificate.

## Scenario
Imagine that you are a lead Linux developer at the top-tech company ABC International Inc. ABC currently suffers from a huge bottleneck: each day, interns must painstakingly access encrypted password files on core servers and back up any files that were updated within the last 24 hours. This process introduces human error, lowers security, and takes an unreasonable amount of work.

As one of ABC Inc.'s most trusted Linux developers, you have been tasked with creating a script called backup.sh which runs every day and automatically backs up any encrypted password files that have been updated in the past 24 hours.

## What I Learned
- Check if the number of arguments is correct
- Check if argument 1 and argument 2 are valid directory paths
- Go into the target directory
- Create the backup files
- Move the backup files to the destination directory
- Compress and archive the files
- Backup the important-documents folder every 24 hours to the project directory