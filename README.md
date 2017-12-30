# UniqueCopy
Copy a file to a folder, if there's the same file in the folder elsewhere, then create a link. Command and manage tool.

# Plan

1. file md5 calculating
2. md5 key: md5 + md5-head-512, + size
3. sqlite db
4. a user folder with ".unique-copy" subfolder,
```
     [dest folder]
       [.unique-copy]		//config folder
         .unique-copy-tool	//config file, double click to open manage tool.
         .db			//database
```
5. link to oldest file
6. compare file, parent folder, ancester folder for oldest file
7. db table
     [file] md5 key, is file flag, file path, file name, file date, file size


