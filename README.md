# IDP Course Base Environment & Assignment Starter

Welcome! This repository contains the standardized Python development environment for our class assignments. It is configured to run seamlessly both in **GitHub Codespaces** (cloud browser setup) and **locally on Windows / Mac / Linux via VS Code** without requiring Docker. This does not require **Anaconda** to be configured. You should select the ".venv" python environment when running.

---

## Quick Start: Getting to Your Assignment

This assignment's tasks are located in **`processing.ipynb`**. 

Follow the instructions below for your chosen setup option to configure your environment, then open **`processing.ipynb`** to begin your work.

---

## Environment Setup Options

Choose **one** of the two methods below to open and run your workspace.

### Option 1: Local VS Code Desktop *(Windows / Mac / Linux)*

Lab Computers:

1. **Clone & Open:** Clone this repository to your machine and open the project folder in **VS Code**.
2. **Build Environment (1-Click Setup):**
   * Press **`Ctrl + Shift + B`** on Windows (or **`Cmd + Shift + B`** on Mac).
   * Alternatively, go to the top menu: **Terminal** > **Run Build Task...** > select **1-Click Setup Python Environment**.
   * *This task creates a local virtual environment (`.venv`), upgrades `pip`, and installs all required base dependencies. It is safe to run multiple times.*
3. **Open Assignment:** Open `processing.ipynb`.
4. **Select Kernel:** In the top-right corner of the notebook, ensure the kernel is set to **`Python (.venv)`** (or select **Select Kernel** > **Python Environments** > **.venv**).

---

### Option 2: GitHub Codespaces

1. Click the green **Code** button at the top right of this repository.
2. Select the **Codespaces** tab and click **Create codespace on main**.
3. Wait for the environment to build (1–2 minutes). 
4. Open `processing.ipynb`. The Python kernel will connect automatically—press **Run All** to test!

---

## Verifying Your Environment

Before starting your assignment, you can verify that your environment, Python version, and standard libraries are correctly connected.

1. Open `test_environment.ipynb`.
2. Run the test cell. You should select the **".venv"** python environment when running!
3. You should see output similar to this:

```text
Python Version: 3.13.x
Executable Path: ...\.venv\Scripts\python.exe
Pathlib Working Directory: ...\idp-assign-1-processing
ipykernel Version: 7.x.x

Environment setup verified successfully!