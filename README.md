# so71536562

This repo contains two examples of using C# and Antlr4.

* antlr4cs/ is the "Arithmetic" grammar for the old "TunnelVision" fork of Antlr4.

* antlr4/ is the "Arithmetic" grammar for the "official" Antlr4.

### Requirements

* dotnet 6.0
* git
* cd (change directory in Bash, or Cmd)

### Run

```
git clone https://github.com/kaby76/so71536562.git
cd so71536562/antlr4cs
dotnet build
dotnet run -input "1 + 2"
cd ../antlr4
dotnet build
dotnet run -input "1 + 2"
```
