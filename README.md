# AUTOMATING
This helps in automating all excel files (inclusing csvs &amp; excel) Ingestion on to Azure Data Studio(SQL-Server).
If the file is in format that will accepted by SQL then it will allow to download file automatically.
Just change the path to your folder that might contain excel files with all other files. 
One of the function created will provide out of all available files, only just the list of excel files. 
And then that list of files can be automated to ingest on to sql server, making in between adjustment of column names in desired format.
But If case say files such format that is not acceptable format then will not able to upload it, but will still continue to proceed ahead as loop is masked by try catch.

