# Question 1
## Question 1_1 — User Identity Verification

### Task
**Display your currently logged-in username and all groups your user account belongs to.**  
✅ Your name/login ID must appear in the output.

---

### What I did
I used:
- `whoami` to print the currently logged-in username
- `who am i` to print the currently logged-in username, terminal session, when login session started
- `groups` to print all groups my user belongs to  
- `id` to print both currently logged-in username and all groups

---

### Commands
```bash
whoami
who am i
groups
id
```

### Screenshot
![Terminal](Screenshots/Question_1_1.png)

## Question_1_2 - Workspace Validation

### Task
**Display the current working directory and list all files and directories in that location using long format listing.**

___

### What I did
I used:
- `pwd` (print working directory) to show the full path of the directory I am currently in.
- `ls -l` to list the contents of the directory in "long" format, which shows pwermissions, owner, size and modification date.
- `ls -la` to list the contents of the directory in "long" format, which shows permissions, owner, size, and modification date along with hidden files.

### Commands
```bash
pwd
ls -l
ls -la
```

### Screenshot
![Terminal](Screenshots/Question_1_2.png)

## Question_1_3 - Environment Confirmation File

### Task
**Create a file named `user_info.txt` and write the line: "Linux user environment verified"**

### What I did
I used:
- `echo` to output the specific string of text.
- The `>` redirection operator to write that output directly into a new file named `user_info.txt`.
- `cat` to verify the file was created correctly and contains the text.

### Commands
```bash
echo "Linux user environment verified" > user_info.txt
cat user_info.txt
```

### Screenshot
![Terminal](Screenshots/Question_1_3.png)
