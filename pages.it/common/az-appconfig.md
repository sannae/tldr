# az appconfig

> Gestisce la configurazione di App su Azure.
> Parte di `az`, il client a riga di comando per Microsoft Azure.
> Più informazioni: <https://learn.microsoft.com/cli/azure/appconfig>.

- Creare una configurazione di App:

`az appconfig create --name {{name}} --resource-group {{group_name}} --location {{location}}`

- Rimuovere una configurazione di App:

`az appconfig delete --resource-group {{rg_name}} --name {{appconfig_name}}`

- Elencare tutte le configurazioni di App sotto la sottoscrizione corrente:

`az appconfig list`

- Elencare tutte le configurazioni di App in uno specifico gruppo di risorse:

`az appconfig list --resource-group {{rg_name}}`

- Mostrare le proprietà di una configurazione di App:

`az appconfig show --name {{appconfig_name}}`

- Aggiornare una specifica configurazione di App:

`az appconfig update --resource-group {{rg_name}} --name {{appconfig_name}}`