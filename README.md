***I'm done with OSED soon!! I've made this repository in order to share some of my useful knowledge, methods, techniques and tools regarding Windows kernel-mode exploitation. Currently I'm taking a course called Windows Kernel Exploitation Professional(WKEP) by a local instructor, so the resources I've used are the mentioned course and hours of personal research and effort.***

_________________________________________________________________________________________________________________________________________________________________________

**PDB files:** 

Program database (PDB) is a file format (developed by Microsoft) for storing debugging information about a program (or, commonly, program modules such as a DLL or EXE). PDB files commonly have a .pdb extension. A PDB file is typically created from source files during compilation. pdb file holds debugging and project state information that allows incremental linking of a Debug configuration of your app. 

Some tools used to parse PDB files and structures and gathering useful info from them: 

**pdbex:** https://github.com/wbenny/pdbex

- Usage: 
>pdbex.exe _SID ntdll.pdb


**PDBRipper:** https://github.com/horsicq/PDBRipper

- Usage: Has a GUI and is very easy to use.

