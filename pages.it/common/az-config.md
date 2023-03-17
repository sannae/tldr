# az config

> Gestisce la configurazione della Azure CLI.
> Parte di `azure-cli`.
> Più informazioni: <https://learn.microsoft.com/cli/azure/config>.

- Mostra tutte le configurazioni:

`az config get`

- Mostra le configurazioni per una specifica sezione:

`az config get {{section_name}}`

- Imposta una configurazione:

`az config set {{configuration_name}}={{value}}`

- Ripristina una configurazione:

`az config unset {{configuration_name}}`
