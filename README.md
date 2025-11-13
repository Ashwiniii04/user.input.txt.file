# Word Count Program

This project is a simple and user‑friendly C++ program that allows users to:

✔ Enter the **name of any text file** (example: `notes.txt`, `story.txt`, `data.txt`)
✔ Enter **any word** they want to search
✔ Get the **total number of times** that word appears in the file
✔ Word matching is **case‑insensitive** ("The", "THE", "the" all count as same)

---

## 📌 Features

* User can choose any `.txt` file
* Counts any word entered by the user
* Ignores uppercase/lowercase differences
* Easy to use and beginner‑friendly
* Works with all text files placed in the same folder

---

## 🧾 How It Works

1. Program asks the user to input the **file name**.
2. User enters the text file they want to analyze.
3. Program asks for the **word to search**.
4. The program converts both the input word and file words to **lowercase** so the search is case‑insensitive.
5. It scans the file word‑by‑word and counts matches.
6. Displays the total number of times the word appears.

---

## 📥 Example Input

```
Enter your file name: wini.txt
Enter your word: the
```

## 📤 Example Output

```
Total count of 'the' is: 12
```

---

## 📂 File Requirements

* The `.txt` file must be placed in the **same folder** as your `.cpp` file (unless using full path).
* Make sure the file name and extension are correct.

---

## ▶️ How to Run

### Using g++

```
g++ count.cpp -o count

./count
```

### Using an IDE

You can run this program in:

* CodeBlocks
* Dev C++
* VS Code
* OnlineGDB
* Replit

---



## 👤 Author

Ashwini

---

## 📄 License

Free to use for learning and practice.
