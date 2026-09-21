# [bandit 8]

**Platform:** [OverTheWire]  
**Topic:** [Linux]

## 1. Goal
The password was inside the file having bunch of fake passwords and repeted but the real password is only repeat once.

## 2. What I Did
print out the all the data.txt. Then first sorted the data and then found the unique string from the file.

```bash
[sort data.txt | uniq -u]
```

## 3. What Happened
I got only one password that was only repeated once

## 4. Why It Worked
After running that command all the text got sort out with the help of sort commmand and then uniq -u found the only text which
was appeared once.

## 5. What I Learned
Learned about uniq -u command.

## 6. Key Takeaway
None
