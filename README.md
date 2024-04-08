# OES-BLS
 Code to compile the OES survey into a sqlite database. It uses:
 - Python: 3.12.0
 - Packages: request, sqlite3, numpy, and pandas
 

 The purpose of this project is to highlight and make accessible the OES survey from the BLS. 
 
## TODO: 
- **Fix the downloading procedure**: sometimes the BLS thinks that I am a bot and block any other connection to their website. Because of that, I disable the downloading mechanism in the code. However, you can still compile the database from the excel files that are in the folder by using the Python codes. 

## INFO: 
- I removed the data folders and the database given the space constraints of github, however, you can download the database from this Dropbox link: https://www.dropbox.com/scl/fo/i80j1jok9effr52ia1qki/h?rlkey=s6j58hg14fp5pyas15ozuk48j&dl=0
- Now the database only has information about total employment, Hourly mean wage, Annual mean wage, and Annual median wage. 
- If you want to have access to other information from the survey you need to add that into the database. You can do that by modifying the code get_OE_data_from_xlsx.py and config.py.
    - However, to do that, you will need to make the folder structure for the data. If I fix download_and_save.py this can be done automatically, however, now we have the problem that I told you on the TODO section.
- Now the size of the database is around 3.00 GBs


