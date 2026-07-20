# Title: Using Wildcards (*, ?, and [])

---

## (1) Create files named `report1.txt`, `report2.txt`, `report3.txt`, and `notes.txt`. List only the `.txt` files using a wildcard.

### Ans:

```bash
touch report1.txt report2.txt report3.txt notes.txt
ls *.txt
```

---

## (2) Create files named `file1.txt`, `file2.txt`, and `file10.txt`. Use a wildcard to display only `file1.txt` and `file2.txt`.

### Ans:

```bash
touch file1.txt file2.txt file10.txt
ls file?.txt
```

---

## (3) Create files named `testA.txt`, `testB.txt`, and `testC.txt`. Use square brackets to list only `testA.txt` and `testB.txt`.

### Ans:

```bash
touch testA.txt testB.txt testC.txt
ls test[A-B].txt
```

---

## (4) Copy all `.txt` files into a directory named `backup` using a wildcard.

### Ans:

```bash
mkdir backup
cp *.txt backup/
```

---

## (5) Display your current working directory and list the contents of the `backup` directory.

### Ans:

```bash
pwd
ls backup
```
