**Native Shell, a (sort of) command prompt, loaded before the Win32 environment.**

*What is Native Mode?*

The Microsoft docs have a good introduction to native mode (keep in mind, this is 2006) 

> The majority of a native application's runtime environment is provided by NTDLL.DLL, NT's native API export library. Native applications must create their own heap from which to allocate storage by using RtlCreateHeap, a NTDLL function. Memory is allocated from a heap with RtlAllocateHeap and freed with RtlFreeHeap. If a native application wishes to print something to the screen it must use the function NtDisplayString, which will output to the initialization Blue Screen.

*Compiling* 

See Compiling/compile.md

*Running*

1. Copy "native.exe" to your System32 folder (%systemroot%\system32)
2. Run add.reg (or append "native" to `BootExecute` in `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager` )
3. Reboot.
