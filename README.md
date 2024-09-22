# Basic Dotnet Projects [![GitHub](https://img.shields.io/github/license/anveshmuppeda/basic-dotnet-projects?color=blue)](https://github.com/anveshmuppeda/basic-dotnet-projects/blob/main/LICENSE)


## Versioning: 
* 4 -> dotnet  
* After 4 all are dotnet code which is from 5  

## Version  
```console
dotnet --version
```  

## Dotnet Installer   
```console
https://dotnet.microsoft.com/en-us/download
```  

## To create new project  
```console
dotnet new console -n <project-name>
```  

##  Create a Solution file  
```console
dotnet new sln -n <sln-filename>
```  

## Adding new project to a solution file   
```console
dotnet sln <filename.sln> add <project-name>
```  

## To Build   
```console
dotnet build
```  

## To restore  
```console
dotnet restore
```  

## To run    
```console 
# Run within project folder
dotnet run 

# Run outside project
dotnet run --project <project-name>
```  

## To add a reference between two projects   
```console
dotnet add hello-world reference echo-hello-world
```  

## Project Maintainers & Contributors  
<table>
  <tr>
    <td align="center"><a href="https://anveshmuppeda.github.io/profile/"><img src="https://avatars.githubusercontent.com/u/115966808?v=4" width="100px;" alt=""/><br /><sub><b>Anvesh Muppeda</b></sub></a></td>
    <td align="center"><a href="https://github.com/saimanasak"><img src="https://avatars.githubusercontent.com/u/47205414?v=4" width="100px;" alt=""/><br /><sub><b>Sai Manasa Kota</b></sub></a></td>
    <td align="center"><a href="https://github.com/khajjayamteja"><img src="https://avatars.githubusercontent.com/u/151116058?v=4" width="100px;" alt=""/><br /><sub><b>Teja Sai Srinivas</b></sub></a></td>
  </tr>
</table>  