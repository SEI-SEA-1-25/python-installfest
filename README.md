# Python Installfest

## Mac (Homebrew install)

`brew install python`

check for pip3

* pip3 --version

install ipython

* `pip3 install ipython`

alias python 

# python 3 aliases
alias python=python3
alias pip=pip3


## Windows (Chocolatey install)

* open a powershell as administrator

* install chocolatey:

https://docs.chocolatey.org/en-us/choco/setup

```c#
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

* install python `choco install python`
* check python version `python --version` `pip --version`
* check virtualenv version `virtualenv --version`
* `pip install virtualenv` if needed
