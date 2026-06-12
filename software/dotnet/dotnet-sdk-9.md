## verify install 

PS C:\enterprise-workstation-build> dotnet --version
dotnet : The term 'dotnet' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ dotnet --version
+ ~~~~~~
    + CategoryInfo          : ObjectNotFound: (dotnet:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException



## Install command 
winget install --id Microsoft.DotNet.SDK.9 --source winget



## Sample output
PS C:\Windows\system32> winget install --id Microsoft.DotNet.SDK.9 --source winget
Found Microsoft .NET SDK 9.0 [Microsoft.DotNet.SDK.9] Version 9.0.315
This application is licensed to you by its owner.
Microsoft is not responsible for, nor does it grant any licenses to, third-party packages.
Downloading https://builds.dotnet.microsoft.com/dotnet/Sdk/9.0.315/dotnet-sdk-9.0.315-win-x64.exe
  ██████████████████████████████   220 MB /  220 MB
Successfully verified installer hash
Starting package install...
Successfully installed




# final step verify 

C:\Users\devak>dotnet --version
9.0.315