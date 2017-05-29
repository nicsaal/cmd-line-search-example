# cmd-line-search-example
Command-line text search

searches your com directory for a file name that matches the users arguments and returns the matching result in the form of a zip file.
Extract the zip file and try the following command from the command line from the FileSearch/bin directory: 
java com.example.filesearch.FileSearchApp ./ .*file.* ../test.zip

This searches all directories for any filename containing the word "file" and exports the search results to the root directory in test.zip
