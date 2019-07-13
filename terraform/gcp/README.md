## Setup

1. Create services account that has 'editor' role on your GCP Project.
2. Download its services account's JSON
3. Rename the JSON File and place to ~/.terraform/gcp_sa_credential.json

As you finished setup, execute terraform command by docker-compose.

```console
$ docker-compose run --rm terraform init
```
