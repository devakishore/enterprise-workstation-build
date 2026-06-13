## verify install 

python --version


## Install command 

winget install --id Python.Python.3.12 -e --source winget


## Sample output

PS C:\Windows\system32> pip config set global.require-virtualenv true
Writing to C:\Users\devak\AppData\Roaming\pip\pip.ini



# final step verify 

PS C:\Windows\system32> pip config list
global.require-virtualenv='true'


✔ pip.ini exists
✔ pip.ini is in the correct enterprise location
✔ pip is now locked down to virtual environments only
✔ Your workstation is now following best practices


# Install Python extension for VS CODE 
code --install-extension ms-python.python

code --install-extension ms-python.vscode-pylance



PS C:\Windows\system32> code --install-extension ms-python.python
Installing extensions...
(node:10068) [DEP0169] DeprecationWarning: `url.parse()` behavior is not standardized and prone to errors that have security implications. Use the WHATWG URL API instead. CVEs are not issued for `url.parse()` vulnerabilities.
(Use `Code --trace-deprecation ...` to show where the warning was created)
Installing extension 'ms-python.python'...
Extension 'ms-python.vscode-python-envs' v1.34.0 was successfully installed.
Extension 'ms-python.debugpy' v2026.6.0 was successfully installed.
Extension 'ms-python.python' v2026.4.0 was successfully installed.
Extension 'ms-python.vscode-pylance' v2026.2.1 was successfully installed.


PS C:\Windows\system32> code --version
1.124.0
1b50d58d73426c9171299ec4037d01365d995b78
x64
PS C:\Windows\system32> code --list-extensions
ms-dotnettools.csdevkit
ms-dotnettools.csharp
ms-dotnettools.vscode-dotnet-runtime
ms-python.debugpy
ms-python.python
ms-python.vscode-pylance
ms-python.vscode-python-envs
PS C:\Windows\system32>