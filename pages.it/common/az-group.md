# az group

> Gestisce i gruppi di risorse.
> Parte di `azure-cli`.
> Più informazioni: <https://docs.microsoft.com/cli/azure/group>.

- Crea un nuovo gruppo di risorse:

`az group create --name {{name}} --location {{location}}`

- Verifica se uno specifico gruppo di risorse esiste:

`az group exists --name {{name}}`

- Cancella un gruppo di risorse:

`az group delete --name {{name}}`

- Attendi finché si verifica una specifica condizione del gruppo di risorse:

`az group wait --name {{name}} --{{created|deleted|exists|updated}}`