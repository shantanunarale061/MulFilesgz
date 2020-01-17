THe File folder has source files and there ziped folders with gz extension. It also has a Destination folder where the files will be extracted.
The package uses a Script COmponent configured as source. It truncates the target table, deletes all the content from destination folder and then decrypts the zip file to Destination folder. The target file is then read from the destination folder by Script Component and loaded to a table.
The table script is also attached.
