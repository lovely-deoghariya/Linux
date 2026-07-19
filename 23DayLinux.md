# Title: Searching Text Inside Files with `grep`

---

## (1) Create a file named `fruits.txt` with at least 10 lines. Search for the word `Apple` using `grep`.

### Ans:

```bash
nano fruits.txt
```

(Type at least 10 lines, then save and exit.)

```bash
grep "Apple" fruits.txt
```

---

## (2) Search for the word `apple` without considering uppercase or lowercase letters.

### Ans:

```bash
grep -i "apple" fruits.txt
```

---

## (3) Search for the word `Apple` and display the matching line numbers.

### Ans:

```bash
grep -n "Apple" fruits.txt
```

---

## (4) Create a folder named `logs` with two text files. Put the word `ERROR` in one file and use `grep` recursively to find it.

### Ans:

```bash
mkdir logs
touch logs/log1.txt logs/log2.txt
nano logs/log1.txt
```

(Add the word **ERROR**, then save and exit.)

```bash
grep -r "ERROR" logs
```

---

## (5) Display your current working directory after completing today's tasks.

### Ans:

```bash
pwd
```
