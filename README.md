# SavSysInfo
SavSysInfo.DLL - Testing .DLL functions in Visual Basic.net

<hr>

I have uploaded the complete project for those that wish to use it and maybe improve it.

To use this .DLL files in Visual Basic, the function returns the values in an Array....  an example is included below.

```
        Dim MySysInfo = New SavSystem

        Dim SysInfo = MySysInfo.GetSystemInfo(1)

        MsgBox(SysInfo)
```

- (0) Displays the computer Name
- (1) OS Full Name
- (2) OS Version Numbers
- (3) OS Platform
- (4) Physical Memory
- (5) Virtual Memory.

<hr>
More will be added very soon!

