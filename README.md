***I'll be done with OSED soon!! I've made this repository in order to share some of my useful knowledge, methods, techniques and tools regarding Windows kernel-mode exploitation. Currently I'm taking a course called Windows Kernel Exploitation Professional(WKEP) by a local instructor, so the resources I've used are the mentioned course and hours of personal research and effort.***

_________________________________________________________________________________________________________________________________________________________________________
Awsome book recommendations that help mastering Windows architecture: 
- Windows kernel programming by the legend himself(Pavel Yosifovich)
- Windows 10 programming pt. 1 by Pavel Yosifovich
- Windows 10 programming pt. 2 by Pavel Yosifovich

Useful links that I've found so far:
https://www.geoffchappell.com/studies/windows/km/ntoskrnl/inc/ntos/kpcr.htm
https://github.com/S3cur3Th1sSh1t/Pentest-Tools
_________________________________________________________________________________________________________________________________________________________________________
**PDB files:** 

Program database (PDB) is a file format (developed by Microsoft) for storing debugging information about a program (or, commonly, program modules such as a DLL or EXE). PDB files commonly have a .pdb extension. A PDB file is typically created from source files during compilation. pdb file holds debugging and project state information that allows incremental linking of a Debug configuration of your app. 

Some tools used to parse PDB files and structures and gathering useful info from them: 

**pdbex:** https://github.com/wbenny/pdbex

- Usage: 
>pdbex.exe _SID ntdll.pdb

**symChk:** https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/symchk-command-line-options
- Usage: 
>symchk /r c:\windows\system32\[filename] /s SRV*c:\symbols\*http://msdl.microsoft.com/download/symbols

Dia2dump(parse pdb files): The Dia2dump sample shows how to use the Microsoft Debug Interface Access Software Development Kit (DIA SDK) to query a PDB file for information. The Dia2dump sample is installed with Visual Studio and contains the solution and source files. The compiled executable runs from the command line. It can display the contents of an entire program database (.pdb) file, or just the sections you're interested in.

**PDBRipper:** https://github.com/horsicq/PDBRipper

- Usage: Has a GUI and is very easy to use.
_____________________________________


