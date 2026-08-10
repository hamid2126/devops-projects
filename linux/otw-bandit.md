# Over The Wire Bandit Solutions

## Level 0 → 1

### Commands used
``` bash
ls
cat readme
```

### What this does
Lists files and reads contents of the files

---

## Level 1 → 2
### Commands used
``` bash
ls
cat ./-
```

### What this does
Reads files with special characters

---

## Level 2 → 3
### Commands used
``` bash
ls
cat ./"--spaces in this filename--"
```

### What this does
Reads files with spaces in the file name

---

## Level 3 → 4
### Commands used
``` bash
ls
cd inhere
ls -a
cat ./...Hiding-From-You
```

### What this does
Changes directory and lists hidden files

---

## Level 4 → 5
### Commands used
``` bash
file ./*
cat ./-file07
```

### What this does
Tells you what type each file is in the current directory

---

## Level 5 → 6
### Commands used
``` bash
find . -type f -size 1033c ! -executable
cat ./maybehere07/.file2
```

### What this does
Finds a file from the current directory that is exactly 1033 bytes (c=bytes) and the file must not be executable

---

## Level 6 → 7
### Commands used
``` bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
```

### What this does
Finds a file owned by user bandit7 and group bandit6 with the size 33 bytes, whilst also ignoring error messages (Permission denied)

---

## Level 7 → 8
### Commands used
``` bash