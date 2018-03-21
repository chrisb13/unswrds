Note: You need to have a working copy of java to use the script.

Step 1: Edit config.cfg
-------

If you are running the script manually:
Add zID after
user=

leave password line blank:
password=
This will force the script to ask for your zPass when you run the script. It is not recommended to save your zPass here as it will be visible to anyone who has access to the file.

If you wish to automate the script please contact the servicedesk.

In the directory containing the script files run the following command to upload data to the Archive:

For Windows:
upload.bat “D:\path\to\your\local\directory” “/UNSW_RDS/D0000000/your/collection/name”
For Linux/Mac OS:
./upload.sh “/path/to/your/local/directory” “/UNSW_RDS/D0000000/your/collection/name”

To download data from the archive:

For Windows:
download.bat “/UNSW_RDS/D0000000/your/collection/name” “D:\path\to\your\local\directory”
For Linux/Mac OS:
./download.sh “/UNSW_RDS/D0000000/your/collection/name” “/path/to/your/local/directory” 

