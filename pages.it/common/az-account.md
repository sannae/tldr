# az account

> Permette di gestire le informazioni della sottoscrizione di Azure.
> Parte di `az`, il client a riga di comando per Microsoft Azure.
> Più informazioni: <https://learn.microsoft.com/cli/azure/account>.

- Lista le sottoscrizioni per l'account connesso:

`az account list`

- Imposta una specifica sottoscrizione come attiva: 

`az account set --subscription {{subscription_id}}`

- Lista le regioni supportate per la sottoscrizione attiva:

`az account list-locations`

- Ottiene un Access Token da usare con `MS Graph API`:

`az account get-access-token --resource-type {{ms-graph}}`

- Mostra i dettagli della sottoscrizione attiva in uno specifico formato:

`az account show --output {{json|tsv|table|yaml}}`
