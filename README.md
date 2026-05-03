# Upbound

Upbound is a universal cloud platform built on Crossplane, providing managed control planes and a marketplace for cloud infrastructure APIs. The Upbound API enables programmatic management of organizations, spaces, control planes, package repositories, teams, and robot accounts for CI/CD automation.

**Website:** https://www.upbound.io
**Documentation:** https://docs.upbound.io
**Marketplace:** https://marketplace.upbound.io

## APIs

| API | Description |
|---|---|
| [Upbound API](openapi/upbound-openapi.yml) | Core platform API for organizations, control planes, repositories, teams, and robots |

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [upbound-openapi.yml](openapi/upbound-openapi.yml) | Upbound Cloud API covering organizations, control planes, repositories, teams, and robots |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [upbound-rules.yml](rules/upbound-rules.yml) | Spectral ruleset enforcing Upbound API conventions including path naming, auth, and response structure |

## Naftiko Capabilities

### Shared Definitions

| File | APIs Covered |
|---|---|
| [shared/upbound.yaml](capabilities/shared/upbound.yaml) | Upbound Cloud API (organizations, control planes, repos, robots) |

### Workflow Capabilities

| Workflow | Description | Tools |
|---|---|---|
| [platform-engineering.yaml](capabilities/platform-engineering.yaml) | End-to-end platform engineering — org management, control plane lifecycle, repositories, teams, and CI/CD robots | 12 tools |

## JSON Schemas

| Schema | Description |
|---|---|
| [upbound-control-plane-schema.json](json-schema/upbound-control-plane-schema.json) | Managed Crossplane control plane resource |

## JSON Structure

| Structure | Description |
|---|---|
| [upbound-control-plane-structure.json](json-structure/upbound-control-plane-structure.json) | Field-level documentation for the Control Plane resource |

## JSON-LD

| Context | Description |
|---|---|
| [upbound-context.jsonld](json-ld/upbound-context.jsonld) | Linked data context mapping Upbound resources to schema.org |

## Examples

| Example | Description |
|---|---|
| [upbound-list-control-planes-example.json](examples/upbound-list-control-planes-example.json) | GET /organizations/{org}/controlplanes response |
| [upbound-create-control-plane-example.json](examples/upbound-create-control-plane-example.json) | POST /organizations/{org}/controlplanes request and response |

## Vocabulary

| File | Description |
|---|---|
| [upbound-vocabulary.yml](vocabulary/upbound-vocabulary.yml) | Domain vocabulary for Upbound and Crossplane platform engineering concepts |

## Links

- **Website:** https://www.upbound.io
- **Documentation:** https://docs.upbound.io
- **Marketplace:** https://marketplace.upbound.io
- **GitHub Organization:** https://github.com/upbound
- **Crossplane:** https://www.crossplane.io

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
