# Google Cloud Service Mesh (google-cloud-service-mesh)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Google Cloud Service Mesh is Google's managed service mesh solution for GKE and supported GKE Enterprise environments, enabling secure, observable, and reliable communication between microservices. It provides a managed Istio control plane, Google Cloud-native service routing APIs, mTLS security, and built-in telemetry for distributed applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-cloud-service-mesh/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-cloud-service-mesh/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Google Cloud
- Istio
- Kubernetes
- Microservices
- Service Mesh

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Google Cloud Network Services API

The Network Services API provides programmatic configuration of application networking infrastructure for Cloud Service Mesh. It manages gateways, meshes, HTTP/gRPC/TCP/TLS routes, endpoint policies, service load balancing policies, WebAssembly plugins, and authorization extensions through a REST interface backed by the networkservices.googleapis.com service endpoint.

- **Human URL:** [https://cloud.google.com/service-mesh/docs/reference/network-services/rest](https://cloud.google.com/service-mesh/docs/reference/network-services/rest)
- **Base URL:** `https://networkservices.googleapis.com/`

#### Tags

- Networking
- REST
- Service Mesh
- Traffic Management

#### Properties

- [OpenAPI](openapi/google-cloud-service-mesh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/google-cloud-service-mesh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-cloud-service-mesh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://cloud.google.com/service-mesh/docs/reference/network-services/rest)
- [Reference](https://cloud.google.com/service-mesh/docs/reference/network-services/rest/v1/projects.locations.meshes)
- [Discovery](https://networkservices.googleapis.com/$discovery/rest?version=v1)

### Google Cloud Network Security API

The Network Security API manages security policies for Cloud Service Mesh, including authorization policies, client TLS policies, and server TLS policies. It provides REST endpoints for creating and managing mTLS configuration and fine-grained access control across projects and locations, served from the networksecurity.googleapis.com service endpoint.

- **Human URL:** [https://cloud.google.com/service-mesh/docs/reference/network-security/rest](https://cloud.google.com/service-mesh/docs/reference/network-security/rest)
- **Base URL:** `https://networksecurity.googleapis.com/`

#### Tags

- Authorization
- mTLS
- Security
- Service Mesh

#### Properties

- [Documentation](https://cloud.google.com/service-mesh/docs/reference/network-security/rest)
- [Reference](https://cloud.google.com/service-mesh/docs/reference/network-security/rest/v1/projects.locations.authorizationPolicies)
- [Discovery](https://networksecurity.googleapis.com/$discovery/rest?version=v1)
- [Postman Collection](collections/google-cloud-service-mesh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-cloud-service-mesh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Google Cloud Service Mesh xDS Control Plane API

Cloud Service Mesh uses the open-source xDS v3 control plane API to distribute configuration to Envoy sidecar proxies and proxyless gRPC clients. Configurations defined via the Network Services and Network Security REST APIs are translated and pushed to connected clients through the xDS protocol, supporting Listener Discovery Service (LDS), Route Discovery Service (RDS), Cluster Discovery Service (CDS), and Endpoint Discovery Service (EDS).

- **Human URL:** [https://cloud.google.com/service-mesh/docs/service-routing/xds-control-plane-apis](https://cloud.google.com/service-mesh/docs/service-routing/xds-control-plane-apis)
- **Base URL:** `https://trafficdirector.googleapis.com/`

#### Tags

- Control Plane
- Envoy
- Service Mesh
- xDS

#### Properties

- [Documentation](https://cloud.google.com/service-mesh/docs/service-routing/xds-control-plane-apis)
- [Postman Collection](collections/google-cloud-service-mesh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-cloud-service-mesh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/GoogleCloudPlatform)
- [Website](https://cloud.google.com/service-mesh)
- [Documentation](https://cloud.google.com/service-mesh/docs)
- [Getting Started](https://cloud.google.com/service-mesh/docs/onboarding/provision-control-plane)
- [Reference](https://cloud.google.com/service-mesh/docs/reference/network-services/rest)
- [Pricing](https://cloud.google.com/service-mesh/pricing)
- [Changelog](https://cloud.google.com/service-mesh/docs/release-notes)
- [Support](https://cloud.google.com/service-mesh/docs/getting-support)
- [Security](https://cloud.google.com/service-mesh/docs/security-bulletins)
- [Integrations](https://cloud.google.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
