## Guide (not completed)

- Registry keys have history for exes. NO KIDDING, THERE'S A LOT OF REGISTRY TO DELETE(Will implement it in the external)
- Prefetch
- I like to hide my externals in C:\windows\setup\files and configs C:\Windows\Setup\State has to be .ini
---
# Registry keys to delete
1. HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\TypedPaths
2. Computer\HKEY_CURRENT_USER\Software\Classes\Local Settings\MrtCache
3. Computer\HKEY_CURRENT_USER\Software\Classes\Local Settings\MuiCache
4. Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Compatibility Assistant\Store -- When I found this, I managed to delete A Rat in my computer
5. Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Layers -- Program execution flags/ RUNASADMIN Compatibility shims on unknown EXEs
6. Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Compatibility Assistant\Persisted
7. HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\BAM -- Background Activity Moderator (BAM) 
8. HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\DAM -- Desktop Activity Moderator (DAM)
9. Computer\HKEY_CURRENT_USER\Software\WinRAR\ArcHistory -- IF YOU HAVE WINRAR
10. Computer\HKEY_CURRENT_USER\Software\WinRAR\DialogEditHistory\ArcName -- WINRAR
11. Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\RADAR\HeapLeakDetection\DiagnosedApplications 
12. Computer\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\bam\State\UserSettings -- just bam but different its just because of your os being custom
13. Computer\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\dam --  just Dam but different its just because of your os being custom
14. Computer\HKEY_CURRENT_USER\Control Panel\NotifyIconSettings -- This stores system tray (notification area) icon history. 

--

# FOLDERS

1. C:\windows\Prefetch

--




