# Lab Report 4 

Step 4:

![Image](step4.png)

I typed my remote access login information, followed by `<enter>` to establish remote connection.
  
Step 5:
  
![Image](step5.png)

I then used the git clone command followed by the url of the repository I was forking, finished with `<enter>`.

![Image](vimstep.png)

Step 6:

I ran the following tests in the `test.sh` file, which yielded some errors.
`javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`
`java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`

![Image](tests.png)

Step 7:

I then used the change directory command to change into lab7's directory, followed by looking for the ListExamples.java which held the corresponding code. I then activated vim with the corresponding file.

![Image](vimstep2.png)

Keys pressed: `<up> * 5 | <left> * 12 | i | <backspace> | 2 | <esc> | :w | :q |`
I navigated to the line `index1+=1`, then entered insert mode. I then deleted the 1, inputted the 2, used esc, and saved while exiting vim.

![Image](vimresult.png)

Step 8:

I used `bash test.sh` to run the testers. I passed both of them, leaving me to conclude I made the corrections and the code is working properly now.

![Image](bashtest.png)

Step 9:

I then used git add and commit with the following message "Fix failing tests" to push my changes to my github page.

![Image](gitpush2.png)
  
  
  
  
  
