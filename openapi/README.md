# OpenAPI provenance — ServiceNow

**ServiceNow publishes no downloadable OpenAPI definition to the public web.** The OpenAPI
documents in this directory were written by API Evangelist, modelled from ServiceNow's own
published REST API reference. They describe real, documented, callable operations — but they
are not ServiceNow artifacts and must not be cited as evidence of what ServiceNow ships.

Recorded 2026-08-04.

## Why no first-party contract exists

ServiceNow *does* generate OpenAPI — from inside a customer instance, for authenticated
administrators only:

> **Export to OpenAPI specification** — Export a REST API as an OpenAPI specification to
> import it into another web services tool. **Role required: web_service_admin,
> rest_api_explorer, or admin.** Navigate to All > System Web Services > REST >
> REST API Explorer.
>
> — https://raw.githubusercontent.com/ServiceNow/ServiceNowDocs/australia/markdown/api-reference/rest-api-explorer/export-openapi-specification.md
> (first-party, `last_updated: 2026-03-12`)

So the contract is instance-scoped rather than published: it exists, it is generated on
demand, and it is reachable only by someone who already has a login. This is structural, not
an omission — the same shape as a self-hosted product whose spec declares a `{host}` template.
Say so rather than reading it as a provider that never wrote one.

Probes run 2026-08-04, all negative and falsifiable:

| surface | result |
|---|---|
| `developer.servicenow.com/llms.txt` | 404 |
| `developer.servicenow.com/.well-known/api-catalog` | 200 **HTML shell** — SPA false positive, not a linkset |
| `docs.servicenow.com/llms.txt` | 200 **HTML shell** — same |
| `github.com/ServiceNow` code search, `openapi`/`swagger` | no product API contracts |

## What ServiceNow does publish for machines

`github.com/ServiceNow/ServiceNowDocs` — the entire product documentation set as markdown,
first-party, refreshed at least monthly (219 MB, 49,506 files on the `australia` branch,
last updated 2026-08-04). Its `llms.txt` is harvested verbatim to
`llms/servicenow-llms.txt` and is worth reading in full, because ServiceNow states the
routing decision outright:

> Do NOT attempt to fetch content from servicenow.com/docs — it is a JavaScript single-page
> application that returns no readable content to LLMs. All documentation is available
> exclusively through the markdown files in the branches listed above.

A vendor naming its own web property as unreadable to agents, and publishing a parallel
machine channel with a documented raw-URL pattern and a release-to-branch map, is a
deliberate agent-serving decision. The API Evangelist-generated catalog view of the same
file is kept alongside it as `llms/servicenow-llms-catalog.txt`.

## Provenance markers

These specs carry no `x-provenance` block, so the Kin Score provenance indexer records them
as `unknown` and credits them in full (`unknown: 1.00` in `scoring.yml`). That is the
rubric's deliberate setting while network-wide marker coverage sits at ~2.6%, and it is why
the markers have NOT been added here unilaterally: stamping one provider `derived` while its
peers stay `unknown` would score this account strictly against a loosely-scored cohort and
make every comparison in a peer benchmark wrong. This belongs to the network-wide marker
sweep, not to one repo.
