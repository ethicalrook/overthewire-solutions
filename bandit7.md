Level 7
Goal: There is a file named data.txt and the password is is next to the word millionth 
Tried: ls, grep
Key: hidden file + permissions
Solved with: grep "millionth" data.txt
Learned: grep finds the specific word from the file

# [bandit7]

**Platform:** [OverTheWire]  
**Topic:** [Linux]

## 1. Goal
The password of next level is inside the file data.txt and near the word millionth

## 2. What I Did
Used grep command to find the line that contains the word millionth

```bash
[grep "millionth" data.txt]
```

## 3. What Happened
It found the word and also found the password that was inthe same line.

## 4. Why It Worked
grep command finds the specific command and gives the full line that contains the specific word.

## 5. What I Learned
grep gives the full line containing the words that we searched for. (example as above)

## 6. Key Takeaway
None
