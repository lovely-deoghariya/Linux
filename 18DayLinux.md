# Title: Revision Quiz #2 - File Viewing & Editing

---

## (1) Create a file named `review.txt` using `nano`. Write at least 12 lines, save it, and exit.

### Ans:

```bash
nano review.txt
```

(Type at least 12 lines, then save and exit.)

```text
Ctrl + O
Enter
Ctrl + X
```

---

## (2) Display the entire contents of `review.txt` using `cat`.

### Ans:

```bash
cat review.txt
```

---

## (3) Display the first 5 lines and the last 5 lines of `review.txt`.

### Ans:

```bash
head -5 review.txt
tail -5 review.txt
```

---

## (4) Open `review.txt` with `less`, search for a word, then quit. Next, open it with `more` and move to the next page before quitting.

### Ans:

```bash
less review.txt
```

Inside `less`:

```text
/word
q
```

Then:

```bash
more review.txt
```

Inside `more`:

```text
Space
q
```

---

## (5) Display your current working directory and list all files in the current directory.

### Ans:

```bash
pwd
ls
```
