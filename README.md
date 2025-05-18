# Artifitial Vision Project
In this project, a Convolutional Neural Network (CNN) was developed to recognize human emotions. This work was part of a workshop conducted on May 19th, 2025.

## 🔧 Virtual Environment Configuration

> 💡 *Ensure your python version is 3.10*

To set up the virtual environment for this project, follow the steps below according to your operating system.

---

### 🪟 For Windows

#### Using CMD:
```bash
.\setup.bat
```

#### Using PowerShell:
```powershell
Start-Process .\setup.bat
```

---

### 🐧 For Unix-based Systems (Linux/macOS)

```bash
bash setup.sh
```

---

### ⚙️ Manual Setup (Optional)

If you prefer to configure the virtual environment manually:

1. **Create the virtual environment**:
   ```bash
   python -m venv .venv
   ```

2. **Activate it**:
   - On **PowerShell**:
     ```powershell
     & .\.venv\Scripts\Activate.ps1
     ```
   - On **CMD**:
     ```cmd
     .\.venv\Scriptsctivate.bat
     ```
   - On **Unix-based systems**:
     ```bash
     source .venv/bin/activate
     ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Verify the environment**:
   Ensure all required libraries are installed:
   ```bash
   pip list
   ```

> 💡 *It is recommended to upgrade `pip` to the latest version before installing dependencies:*
```bash
python -m pip install --upgrade pip
```
