# AUTOMATING
This helps in automating all excel files (inclusing csvs &amp; excel) Ingestion on to Azure Data Studio(SQL-Server).
<h4> Just change the path to your folder that might contain excel files with all other files.  
One of the function created, will provide out of all available files, only just the list of excel files & it copies those selected file into new folder. 
And then that list of files in new directory is used to ingest files on to sql server. Before executing upload it does in between adjustment of column names in desired format. So, that no error it returns (tried my best to cover all possible cases that could return error).
But, In case say any files whose format that is such that which wouldn't be acceptable as per norms of sql ingestion then it will not able to upload it, but it will still continue to proceed ahead as loop is masked by try catch.</h4>

Do give your Feedback, if possible. Thanks.

