# Title: Mini Project #1 - Build and Organize a Project Workspace

---

## (1) Create a folder named `data_engineering_project`. Inside it create three folders: `python`, `sql`, and `linux`.

### Ans:

```bash
mkdir data_engineering_project
cd data_engineering_project
mkdir python sql linux
```

---

## (2) Using Nano, create `README.md` in the main folder explaining the project in at least 8 lines.

### Ans:

```bash
nano README.md
```

(Type at least 8 lines, then save and exit.)

```text
Ctrl + O
Enter
Ctrl + X
```

---

## (3) Inside each subfolder, create two text files. Add meaningful content using Nano.

### Ans:

```bash
touch python/python1.txt python/python2.txt
touch sql/sql1.txt sql/sql2.txt
touch linux/linux1.txt linux/linux2.txt
```

(Add content using `nano`.)

---

## (4) Use wildcards to list all `.txt` files. Use `find` to locate `README.md`. Use `grep` to search for the word `Linux` inside all text files.

### Ans:

```bash
ls */*.txt
find . -name "README.md"
grep -r "Linux" .
```

---

## (5) Create a `backup` folder. Copy every `.txt` file into `backup`, rename one copied file, verify the results using `ls`, `head`, `tail`, and finally display your command history.

### Ans:

```bash
mkdir backup
find . -name "*.txt" -exec cp {} backup/ \;
mv backup/python1.txt backup/python_backup.txt
ls backup
head -5 backup/python_backup.txt
tail -5 backup/python_backup.txt
history
```
