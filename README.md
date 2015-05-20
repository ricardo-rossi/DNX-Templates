# DNX-Templates

## Pre-Requisites

(DNX)[https://github.com/aspnet/home]
(Mono 4.*)[http://www.mono-project.com/download/]

## Setup

Add this to your .bash_profile to get around an issue:   

`export MONO_MANAGED_WATCHER=disabled`   

kqueue() FileSystemWatcher has reached the maximum nunmber of files to watch:   
https://github.com/OmniSharp/generator-aspnet/issues/138

## Running the templates

### ConsoleApplication

```
cd ConsoleApplication   
dnu restore (first time only)    
dnx . run 
```

### WebAPIApplication

```
cd WebAPIApplication   
dnu restore (first time only)    
dnx . web 
```

### WebApplication

```
cd WebApplication   
dnu restore (first time only)    
dnx . kestrel 
```



