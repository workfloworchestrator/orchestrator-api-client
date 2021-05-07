# Orchestrator api client generator

Generates a modern Python client from OpenAPI 3.x documents.

> NOTE: this project status is POC
> paging, sort and filter will probably not work on the list endpoint

Under the hood it uses: https://github.com/triaxtec/openapi-python-client to generate a client.

# Log

Created initial client with:

```bash
openapi-python-client generate --url https://YOUR_ORCHESTRATOR_URI/api/openapi.json
```

