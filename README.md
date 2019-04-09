# My-tools
My tools.
    -q            Export IIS7 configuration file
    -dir          Get all site root directories
    -url          Get all site domain names
    -dirdump      Export all site root directories
    -urldump      Export all site domain names
    -copy -p file name
    Copy the specified file to the root directory of all sites
    -copy -pdump file name
    Copy the specified file to the root directory of all sites and export the URL
    -del -p file name
    Batch deletion of specified files from all site root directories
-------------------------------------------------------------------------
Example: iis.exe -copy -p asphxg.txt
Copy asphxg.txt to the root directory of all sites
-------------------------------------------------------------------------
