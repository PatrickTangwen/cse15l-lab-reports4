# CSE15L Lab Reports 4
In this lab report, I will demonstrate the task we did in the lab.<br>

**1. Setup Delete any existing forks of the repository you have on your account** <br>
<img width="841" alt="image" src="https://user-images.githubusercontent.com/102566928/221334310-30f9f488-513c-4943-b8de-c53517d31df1.png"> <br>
I opened the setting of my previous lab7 repository, and then deleted it on my account. <br>

**2. Setup Fork the repository** <br>
<img width="1223" alt="image" src="https://user-images.githubusercontent.com/102566928/221334446-e34f834b-b18e-44a5-8a1d-b8b65f580d0f.png">
I opened the link of lab7 repository and clicked the fork button. <br>


**3. Log into ieng6** <br><br>
<img width="430" alt="image" src="https://user-images.githubusercontent.com/102566928/221334648-b5d030d7-e037-4b11-8e5a-de7fdb024411.png"><br>
`ssh cs15lwi23akw@ieng6.ucsd.edu` enables me to log into the school server. <br>
Then I typed `<enter>`. It directly logs into the machine. 

**4. Clone your fork of the repository from your Github account**<br>
<img width="859" alt="image" src="https://user-images.githubusercontent.com/102566928/221334900-d6303ec5-b055-4451-86d1-090505b264b6.png"><br>

Before I cloned the repository, I had to remove the previous repository first.<br>
So, I typed `rm -rf lab7` to remove the existing lab7 directory.<br>
key pressed: `<enter>`, it will execute the command above.

<img width="733" alt="image" src="https://user-images.githubusercontent.com/102566928/221334918-3c768c6e-66a6-43ca-be58-864a7abea3ff.png"> <br>

Next, I typed `git clone git@github.com:PatrickTangwen/lab7.git` to clone my new fork of the repository.<br>
key pressed: `<enter>`, it will execute the command above.


**5. Run the tests, demonstrating that they fail**<br>
<img width="982" alt="image" src="https://user-images.githubusercontent.com/102566928/221335045-fbd1ae37-41e0-4b06-9398-38b06149eca0.png"> <br>
I went to the lab7 directory, and typed `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` to compile all the java files.<br>

Then, I typed `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` to run all the tests in ListExamplesTest.java. It turns out that there are two tests and one of the test is fail.<br>

key pressed: `<enter> <enter>`, each enter will execute the each command above.

**6. Edit the code file to fix the failing test**
<img width="1140" alt="image" src="https://user-images.githubusercontent.com/102566928/221335169-d8462849-d957-4c97-9521-5f48f0aa6823.png"><br>
`nano ListExamples.java` will give me the text editor of this file.<br>
key pressed: `<tab><tab><tab><enter>`<br>
The first two <tab> will display the abbreviation of the two java files 'List',then the last `<tab>` will give me the `ListExamples`. <enter> will execute the command I typed.<br>
  
Then I found the bug and fixed. To saved my change, I typed `Ctrl-O`. To back to the previous editor window, I pressed `<enter>`. Then, to exit the text editor, I typed `Ctrl-X` and pressed <enter>, it gives me back to the terminal.

**7. Run the tests, demonstrating that they now succeed**<br>
<img width="1008" alt="image" src="https://user-images.githubusercontent.com/102566928/221336040-a611194e-67e0-4dd1-9b45-0e4e3853a2fe.png">
key pressed: `<up><up><up><enter>, <up><up><up><enter>`<br>
  
The `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` command was 3 up in my search history.So,I used three up arrow to access this command.<br>
  
Same step, `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore` was 3 up in my search histroy. So, I used three up arrows to access this command and then ran it.

**8. Commit and push the resulting change to your Github account**<br>
<img width="515" alt="image" src="https://user-images.githubusercontent.com/102566928/221338406-c47be89f-1468-4ea9-8a0e-6285054f6d13.png">
<img width="727" alt="image" src="https://user-images.githubusercontent.com/102566928/221338422-1e2c5ce4-360e-42bf-804a-7c31921b6486.png"><br>
`git add` will add my changes to an existing file (ListExample) to the set of changes to be committed.<br>
`git commit -m` will commit my changes to the file with the user's message. <br>
`git push` will upload my local repository content to the github remote repository.  
  
key pressed: `<enter><enter><enter>`<br>
Each <enter> will execute the commands above.
 

