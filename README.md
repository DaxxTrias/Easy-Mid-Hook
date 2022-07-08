![Project Banner](https://user-images.githubusercontent.com/48086737/178064575-e12e1a25-49db-4a93-898d-53f4f0571e37.png)

# Easy Mid Hook

[![C++](https://img.shields.io/badge/language-C%2B%2B-%23f34b7d.svg?style=for-the-badge&logo=appveyor)](https://en.wikipedia.org/wiki/C%2B%2B) [![Windows](https://img.shields.io/badge/platform-Windows-0078d7.svg?style=for-the-badge&logo=appveyor)](https://en.wikipedia.org/wiki/Microsoft_Windows) [![x64](https://img.shields.io/badge/arch-x64-green.svg?style=for-the-badge&logo=appveyor)](https://en.wikipedia.org/wiki/X64)

## :open_book: Project Overview :

This template teach you and help you how to easily create x64 mid hook in C++ using [MS Detours](https://github.com/microsoft/Detours) and seperate ASM file, since inline ASM is not available in x64.

The code cave permit to execute new instructions in the middle of a function, the hook will redirect the flow into our new code then jump back to the original function, this is very useful for game hacking.

This project also show you how to exchange datas between you C++ code and your ASM code.

#### Used librairies :

- [MS Detours](https://github.com/microsoft/Detours)

The project include a test executable to see how it works.

## :rocket: Getting Started :

[MS Detours](https://github.com/microsoft/Detours) is already setup and include in the project.

This is a **x64 executable / DLL**, you can't compile this project in x86, we are using x64 assembly.

### Visual Studio :

1. Open the solution file (.sln).
2. Build the project in Debug (x64)

⚠️ If the hook do not works you should check if the address is good if you recompiled, else you can test with test files in the Release section.

## 🧪 Demonstration :

https://user-images.githubusercontent.com/48086737/166695158-98c3f033-93c0-481e-9ad1-a3252b05ec29.mp4
