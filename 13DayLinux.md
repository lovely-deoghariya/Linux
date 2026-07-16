# Title: Viewing the End of Files with tail

---

## (1) Create a file named `logs.txt` with at least 12 lines of text, then display the last 10 lines using `tail`.

### Ans:

```bash
nano logs.txt
```

(Type at least 12 lines, then save with **Ctrl + O**, **Enter**, **Ctrl + X**)

```bash
tail logs.txt
```

---

## (2) Display only the last 5 lines of `logs.txt`.

### Ans:

```bash
tail -5 logs.txt
```

---

## (3) Create a file named `tasks.txt` with at least 8 lines of text and display the last 3 lines.

### Ans:

```bash
nano tasks.txt
```

(Type at least 8 lines, save and exit.)

```bash
tail -3 tasks.txt
```

---

## (4) Navigate to another directory and use `tail` to display the end of a text file there.

### Ans:

```bash
cd ..
tail logs.txt
```

---

## (5) Display your current working directory after completing today's tasks.

### Ans:

```bash
pwd
```
