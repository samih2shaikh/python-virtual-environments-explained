# 🐍 Installing and Managing Python Virtual Environments  
> A clean start for every Python project—just like using a new notebook for a new subject.

---

## 🎯 Why Use a Virtual Environment?

When working on multiple Python projects, each one may need different versions of packages. A virtual environment helps by:

- Isolating project-specific dependencies  
- Avoiding conflicts between projects  
- Making your project reproducible for others  

---

## 💡 Real-World Example: Freelance Developer with Multiple Clients

Imagine you're a freelance developer:

- Client A wants a data dashboard built with **Plotly 4.5**
- Client B needs an automation script using **Plotly 5.15**

If you install both globally, you'll overwrite one with the other, and suddenly, one client's app stops working.

Instead, create a virtual environment for each project, and each one gets its own version of Plotly. Everyone’s happy, and your code runs consistently—anywhere.

---

## 🧰 Tools We’ll Use

| Tool             | Role                                               |
|------------------|----------------------------------------------------|
| `venv`           | Built-in Python tool to create virtual environments |
| `pip`            | Installs Python packages                            |
| `requirements.txt` | Keeps track of installed packages                |

---

## 🛠️ Step-by-Step Guide

### 1. 🔍 Check Python Version

```bash
python3 --version
