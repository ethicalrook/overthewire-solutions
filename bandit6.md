# [Bandit 6]

**Platform:** [OverTheWire]  
**Topic:** [Linux]

## 1. Goal
Finding the file with specific parameters, owned by user bandit7, owned by group bandit6, size=33 bytes

## 2. What I Did
ls, ls -la, Used the specific sub commands of "find" command

```bash
[find / -user bandit7, -group bandit6, -size 33c,
cat /var/lib/dpkg/info/info/bandit7.password]
```

## 3. What Happened
1st command gave the specific file and after doing cat it gave me the password

## 4. Why It Worked
Find command filtered out the files and folders with specific conditions.

## 5. What I Learned
sub commands of find command.

## 6. Key Takeaway
None
