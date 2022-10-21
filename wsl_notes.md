WSL Notes
=========


Navigating Between Windows and WSL
----------------------------------

### From WSL: ###

- `C:\` --> `/mnt/c`
- Windows 'home' directory (`C:\Users\<username>`) --> `/mnt/c/Users/<username>`

Note you can also open a Windows Explorer window in a current WSL directory by typing `explorer.exe .`



### From Windows: ###

Windows treats WSL installations as mounted drives. In Explorer you can navigate to `\\wsl$` since all WSL installations share a single kernel. Thus an Ubuntu installation would be at `\\wsl$\Ubuntu` and a user's home directory will be at `\\wsl$\Ubuntu\home\<username>`


Upgrading Major Ubuntu Versions
-------------------------------

See [this AskUbuntu question](https://askubuntu.com/questions/1428423/upgrade-ubuntu-in-wsl2-from-20-04-to-22-04) 



Articles Referring to Mysterious Crashing of Ubuntu/WSL
-------------------------------------------------------

- [why does this error appear and how to fix it? process exited with code 4294967295 (0xffffffff)](https://answers.microsoft.com/en-us/windows/forum/all/why-does-this-error-appear-and-how-to-fix-it/0473eb22-3827-4fc6-bce6-ae63b73882d7)
- [Terminal exiting with code 4294967295 every time](https://answers.microsoft.com/en-us/windows/forum/all/terminal-exiting-with-code-4294967295-every-time/920b405b-38df-435b-bd31-550ce29f31c8)
- [How to Fix “Error Code: 4294967295” on WSL?](https://appuals.com/wsl-fails-to-start-error-4294967295/)
- [WSL2 distro failing to startup with code 4294967295 #5092](https://github.com/microsoft/WSL/issues/5092)
- [Updated Windows Terminal and now Ubuntu won't load. process exited with code 4294967295 (0xffffffff)](https://superuser.com/questions/1706906/updated-windows-terminal-and-now-ubuntu-wont-load-process-exited-with-code-429)


Non-WSL-Specific Documents
--------------------------

- [The UNIX Workbench Ebook](https://seankross.com/the-unix-workbench/command-line-basics.html)
- [The Art of the Command Line](https://github.com/jlevy/the-art-of-command-line)
- [The Bash Guide](https://guide.bash.academy)
- [Awesome Command Line Apps](https://github.com/herrbischoff/awesome-command-line-apps)
