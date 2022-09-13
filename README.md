# UnoHelloLinux
Your first Uno application on Linux. Dedicated to all Uno-first events in Nigeria 🇳🇬

## Introduction
<a href="https://platform.uno" target="_blank">Uno Platform</a> is the first C# & XAML, free and open-source platform for creating true single-source, multi-platform applications. With Uno Platform, you can empower your existing .NET teams to reuse 99% of the business logic and UI layer to target native mobile, web, and desktop platorms from any development environment — including Linux.

## Getting started
<a href="https://dotnetfoundation.org/" target="_blank">.NET Foundation</a> projects are well maintained, easy to adopt, and have great documentation. However, developers who primarily work on a Linux environment might find it daunting to take advantage of .NET cross-platform offerings. <a href="https://platform.uno" target="_blank">Uno Platform</a> aims to close this barrier.

## Prerequisites
Before continuing to run this project on your Linux distro, there are a few programs you should have up and running on your machine:
- <a href="https://dotnet.microsoft.com/en-us/download" target="_blank">.NET SDK for Linux</a>
- <a href="https://code.visualstudio.com" target="_blank">Visual Studio Code</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=unoplatform.vscode" target="_blank">Uno Platform extension, VS Code</a>

For more information, visit the <a href="https://platform.uno/docs/articles/get-started-with-linux.html?tabs=ubuntu1804%2Cwindows" target="_blank">Additional setup for Linux or WSL guide</a>.

## Requirements
- Fork the <a href="https://github.com/davidconoh/UnoHelloLinux" target="_blank">UnoHelloLinux GitHub repo</a> to your GitHub account.
- Clone on your local machine: Replace `yourusername` with your GitHub username
  ```
  git clone https://github.com/yourusername/UnoHelloLinux.git
  ```
- These are the files relevant for the current project:
  ```
  .
  ├── .vscode       # directory
  ├── UnoHelloLinux.Shared      # directory
  ├── UnoHelloLinux.Skia.Gtk
  │   ├── Assets   # directory
  │   ├── bin      # directory
  │   ├── obj      # directory
  │   ├── app.manifest
  │   ├── Program.cs
  │   └── UnoHelloLinux.Skia.Gtk.csproj
  ├── .vsconfig     # directory
  ├── README.md
  ├── UnoHelloLinux-vsmac.slnf
  ├── UnoHelloLinux.sln
  └── UnoSolutionTemplate.net6.csproj
  ```
- Open with VS Code
  ```
  cd UnoHelloLinux
  code .
  ```
- Open a new Terminal in VS Code. You are looking for the `Skia.Gtk` folder:
  - Enter the directory
    ```
    cd UnoHelloLinux.Skia.Gtk
    ```
  - Run the application
    ```
    dotnet run
    ```


## License
Licensed under the Apache License, Version 2.0. See <a href="https://github.com/davidconoh/UnoHelloLinux/blob/main/LICENSE" target="_blank">here</a>

## Limitations
The `uno-check` command fails on Fedora 36. The current version of .NET SDK 6 on 
Fedora 36 is `6.0.100`, and the required is `6.0.400`. Let me know if you find a work around. 

## Author
- <a href="https://github.com/davidconoh" target="_blank">Chika Onoh</a>

## Version
```
Version: 0.0.1
```
