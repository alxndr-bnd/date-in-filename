# date-in-filename

The goal is to learn how to generate filename based on current date + time

Use create-file-with-date-in-filename.sh to create an empty file with
Y.M.d-h.m.s.log filename format
To run cron use:
`crontab -e`
add
`* * * * * path/to/file/create-file-with-date-in-filename.sh`
to run cron job every minute
