# practice_temp

## Соответствие групп и тем на практикум.

1. Что такое система контроля версий
2. Для чего нужна система контроля версий
3. Установка git на ваш ПК (в зависимости от системы)
4. Установка VSCode на ваш ПК
Installation
Download the Visual Studio Code installer for Windows.
Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe). This will only take a minute.
By default, VS Code is installed under C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code.
Alternatively, you can also download a Zip archive, extract it and run Code from there.

Tip: Setup will add Visual Studio Code to your %PATH%, so from the console you can type 'code .' to open VS Code on that folder. You will need to restart your console after the installation for the change to the %PATH% environmental variable to take effect.

User setup versus system setup
VS Code provides both Windows user and system level setups. Installing the user setup does not require Administrator privileges as the location will be under your user Local AppData (LOCALAPPDATA) folder. User setup also provides a smoother background update experience.

The system setup requires elevation to Administrator privileges and will place the installation under Program Files. This also means that VS Code will be available to all users in the system.

See the Download Visual Studio Code page for a complete list of available installation options.

32-bit versions
If you need to run a 32-bit version of VS Code, both a 32-bit Installer and Zip archive are available.

Updates
VS Code ships monthly releases and supports auto-update when a new release is available. If you're prompted by VS Code, accept the newest update and it will be installed (you won't need to do anything else to get the latest bits).

Note: You can disable auto-update if you prefer to update VS Code on your own schedule.

Windows Subsystem for Linux
Windows is a popular operating system and it can be a great cross-platform development environment. This section describes cross-platform features such as the Windows Subsystem for Linux (WSL) and the new Windows Terminal.

Recent Windows build
Make sure you are on a recent Windows 10 build. Check Settings > Windows Update to see if you are up-to-date.

Windows as a developer machine
With WSL, you can install and run Linux distributions on Windows. This enables you to develop and test your source code on Linux while still working locally on your Windows machine.

When coupled with the WSL extension, you get full VS Code editing and debugging support while running in the context of WSL.

See the Developing in WSL documentation to learn more or try the Working in WSL introductory tutorial.

New Windows Terminal
Available from the Microsoft Store, the Windows Terminal (Preview) lets you easily open PowerShell, Command Prompt, and WSL terminals in a multiple tab shell.

Next steps
Once you have installed VS Code, these topics will help you learn more about VS Code:

Additional Components - Learn how to install Git, Node.js, TypeScript, and tools like Yeoman.
User Interface - A quick orientation to VS Code.
User/Workspace Settings - Learn how to configure VS Code to your preferences through settings.
Tips and Tricks - Lets you jump right in and learn how to be productive with VS Code.
Common questions
5. Что такое репозиторий и инструкция по созданию локальных репозиториев.
6. Базовая работа с локальным репозиторием
7. Что такое ветки и для чего они нужны при работе с системой контроля версий.
8. Базовая работа с ветками в git.
9. Что такое удаленный репозиторий и для чего он нужен
10. Базовая работа с удаленными репозиториями GitHub
11. Как строится и для чего нужна совместная работа в системах контроля версий
12. Инструкция по созданию pull request
13. Книги и полезные ссылки по изучению git.
14. Альтернативные системы контроля версий.
