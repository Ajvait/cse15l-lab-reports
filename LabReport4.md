# CSE 15L Lab Report 4   - Adomas Vaitkus

**Step 4:**

Keys Pressed:
`ssh<space>avaitkus@ieng6-202.ucsd.edu<enter>`

Explanation:
I used the ssh command to log into the ieng6 server remotely

![Image](Lab4Step4.png)

**Step 5:**

Keys Pressed:
`git<space>clone<Ctrl+V><enter>`

Explanation:
I git cloned the repository i had forked in an earlier step onto the ieng6 server I am now logged into.

![Image](Lab4Step5.png)

**Step 6:**

Keys Pressed:
`cd<space>./l<tab><enter>`
`bash<space>t<tab><enter>`

Explanation:
I first changed the directory to be lab7 and then I ran the test script using `bash test.sh` and received the expected results.

![Image](Lab4Step6.png)

**Step 7:**

Keys Pressed:
`vim<space>L<tab>.java`

Explanation:
I entered the ListExamples.java file using vim and then continued editing as explaned after the next screenshot.

![Image](Lab4Step7-1.png)

Keys Pressed:
`:44<right><right><right><right><right>xi2<esc>:wq!`

Explanation:
I skipped to line 44(the desired line to edit), then I moved on top of the character I wanted to delete and used the command x to delete. I then enetered insert mode and inserted a 2, exited insert mode and ran `:wq!` to save and exit the file, the result of my edits before saving and quitting is shown below.

![Image](Lab4Step7-2.png)

**Step 8:**

Keys Pressed:
`bash<space>t<tab><enter>`

Explanation:
I used the tester script again and got the desired results according to the task.

![Image](Lab4Step8.png)

**Step 9:**

Keys Pressed:
`git<space>commit<space>L<tab><enter>`
`committed:wq!<enter>`
`git<space>remote<space>set-url<space>origin<git@github.com/lab7.git<enter>`
`git<space>push<space>origin<space>main`

Explanation:
Used the `git commit` command on `ListExamples.java` and then entered my message before using `wq!` to save and quit out of the `git commit` command and received the message shown below. Then `git push` was used to push the changes onto the branch on github.

![Image](Lab4Step9.png)
![Image](Lab4Step9-2.png)
