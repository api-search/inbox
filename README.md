# APIs.io Inbox

This is where you ask us to change what [APIs.io](https://apis.io) says about your API.

APIs.io indexes public APIs and scores them with the [Kin Score](https://apis.io/rating/). We build every profile from what a provider publishes — OpenAPI, AsyncAPI, `llms.txt`, MCP manifests, docs, pricing. When we get it wrong, or when you have published something new that we have not picked up, open an issue here and we will fix it.

## What to open an issue for

| I want to… | Use |
|---|---|
| Get my API listed | [Add an API](../../issues/new?template=add-api.yml) — or use the [add form](https://apis.io/add/), which is faster |
| Get rescored after publishing new artifacts | [Rescore or reindex](../../issues/new?template=rescore.yml) |
| Fix something wrong on my profile | [Correct a profile](../../issues/new?template=correct.yml) |
| Be removed from the catalog | [Delist](../../issues/new?template=delist.yml) |

**If your API is already listed**, you can also open an issue directly on your own provider repo under [github.com/api-evangelist](https://github.com/orgs/api-evangelist/repositories) — every listed provider has one, and that is the best place for anything specific to your profile.

## What helps us move fast

Point us at machine-readable sources rather than describing them. A URL to an OpenAPI, an `llms.txt`, an `apis.json`, or a reachable MCP endpoint is worth more than a paragraph, because it is what the pipeline actually reads.

We do not charge to list, correct, or rescore an API. Scores are derived from published evidence — we will not adjust one without a source behind it.

## Response

We work this queue on a regular cadence. Rescores land on the next catalog build after the fix.
