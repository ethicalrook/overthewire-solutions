# [Level 10]

**Platform:** [OverTheWir]  
**Topic:** [Linux]

## 1. Goal
The password was inside the data.txt but it was in the base64 format

## 2. What I Did
First performed cat data.txt to watch the base64 format
Then performed base64 -d data.txt to convert base64 data into string

```bash
[base64 -d data.txt]
```

## 3. What Happened
The base64 data converted into string

## 4. Why It Worked
The command converts base64 into string

## 5. What I Learned
To convert base64 data into string we use the base64 -d command

## 6. Key Takeaway
None
