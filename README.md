#Install-Module -Name Az -AllowClobber -Scope CurrentUser
#Get-InstalledModule -Name Az -AllVersions | select Name,Version

#Set-ExecutionPolicy -ExecutionPolicy AllSigned -Scope CurrentUser

#Import-Module Az.Accounts

#Connect-AzAccount

#New-AzVm -ResourceGroupName "az301" -Name "mywinvm" -Location "eastus" -VirtualNetworkName "myvnetwork1" -SecurityGroupName "newsg" -PublicIpAddressName "myipaddr" -SubnetName "default" -OpenPorts 80,443,3389 

#New-AzResourceGroupDeployment -Name "mynpbsa2" -ResourceGroupName "az-300" -TemplateFile ".\template.json"
