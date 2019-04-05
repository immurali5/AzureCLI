# AzureCLI
notes:
# az login
Resource Group 
# az group create --name satya --location westus
V-net
# az network vnet create --resource-group satya --name satya-vnet --subnet-name satya-sub1
Public-ip
# az network public-ip create --resource-group satya --name satya-ip
nsg
# az network nsg create --resource-group satya --name satya-nsg
nic
# az network nic create --resource-group satya --vnet-name satya-vnet --subnet satya-sub1 --public-ip-address satya-ip --network-security-group satya-nsg --name satya-nic

