# Lab Report 3 - Researching Commands

## Researching Find

grep -r

`grep -r "to answer" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/911report
`

![Image](grepr.png)
In this case, -r used with the grep command is recursively searching for all patterns of **to answer** in all files under the 911report directory. This is very useful if you're looking for a specific phrase or sentence that is repeated among many files under one directory.



grep -v

`grep -v "Barnes Volunteers as Lawyer to Poor" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/government/Media/Barnes_Volunteers.txt
`

![Image](grepvnew.png)

In this case, -v is used with the grep command to return all strings in the document **Barnes_Volunteers.txt** that are not a part of the given pattern. This is very useful in smaller documents when trying to locate patterns unrelated to the one you're using as an input.
