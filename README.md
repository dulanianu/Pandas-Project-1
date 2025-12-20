# Environment Setup for a Python - Pandas Project

A beginner-friendly project demonstrating **practical Pandas use cases** for data analysis using Python.
This project focuses on setting up a **clean, reproducible environment** and working with Jupyter notebooks in **VS Code**.

---

## Project Overview

This repository showcases:

* Pandas fundamentals and common use cases
* A reproducible Python environment
* Jupyter Notebook integration with VS Code

---

## Environment Setup

This project uses **Conda** to manage the Python environment.

### 1️⃣ Create a new Conda environment (pandas_tutorials)

Open **Anaconda Prompt** (Windows) and run:

```bash
conda create --name pandas_tutorials python=3.11
```

Activate the environment:

```bash
conda activate pandas_tutorials
```

When activated, you should see:

```text
(pandas_tutorials)
```

---

### 2️⃣ Install required packages

With the environment activated, install the dependencies:

```bash
pip install numpy pandas openpyxl pyarrow pyjanitor ipykernel
```

---

### 3️⃣ Register the environment as a Jupyter kernel

This step is required so that the environment appears in Jupyter notebooks:

```bash
python -m ipykernel install --user --name pandas_tutorials --display-name "Python (pandas_tutorials)"
```

---

## 📓 Using the Environment in VS Code

1. Open this project folder in **Visual Studio Code**
2. Create a notebook file:

   ```text
   file_name.ipynb
   ```
3. Open the Command Palette:

   ```
   Ctrl + Shift + P
   ```
4. Select:

   ```
   Notebook: Select Kernel
   ```
5. Choose:

   ```
   Python (pandas_tutorials)
   ```

Your notebook is now connected to the correct environment ✅

---


