
# Title: Finding Files Quickly with `locate`

---

## (1) Check whether the `locate` command is available by running `locate --version` or `locate notes.txt`.

### Ans:

```bash
locate --version
```

or

```bash
locate notes.txt
```

---

## (2) Create a file named `sample.txt` and try locating it with `locate`. If it isn't found, explain why.

### Ans:

```bash
touch sample.txt
locate sample.txt
```

If the file is not found, it may be because the `locate` database has not been updated yet.

---

## (3) Use `find` to locate `sample.txt` and compare the result with `locate`.

### Ans:

```bash
find . -name "sample.txt"
```

---

## (4) If `locate` is available, run `updatedb` (if permitted) and try locating `sample.txt` again.

### Ans:

```bash
sudo updatedb
locate sample.txt
```

---

## (5) Display your current working directory after completing today's tasks.

### Ans:

```bash
pwd
```
