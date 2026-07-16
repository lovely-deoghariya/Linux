# Title: Reading Large Files with `less`

---

## (1) Create a file named `notes.txt` with at least 25 lines and open it using `less`.

### Ans:

```bash
nano notes.txt
```

(Add at least 25 lines, save and exit.)

```bash
less notes.txt
```

---

## (2) Inside `less`, move to the next page and then return to the previous page.

### Ans:

```text
Space      → Next page
b          → Previous page
```

---

## (3) Search for a word that appears in your file using the search feature.

### Ans:

```text
/word
```

Example:

```text
/Linux
```

Press **Enter** to search.

---

## (4) Exit `less` using the correct keyboard key.

### Ans:

```text
q
```

---

## (5) Display your current working directory after finishing the exercise.

### Ans:

```bash
pwd
```

---

# Mini Challenge

## Create a file named `employees.txt` with 30 lines. Open it with `less`, search for one employee name, scroll to the bottom, then quit.

### Ans:

```bash
nano employees.txt
```

(Add 30 lines, then save.)

```bash
less employees.txt
```

Inside `less`:

```text
/Employee
