# OpenCV-training-course
from this repo you can learn OpenCV step by step in a simple way

## Installing Python 3.10.x on Windows

Here's a full tutorial on installing Python version 3.10.x on Windows:

**1. Download the installer:**

* Visit the official Python downloads page: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)
* Locate the latest stable release in the 3.10.x series (currently 3.10.10).
* Choose the appropriate installer based on your system:
    * **Windows x64** for most modern 64-bit systems.
    * **Windows x86** for older 32-bit systems.

**2. Run the installer:**

* Double-click the downloaded installer file.
* Note to check the "Add Python 3.10 to PATH" option

**3. Verify the installation:**

* Open a command prompt window (search for "cmd" in the Start menu).
* Type `python --version` and press Enter. You should see the installed Python version, like `Python 3.10.10`.
* Alternatively, open the IDLE application (search for "IDLE" in the Start menu). The title bar should display the installed Python version.

**Optional: Add Python to PATH (if not selected "Add Python 3.10 to PATH" option during installation ):**

* Right-click on "This PC" or "My Computer" and select "Properties".
* Go to "Advanced system settings" -> "Environment Variables".
* Under "System variables", find the "Path" variable and click "Edit".
* Click "New" and add the following path (replace "x.x" with your actual version):

```
C:\Python3x.x
```

* Click "OK" on all open windows to save the changes.

**Congratulations!** You have successfully installed Python 3.10.x on your Windows system. 

**Additional notes:**

I apologize for explaining Python in the previous tutorial. Since you already have Python installed, let's focus on setting up VS Code for Python development:

## Installing an IDE like VS code

**1. Install VS Code:**

* **Download VS Code:** Visit the official VS Code website ([https://code.visualstudio.com/](https://code.visualstudio.com/)) and download the installer for Windows.
* **Run the installer:** Double-click the downloaded installer file and follow the on-screen instructions. The default installation settings are usually sufficient.

**2. Install the Python extension for VS Code:**

* **Open VS Code:** Launch VS Code from your Start menu or desktop shortcut.
* **Open the Extensions view:** Click on the Extensions icon (looks like a box with four squares) in the left sidebar, or go to **View > Extensions**.
* **Search for "Python":** In the search bar, type "Python" and press Enter.
* **Install the official "Python" extension:** The extension developed by Microsoft should be the first result. Click the "Install" button.

**3. Verify Python installation:**

* **Open a terminal:** Go to **Terminal > New Terminal** in the VS Code menu.
* **Type "python --version" and press Enter:** This command should display the installed Python version, confirming successful integration with VS Code.

**4. Create your first Python file:**

* **Create a new file:** Go to **File > New File** (or press Ctrl+N).
* **Save the file with a .py extension:** For example, save the file as "hello.py".
* **Write your Python code:** Type your Python code in the file. For example:

```python
print("Hello, world!")
```

**5. Run your Python code:**

* **Open the integrated terminal:** Go to **Terminal > New Terminal** again.
* **Navigate to your file's directory:** Use the `cd` command to navigate to the folder where you saved your Python file.
* **Run the script:** Type `python hello.py` and press Enter. This should execute your code and print "Hello, world!" in the terminal.

**Congratulations!** You have successfully set up VS Code for Python development on Windows. Now you can start writing, running, and debugging your Python projects within VS Code.

**Additional Tips:**

* **Explore extensions:** VS Code offers various extensions for Python development, such as linters, debuggers, and code formatters. Explore the Extensions marketplace to find extensions that enhance your workflow.
* **Refer to official documentation:** For more detailed information and troubleshooting, refer to the official documentation for VS Code and Python:
    * VS Code Python documentation: [https://code.visualstudio.com/docs/python/python-tutorial](https://code.visualstudio.com/docs/python/python-tutorial)

* If you encounter any issues during installation, refer to the official Python documentation for troubleshooting: [https://www.python.org/doc/](https://www.python.org/doc/)
  


