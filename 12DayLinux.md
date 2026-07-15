# Title: Viewing the Beginning of Files with head

## (1) Create a file named fruits.txt with at least 10 line of text, then display the first 10 lines using head
**Ans:**
```bash
cat > fruits.txt
Apple
Banana
Mango
Orange
Grapes
Papaya
Guava
Pineapple
Litchi
Watermelon
```
Press **Ctrl + D** to save the file.

```bash
head fruits.txt
```

## (2) Display only the first 5 lines of fruits.txt
**Ans:**
```bash
head -5 fruits.txt
```

## (3) Create a file named employees.txt with at least 8 lines and display the first 3 lines
**Ans:**
```bash
cat > employees.txt
Rahul 
Priya
Aman
Neha
Rohit
Sneha
Vikas
Anjali
```

## (4) Navigate to another directory and use head to view the beginning of a text file there
**Ans:** 
```bash
cd ..
head -5 fruits.txt
```

## (5) Display your current working directory after completing todays tasks 
**Ans:**
```bash
pwd
```
