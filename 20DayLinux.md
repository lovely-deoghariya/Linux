# Title: Module 2 Practical Workflow - File Viewing & Editing

---

## (1) Create a directory named `module2_project`. Inside it create files `README.md`, `notes.txt`, and `employees.txt`. Open each file with Nano and add meaningful content.

### Ans:

```bash
mkdir module2_project
cd module2_project
touch README.md notes.txt employees.txt
nano README.md
nano notes.txt
nano employees.txt
```

---

## (2) Display the entire `README.md` file using `cat`. Display the first 5 lines and last 5 lines of `employees.txt`.

### Ans:

```bash
cat README.md
head -5 employees.txt
tail -5 employees.txt
```

---

## (3) Open `employees.txt` using `less`, search for a word, quit, then open the same file using `more` and browse one page.

### Ans:

```bash
less employees.txt
```

Inside `less`:

```text
/word
q
```

Then:

```bash
more employees.txt
```

Inside `more`:

```text
Space
q
```

---

## (4) Copy `README.md` to `README_backup.md`. Rename `notes.txt` to `linux_notes.txt` and verify all files using `ls`.

### Ans:

```bash
cp README.md README_backup.md
mv notes.txt linux_notes.txt
ls
```

---

## (5) Display your command history, print your current working directory, and clear the terminal.

### Ans:

```bash
history
pwd
clear
```
