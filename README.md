# Python_Getting-Started
A quick how to with your first application example

## __install Python__
 
### Setup linux distro (tested on Ubuntu 22.04 on 09/26/2023)
    Pre-installed on Linux, nothing to do
 
### Setup Windows (tested on Windows 11 on 09/26/2023)
    C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe (right-click -> Run as administrator)
        Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
        exit (or close Administrator: Windows PowerShell window)
    C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe
        Invoke-RestMethod -Uri get.scoop.sh | Invoke-Expression
        scoop install git
        scoop bucket add extras
        exit (or close Windows PowerShell window)
    C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe (right-click -> Run as administrator)
        scoop install vcredist-aio
        exit (or close Administrator: Windows PowerShell window)
    * C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe
        scoop install python
        scoop install mysql-lts ### Run 'mysqld --standalone' or 'mysqld --console' to start the Database
        scoop install mysql-workbench
        scoop install mongodb
        scoop install mongosh
        scoop install mongodb-compass
        code
            Add the following VSCode extensions to VSCode
                ES Lint
                Docker
                GitLens
                isort
                Python and TypeScript Nightly
                learn-markdown
                Live Preview
                MySQL
                PowerShell
                Pylance
                Pylint
                Python
                Reactjs code snippets
                React Native Tools
                ShellCheck
            close VSCode window
 
## __hello-world__ (tested on Ubuntu 22.04 on 09/26/2023)
    touch hello-world.py
    nano ./hello-world.py
    def greet():
        name = input("Please enter your name: ")
        print("Hello, " + name + "! Nice to meet you.")
   
    if __name__ == "__main__":
        greet()
    CTRL-o -> ENTER
    CTRL-x
    /usr/bin/python3 ./hello-world.py
