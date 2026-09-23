# [bandit level 11]

**Platform:** [OverTheWire]  
**Topic:** [Linux]

## 1. Goal
The password of the next level was encoded in rot13 encoding algorithm and we have to decode it using tr logic.

## 2. What I Did
piped the command tr with the password to decode the level

```bash
[cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m']
```

## 3. What Happened
The passoword decoded in normal string

## 4. Why It Worked
tr command decoded the rot13 algorithm 

## 5. What I Learned
None

## 6. Key Takeaway
None
