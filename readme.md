<Linux-surface pro2-setup>
Terminal:
 download the script from http
 $ wget https://dot.net/v1/dotnet-install.sh -O dotnet-install.sh

 set permission to run script as executable
 $ chmod +x ./dotnet-install.sh

 install the latest SDK version
 $ ./dotnet-install.sh --version latest

 install .NET runtime
<linux-setup done>

<login to MS account to start C#>
# search all loaded templates on .NET SDK
> Explorer > Create .NET project > select (e.g. ASP.NET Core Web API) and put in  folder > name project

Terminal:
See available platform to use with this .NET
$ dotnet workload search

Solution Explorer:
 
Add NuGet Package > 
