# Configurar recursos do Azure com ferramentas

## Anderson Bezerra Silva 
Treinamento - AZ-104T00-A Microsoft Azure Administrator (Green Tecnologia)


## 1. Gerenciar recursos com o portal do Azure

- Exemplo de Estudo: Navegue pelo portal do Azure e experimente criar, gerenciar e excluir um recurso básico, como uma máquina virtual (VM).

- Passo a Passo: Acesse o [Portal do Azure](https://portal.azure.com/#home) e familiarize-se com a navegação e os recursos disponíveis para gerenciamento.

- Tarefa Prática: No portal, crie um grupo de recursos e, dentro dele, adicione uma VM. Explore as opções para iniciar, parar e excluir a VM, além de configurar suas propriedades.

## 2. Gerenciar recursos com o Azure Cloud Shell

- Exemplo de Estudo: Utilize o Cloud Shell no portal do Azure para criar um recurso simples, como um armazenamento de blob, usando comandos básicos.

- Passo a Passo: Abra o [Azure Cloud Shell](https://portal.azure.com/#cloudshell/) e selecione Bash ou PowerShell para explorar a interface.

- Tarefa Prática: No Cloud Shell, execute um comando para criar um grupo de recursos:

```bash 
 az group create --name MeuGrupoDeRecursos --location eastus
```

- Em seguida, crie um armazenamento de blob:

```bash 
az storage account create --name MeuStorageBlob --resource-group MeuGrupoDeRecursos --location eastus --sku Standard_LRS
```

## 3. Gerenciar recursos com o Azure PowerShell

 - Exemplo de Estudo: Com o Azure PowerShell, crie um script simples que inicie uma VM e consulte o status do recurso.

- Passo a Passo: Instale o [Azure PowerShell](https://learn.microsoft.com/pt-br/powershell/azure/new-azureps-module-az?view=azps-12.4.0&viewFallbackFrom=azps-latest) e faça login na conta do Azure com o comando:

```ps1 
Connect-AzAccount
```
 - Tarefa Prática: Após o login, execute o seguinte script para criar um grupo de recursos e uma VM:

 ```ps1 
 New-AzResourceGroup -Name MeuGrupoDeRecursos -Location "EastUS"
New-AzVM -ResourceGroupName MeuGrupoDeRecursos -Name MinhaVM -Location "EastUS" -Image Win2019Datacenter -OpenPorts 3389
```
 - Depois, use Get-AzVM para verificar o status da VM.

## 4. Gerenciar recursos com a CLI do Azure

 - Exemplo de Estudo: Utilize a CLI do Azure para criar um banco de dados SQL em um grupo de recursos existente.

 - Passo a Passo: Instale a [CLI do Azure](https://learn.microsoft.com/pt-br/cli/azure/install-azure-cli) e faça login com o comando:

```bash 
az login
```
  - Tarefa Prática: Após o login, crie um grupo de recursos e um banco de dados SQL usando os comandos abaixo:

```bash 
az group create --name MeuGrupoSQL --location eastus
az sql server create --name MeuServidorSQL --resource-group MeuGrupoSQL --location eastus --admin-user adminuser --admin-password MinhaSenhaSegura123
az sql db create --resource-group MeuGrupoSQL --server MeuServidorSQL --name MeuBancoDeDados --service-objective S0
```

 - Isso cria um servidor SQL e um banco de dados dentro dele.
 



