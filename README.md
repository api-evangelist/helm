# Helm (helm)
Package manager for Kubernetes that helps you define, install, and upgrade complex Kubernetes applications using charts. Helm uses a packaging format called charts, which are collections of files that describe a related set of Kubernetes resources. A chart repository is an HTTP server that houses an index.yaml file and packaged chart archives.

**URL:** [Visit APIs.json URL](https://helm.sh)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Kubernetes, Package Manager, DevOps, Container Orchestration, Charts, Cloud Native

## Timestamps

- **Created:** 2025 
- **Modified:** 2026-03-18 

## APIs

### Helm Chart Repository API
The Helm Chart Repository API defines the HTTP endpoints used by Helm clients to discover and download charts from a repository server. This includes the index.yaml endpoint for chart discovery and chart package download endpoints. ChartMuseum extends this with a JSON-based management API for listing, uploading, and deleting charts.

**Human URL:** [https://helm.sh/docs/topics/chart_repository/](https://helm.sh/docs/topics/chart_repository/)


#### Tags:

 - Charts, Repository, Package Registry

#### Properties

- [OpenAPI](openapi/helm-chart-repository-openapi.yml)
- [Documentation](https://helm.sh/docs/topics/chart_repository/)
- [JSONSchema](json-schema/helm-repository-index-schema.json)

### Helm Chart.yaml Schema
JSON Schema defining the structure and validation rules for Chart.yaml, the metadata file required in every Helm chart. Describes chart name, version, dependencies, maintainers, and other metadata fields.

**Human URL:** [https://helm.sh/docs/topics/charts/#the-chartyaml-file](https://helm.sh/docs/topics/charts/#the-chartyaml-file)


#### Tags:

 - Schema, Chart Metadata, Validation

#### Properties

- [JSONSchema](json-schema/helm-chart-yaml-schema.json)
- [Documentation](https://helm.sh/docs/topics/charts/#the-chartyaml-file)

### Helm Values YAML Schema
JSON Schema describing common conventional patterns for values.yaml files in Helm charts. Values.yaml provides default configuration values including container image settings, service configuration, ingress rules, resource limits, and scheduling constraints.

**Human URL:** [https://helm.sh/docs/chart_template_guide/values_files/](https://helm.sh/docs/chart_template_guide/values_files/)


#### Tags:

 - Schema, Configuration, Values

#### Properties

- [JSONSchema](json-schema/helm-values-yaml-schema.json)
- [Documentation](https://helm.sh/docs/chart_template_guide/values_files/)

### Helm Repository Index Schema
JSON Schema for the index.yaml file served by Helm chart repositories. The index is the primary discovery mechanism listing all available charts and versions with download URLs and integrity digests.

**Human URL:** [https://helm.sh/docs/topics/chart_repository/#the-index-file](https://helm.sh/docs/topics/chart_repository/#the-index-file)


#### Tags:

 - Schema, Repository Index, Discovery

#### Properties

- [JSONSchema](json-schema/helm-repository-index-schema.json)
- [Documentation](https://helm.sh/docs/topics/chart_repository/#the-index-file)

### Helm JSON-LD Context
JSON-LD context document mapping Helm concepts to linked data vocabularies including Schema.org, Dublin Core, SPDX, FOAF, and W3C PROV. Enables semantic interoperability of Helm chart metadata.

**Human URL:** [https://helm.sh/docs/](https://helm.sh/docs/)


#### Tags:

 - Linked Data, Semantics, JSON-LD

#### Properties

- [JSON-LD](json-ld/helm-context.jsonld)

### Helm Go SDK
The Helm Go SDK provides Go packages for programmatically performing Helm actions such as install, upgrade, list, and rollback without using the CLI. The SDK is published as helm.sh/helm/v3 and provides a stable API surface for tooling that embeds Helm functionality.

**Human URL:** [https://helm.sh/docs/v3/sdk/gosdk/](https://helm.sh/docs/v3/sdk/gosdk/)


#### Tags:

 - Go, SDK, Kubernetes, Package Manager

#### Properties

- [Documentation](https://helm.sh/docs/v3/sdk/gosdk/)
- [Reference](https://pkg.go.dev/helm.sh/helm/v3)
- [GitHubRepository](https://github.com/helm/helm)

### Helm Plugins
The Helm Plugins API defines the interface for extending the Helm CLI with additional subcommands. Plugins live in a single directory with a plugin.yaml descriptor and can be implemented as shell scripts, binaries, or WebAssembly modules introduced in Helm 4.

**Human URL:** [https://helm.sh/docs/topics/plugins/](https://helm.sh/docs/topics/plugins/)


#### Tags:

 - Plugins, Extensions, CLI, Kubernetes

#### Properties

- [Documentation](https://helm.sh/docs/topics/plugins/)
- [Reference](https://helm.sh/docs/plugins/developer/)
- [JSONSchema](json-schema/helm-plugin-schema.json)

### Helm Chart Template API
The Helm Chart Template API defines the Go template language extensions, built-in objects, and Sprig function library available for authoring Helm chart templates. Templates render Kubernetes manifests from parameterized values and support flow control, named templates, and over 60 template functions.

**Human URL:** [https://helm.sh/docs/chart_template_guide/](https://helm.sh/docs/chart_template_guide/)


#### Tags:

 - Charts, Templates, Go Templates, Kubernetes

#### Properties

- [Documentation](https://helm.sh/docs/chart_template_guide/)
- [Reference](https://helm.sh/docs/chart_template_guide/function_list/)

## Common Properties

- [JSON-LD](json-ld/helm-context.jsonld)
- [JSONSchema](json-schema/helm-plugin-schema.json)
- [Website](https://helm.sh/)
- [Documentation](https://helm.sh/docs/)
- [Getting Started](https://helm.sh/docs/intro/quickstart/)
- [GitHub Organization](https://github.com/helm)
- [GitHubRepository](https://github.com/helm/helm)
- [Blog](https://helm.sh/blog/)
- [Change Log](https://helm.sh/docs/changelog/)
- [Community](https://helm.sh/community/)
- [Slack](https://kubernetes.slack.com/messages/helm-users)
- [Security](https://helm.sh/community/SECURITY)
- [ArtifactHub](https://artifacthub.io/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
