To generate the Nuget package:
- Build Release-Net45
- cd to the WhoisParsers\nuget folder
- NuGet.exe Pack WhoisParsers.nuspec -Symbols
- NuGet.exe Push WhoisParsers.X.X.X.nupkg \<API_KEY_HERE\> -Source https://www.nuget.org/api/v2/package
