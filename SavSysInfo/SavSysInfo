Imports Microsoft.Win32
Imports System.Management
Imports System


'This class file was written by Steven Houldey.
'I can not be held responsible for any damege or effects to your program or computers by using these files, 
'or any other system file created by myself!

Public Class SavSystem

    ' Ok Lets get some basic info and return some information in an array 
    Public Function GetSystemInfo()


        Dim SavSysCompName As String = My.Computer.Name
        Dim SavSysOS As String = My.Computer.Info.OSFullName
        Dim SavSysOSVer As String = My.Computer.Info.OSVersion
        Dim SavSysPlatform As String = My.Computer.Info.OSPlatform
        Dim SavSysPhysMem As String = My.Computer.Info.TotalPhysicalMemory
        Dim SavSysVerMem As String = My.Computer.Info.TotalVirtualMemory

        Dim SavSystemInfo() As String = {SavSysCompName, SavSysOS, SavSysOSVer, SavSysPlatform, SavSysPhysMem, SavSysVerMem}

        Return SavSystemInfo

    End Function

End Class
