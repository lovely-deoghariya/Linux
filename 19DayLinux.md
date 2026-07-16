# Title: Creating and Organizing Notes with `nano`

---

## (1) Create a directory named `study_notes` and move into it.

### Ans:

```bash
mkdir study_notes
cd study_notes
```

---

## (2) Using Nano, create `linux_notes.txt` with at least 15 lines describing commands learned so far. Save and exit.

### Ans:

```bash
nano linux_notes.txt
```

(Type at least 15 lines.)

```text
Ctrl + O
Enter
Ctrl + X
```

---

## (3) Display the first 5 lines and the last 5 lines of `linux_notes.txt`.

### Ans:

```bash
head -5 linux_notes.txt
tail -5 linux_notes.txt
```

---

## (4) Open `linux_notes.txt` using `less`, search for the word `Linux`, then quit. Afterwards, display the file using `cat`.

### Ans:

```bash
less linux_notes.txt
```

Inside `less`:

```text
/Linux
q
```

Then:

```bash
cat linux_notes.txt
```

---

## (5) List all files in the current directory and print your current working directory.

### Ans:

```bash
ls
pwd
```
