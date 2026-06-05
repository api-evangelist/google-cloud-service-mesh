# Google Cloud Service Mesh (google-cloud-service-mesh)

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
