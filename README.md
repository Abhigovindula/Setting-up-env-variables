# 📌 Setting Up and Using Virtual Environments in Python

> This guide explains how to create, activate, manage, and deactivate virtual environments for different tools like Flask, SQL, APIs, etc while keeping everything organized in your folder.

---

## 🚀 First-Time Setup (New Virtual Environment)

1. **Go to the folder where you want to set up the environment**

   ```sh
   cd (give_path)
   ```

2. **Create a virtual environment (only required once per project)**

   ```sh
   python -m venv env
   ```

3. **Activate the virtual environment**

   ```sh
   env\Scripts\Activate
   ```

4. **Install required packages**

   ```sh
   pip install flask  # Replace 'flask' with any package
   ```

5. **To save installed packages (optional but recommended)**

   ```sh
   pip freeze > requirements.txt
   ```

6. **Deactivate the virtual environment when done** 

   ```sh
   deactivate
   ```

---

## 🔄 Reopening and Continuing Work Later

1. **Go to your folder**

   ```sh
   cd (your_path)
   ```

2. **Activate the virtual environment**

   ```sh
   env\Scripts\Activate
   ```

3. **Start working**


4. **Deactivate when done**

   ```sh
   deactivate
   ```

---

## 📂 Checking Installed Packages in a Virtual Environment

1. **List all installed packages**

   ```sh
   pip list
   ```

2. **Check saved dependencies**

   ```sh
   cat requirements.txt
   ```

3. **Update each time after installing new packages**

   ```sh
   pip freeze > requirements.txt
   ```

4. **To reinstall packages (e.g., on another system)**

   ```sh
   pip install -r requirements.txt
   ```

---

## ⚡ Extra Tips

- **You only need to create env variables once per project.**
- **Always activate env variables before working in your folder.**
- **Deactivate when done**
  

> By following these steps, you ensure a clean and organized learning experience for each tool inside your folder.

---

🚀 Happy Coding! 🎯

