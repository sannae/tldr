# az lock

> Gestisce i blocchi di Azure.
> Parte di `azure-cli`.
> Più informazioni: <https://learn.microsoft.com/cli/azure/lock>.

- Creare un blocco di sola lettura a livello di sottoscrizione:

`az lock create --name {{lock_name}} --lock-type ReadOnly`

- Creare un blocco di sola lettura a livello di gruppo di risorse:

`az lock create --name {{lock_name}} --resource-group {{group_name}} --lock-type ReadOnly`

- Cancellare un blocco a livello di sottoscrizione:

`az lock delete --name {{lock_name}}`

- Cancellare un blocco a livello di gruppo di risorse:

`az lock delete --name {{lock_name}} --resource-group {{group_name}}`

- Elenca tutti i blocchi a livello di sottoscrizione:

`az lock list`

- Mostra un blocco a livello di sottoscrizione:

`az lock show -n {{lock_name}}`
