# [Lab / Level Name]

**Platform:** [OverTheWire / pwn.college / DVWA]  
**Topic:** [Linux / SQL Injection / XSS / etc.]

## 1. Goal
Find the file with specific conditions contains the password: human-redable, 1033 bytes in size, not executable

## 2. What I Did
Tried ls, ls -la for checking the hidden file.
The main command I solved the level is:

```bash
[find . -readable -size 1033c ! -executable,
cat ./maybehere07/.file2]
```

## 3. What Happened
From the multiple folders and files I found the only one file matching the specific conditions.

## 4. Why It Worked
With the help of find command.

## 5. What I Learned
If you want to find a file with specific conditions or specifications you can find it with the help of "find" command

## 6. Key Takeaway
Find is the very important command.
