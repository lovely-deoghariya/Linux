# Title: Finding Files and Directories with `find`

---

## (1) Create three files named `app.py`, `notes.txt`, and `employees.csv`. Use `find` to locate `notes.txt` from the current directory.

### Ans:

```bash
touch app.py notes.txt employees.csv
find . -name "notes.txt"
```

---

## (2) Create two directories named `data` and `backup`. Use `find` to list only directories.

### Ans:

```bash
mkdir data backup
find . -type d
```

---

## (3) Use `find` to locate every `.txt` file in the current directory and its subdirectories.

### Ans:

```bash
find . -name "*.txt"
```

---

## (4) Create a file named `report.txt` inside the `backup` directory. Use `find` to locate `report.txt`.

### Ans:

```bash
touch backup/report.txt
find . -name "report.txt"
```

---

## (5) Display your current working directory after completing today's tasks.

### Ans:

```bash
pwd
```
