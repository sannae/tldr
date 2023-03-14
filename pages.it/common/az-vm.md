# az vm

> Gestisce le macchine virtuali in Microsoft Azure.
> Parte di `azure-cli`.
> Più informazioni: <https://learn.microsoft.com/cli/azure/vm>.

- Elenca i dettagli delle macchine virtuali disponibili:

`az vm list`

- Crea una macchina virtuale usando l'immagine predefinita di Ubuntu e genera le chiavi SSH:

`az vm create --resource-group {{rg}} --name {{vm_name}} --image {{UbuntuLTS}} --admin-user {{azureuser}} --generate-ssh-keys`

- Arresta una macchina virtuale:

`az vm stop --resource-group {{rg}} --name {{vm_name}}`

- Dealloca una macchina virtuale:

`az vm deallocate --resource-group {{rg}} --name {{vm_name}}`

- Avvia una macchina virtuale:

`az vm start --resource-group {{rg}} --name {{vm_name}}`

- Riavvia una macchina virtuale:

`az vm restart --resource-group {{rg}} --name {{vm_name}}`

- Elenca le immagini di macchine virtuali disponibili nell'Azure Marketplace:

`az vm image list`
