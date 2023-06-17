This program is written to fix a problem with the Maltron keyboard I'm currently using, where the keys are randomly typed twice for Korean keys.

The program is a simple prototype that drops the duplicate keys if each key is typed in succession in less than 40ms.

The program works on Windows OS and was compiled in Visual Studio to verify that it works.

To compile this program,
1. simply make a Windows Applicatiotn project using Microsoft Visual Studio.
2. copy main.cpp code to project main cpp file.
3. change "Character set" to "no" in Project Properties in the menu.
4. to enable using IME, add imm32.lib to Linker -> Additional Dependency in  Project Properties in the menu.
5. compile project
