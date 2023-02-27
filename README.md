# terransiwiniis
Scripts terraform + Ansible para criar um Windows Server 2019 na Azure e depois instalar IIS

Pre requisitos
Configurar as variaveis abaixo e instalar e configurar azure-cli (se Linux)
export ARM_CLIENT_ID="CLIENT_ID"
export ARM_CLIENT_SECRET="PASSWORD"
export ARM_SUBSCRIPTION_ID="SUBS"
export ARM_TENANT_ID="TENANT_ID"

export AZURE_CLIENT_ID="CLIENT_ID"
export AZURE_SECRET="PASSWORD"
export AZURE_SUBSCRIPTION_ID="SUBS"
export AZURE_TENANT="TENANT_ID"


Após a criação da VM com o terraform, encontrar a senha do user 'azureuser' na saída do terraform e o IP designado para a VM e configurar em groupvars/windows.yml e no inventario, respectivamente.
