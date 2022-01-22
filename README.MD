# CoffeApp

## Documentação do programa.

#### Para executar o dotnet em ambiente Ubuntu 20.04

Abra um terminal e execute os seguintes comandos:

~~~
wget https://packages.microsoft.com/config/ubuntu/21.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
rm packages-microsoft-prod.deb
~~~

#### Instalar o SDK
O SDK do .NET permite que você desenvolva aplicativos com o .NET. Se você instalar o SDK do .NET, não precisará instalar o runtime correspondente. Execute os seguintes comandos:

~~~
sudo apt-get update; \
  sudo apt-get install -y apt-transport-https && \
  sudo apt-get update && \
  sudo apt-get install -y dotnet-sdk-6.0
~~~

#### Instalar o runtime
O ASP.NET Core Runtime permite executar aplicativos que foram feitos com o .NET que não forneceram o runtime. Os comandos a seguir instalam o ASP.NET Core Runtime, que é o runtime mais compatível para o .NET. Execute os seguintes comandos:

~~~
sudo apt-get install -y dotnet-runtime-6.0
~~~

Acesse o diretório ... [...\coffeeapi\CoffeeApi] e execute o comando:

~~~
dotnet run
~~~

O projeto vai ser carregado na URL: <http://localhost:5166>







#####Desenvolvido por:
* Cleomar Schmitzhaus
* Régis Tomkiel