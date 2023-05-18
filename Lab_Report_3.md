# Lab Report 3 - Researching Commands

## Researching Grep

# grep -r

`grep -r "to answer" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/911report
`

![Image](grepr.png)
In this case, -r used with the grep command is recursively searching for all patterns of **to answer** in all files under the 911report directory. This is very useful if you're looking for a specific phrase or sentence that is repeated among many files under one directory.

`grep -r "Robert H.Cohen" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/government/Post_Rate_Comm `

![Image](grepr2.png)
In this case, -r used with grep searches recursively through all the files in the directory **Post_Rate_Comm** for any patterns of Robert H.Cohen. This is very useful for certain documents in which you're looking for a specific individual's name.

Sources: [Link Grep Commands](https://man7.org/linux/man-pages/man1/grep.1.html)< ChatGPT
ChatGPT Prompt: "What is one command-line option for grep in bash?" 
ChatGPT Response: 
![Image](chatgpt1.png)


# grep -v

`grep -v "Barnes Volunteers as Lawyer to Poor" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/government/Media/Barnes_Volunteers.txt` 

![Image](grepvnew.png)

In this case, -v is used with the grep command to return all strings in the document **Barnes_Volunteers.txt** that are not a part of the given pattern. This is very useful in smaller documents when trying to locate patterns unrelated to the one you're using as an input.

`grep -v "Most patients with celiac disease can eliminate their" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/plos/pmed.0010023.txt`


![Image](grepv2.png), ChatGPT
ChatGPT Prompt: "What is another command-line option for grep in bash?"
ChatGPT Response:
![Image](chatgpt2.png)

In this case, -v is used with grep to return all lines not included in the pattern specified. This is useful when looking through a document and want to exclude certain phrases or information.

Sources: [Link Grep Commands](https://man7.org/linux/man-pages/man1/grep.1.html)

# grep start & end

`grep "^Robert.*Scocchera$" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/government/Post_Rate_Comm/Cohenetal_comparison.txt`

![Image](grepstartend.png)

In this case, using the format above you can search through a file for lines that start with **start** and end with **end**. This can be very useful when trying to search for specific lines or formats within a text.

`grep "^Five.*legal$" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/government/Media/5_Legal_Groups.txt`

![Image](grepstartend2.png)

In this case, we're searching for a line in the **5_Legal_Groups.txt** that starts with **Five** and ends with **legal**. This can be useful is loooking for a specific line within a text document.

Sources: [Start and End Grep](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)

# grep or

`grep "Illinois\|Lawyers" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/government/Media/Annual_Fee.txt`

![Image](grepor.png)

In this case, the use of **\|** functions as an or operater, allowing us to search for two patterns at once. This is very useful in looking for two queries at the same time within a document.

`grep "ripple effects\|Legal Aid" c:/Users/andyy/OneDrive/Documents/GitHub/stringsearch/stringsearch-data/technical/government/Media/balance_scales_of_justice.txt`

![Image](grepor2.png)

In this case, we're searching through the document **balance_scales_of_justice.txt** for two patterns, which are **ripple effects** ad **Legal Aid**. This is useful in terms of efficiency, as we can search for two patterns in one line as opposed to two.

Sources: [Link Grep Commands](https://man7.org/linux/man-pages/man1/grep.1.html), ChatGPT
