# Title: Practical Assignment #1 - Linux Basics & File Viewing

---

## (1) Create a directory named `linux_assignment1`. Inside it create files `notes.txt`, `tasks.txt`, and `data.csv`. Display your current location.

### Ans:

```bash
mkdir linux_assignment1
cd linux_assignment1
touch notes.txt tasks.txt data.csv
pwd
```

---

## (2) Copy `notes.txt` to `notes_backup.txt`. Rename `tasks.txt` to `todo.txt`. List all files in the directory.

### Ans:

```bash
cp notes.txt notes_backup.txt
mv tasks.txt todo.txt
ls
```

---

## (3) Add at least 10 lines of text to `todo.txt`. Display the first 3 lines and the last 3 lines.

### Ans:

```bash
nano todo.txt
```

(Add at least 10 lines, then save and exit.)

```bash
head -3 todo.txt
tail -3 todo.txt
```

---

## (4) Create a directory named `archive`. Move `notes_backup.txt` and `data.csv` into `archive`. Verify the contents of `archive`.

### Ans:

```bash
mkdir archive
mv notes_backup.txt data.csv archive
ls archive
```

---

## (5) Display your command history, clear the screen, and finally print your current working directory.

### Ans:

```bash
history
clear
pwd
```
