Privesc from low-privileged user to NT-AUTORITY\SYSTEM


The rubber ducky script will :

* Disable AV

* Download LocalPotato

* Download SprintCSP.dll that will open a command prompt with NT-AUTORITY\SYSTEM privileges

* Copy SprintCSP.dll to C:\Windows\System32\ using LocalPotato

* Download RpcClient.exe

* Run RpcClient.exe that will trigger the DLL


To do :

* Add a slow version for slow computers and test it.

* Add a privesc version from Administrator to NT-AUTORITY\SYSTEM
