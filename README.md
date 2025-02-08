# 📖 Machine Learning Exams Collection

This repository contains a collection of **Machine Learning exam papers** from the **University of Padua**, part of the **Master's Degree in Computer Engineering** – **AI & Robotics track**, taught by **Prof. Vandin**.

The exams include **theoretical questions, practical exercises, and solutions**, all formatted in **LaTeX**.

---

## 📌 Contents

- 📂 `exams/` → **LaTeX source files** of the exams.
- 📄 `exams.pdf` → **Compiled version** of all exams in one document.
- 🖼 `figures/` → **Images used** in the exams (graphs, diagrams, etc.).
- 📜 `README.md` → This file, explaining the project.
- 📜 `LICENSE` → Repository license (if applicable).

---

## 🚀 How to Compile

To generate the **PDF version** of the exams, compile the LaTeX files using **pdflatex** or **Overleaf**.

### **Using pdflatex (Local Compilation)**

Ensure **TeX Live** or **MikTeX** is installed, then run:

```bash
pdflatex exams.tex
bibtex exams
pdflatex exams.tex
pdflatex exams.tex
```

### **Using Overleaf**

1. Upload all `.tex` files, `.bib` (if any), and the `figures/` folder.
2. Click **Recompile** to generate the PDF.

---

## 📝 Example Output

📄 Here’s a preview of the compiled document:

![Exam Cover](images/cover.pdf)

For the full document, check [**exams.pdf**](exams.pdf).

---

## 🤝 Contributing

Feel free to contribute by:

- **Adding new exams**
- **Fixing typos or improving formatting**
- **Providing alternative solutions**

### **How to contribute**

1. **Fork** this repository.
2. **Create a new branch**:
   ```bash
   git checkout -b feature-name
   ```
3. **Commit your changes**:
   ```bash
   git commit -m "Added new exam"
   ```
4. **Push to your branch**:
   ```bash
   git push origin feature-name
   ```
5. **Open a Pull Request**.

---

## 🐞 Reporting Issues

If you find any **errors, typos, or formatting issues**, please open an **Issue** on GitHub:

1. Go to the **Issues** tab of this repository.
2. Click **New Issue**.
3. Provide a clear description of the problem.
4. If possible, attach a screenshot or reference the affected section.

I will review and fix the reported issues as soon as possible.

---

## 📜 License

This repository is licensed under the **MIT License**. You are free to use, modify, and distribute this material with attribution.

---

🎯 **If you find this project useful, don't forget to ⭐ star the repository!** 🚀🔗
