# dotfiles-windows-office

This is my windows dotfiles for my office laptop.

## Getting Started

This dotfiles utilize [Chocolatey](https://chocolatey.org). Run the following command in **Powershell as Administrator** to install Chocolatey in your machine

```ps1
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

Now that you have installed Chocolatey, you can execute `install.ps1` script. Remember to execute it in **Administration Mode**

Have a nice day!