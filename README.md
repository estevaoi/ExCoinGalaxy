# ExCoinGalaxy 

Desafio "Merchant's Guide to Galaxy" implementada em C# com o ASP.NET Core na vers�o 0.1.

![Alt text](Screenshot_ExCoinGalaxy.jpg "ExCoin Galaxy")


## Requisitos

[Angular CLI](https://github.com/angular/angular-cli) vers�o 1.7.0.
[NodeJS](https://nodejs.org/en/) vers�o 8.12 LTS.
[.Net Core](https://www.microsoft.com/net/download/dotnet-core/2.1) vers�o 2.1.

## Executando a Aplica��o

Primeiro ser� necess�rio navegar para a pasta **ExCoinGalaxy**, depois fazer o *restore* dos pacotes e o *publish* da solu��o.

```sh
$ cd Console
/Console$ dotnet restore
/Console$ dotnet publish -o bin
```
Ap�s os comandos acima terem sido executados o build ser� gerado na pasta **bin**.

Para executar a aplica��o basta chamar a DLL ExCoinGalaxy informando o path do arquivo de entrada.

```sh
/Console$ dotnet ./bin/Debug/netcoreapp2.1/ExCoinGalaxy.dll
```