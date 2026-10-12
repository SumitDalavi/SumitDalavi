# Sumit Dalavi

I build open-source projects around **Kubernetes platforms, cloud-native infrastructure, DevSecOps, and reliability**—and contribute fixes and features upstream.

- [Portfolio case studies](https://sumit-dalavi.is-a.dev)
- [Browse all repositories](https://github.com/SumitDalavi?tab=repositories)

## Upstream contributions

### Merged

- [Argo CD #29627](https://github.com/argoproj/argo-cd/pull/29627) — Fixed CLI wait-condition handling for selected resources. Merged 7 October 2026.
- [OpenTelemetry Collector Contrib #50922](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/50922) — Added delta-temporality aggregation support to the interval processor. Merged 18 September 2026.
- [OpenTelemetry Collector Contrib #50790](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/50790) — Added CI coverage for tests excluded from race-enabled runs. Merged 9 September 2026.

### Open pull requests

- [Argo CD #29601](https://github.com/argoproj/argo-cd/pull/29601) — Proposes a configurable `--max-pending-resources` limit for `app wait`, `sync`, and `rollback`.
- [Argo CD #30083](https://github.com/argoproj/argo-cd/pull/30083) — Improves `app wait` timeout messages with condition summaries and operation details.
- [Kyverno #17506](https://github.com/kyverno/kyverno/pull/17506) — Highlights JMESPath syntax-error locations in `kyverno jp query`.
- [External Secrets Operator #6943](https://github.com/external-secrets/external-secrets/pull/6943) — Adds custom CA support for the Fortanix provider.

PR status can change; use each linked pull request as the source of truth.

## Selected repositories

### Kubernetes and platform engineering

- [Secure Dev Platform Demo](https://github.com/SumitDalavi/secure-dev-platform-demo) — Local integration demo for Kubernetes provisioning, admission control, policy enforcement, and secret rotation.
- [K8s Golden Path Provisioner](https://github.com/SumitDalavi/k8s-golden-path-provisioner) — Kubernetes operator and developer-facing resource model for environment provisioning.
- [K8s Admission Webhook from Scratch](https://github.com/SumitDalavi/k8s-admission-webhook-from-scratch) — Go implementation exploring Kubernetes admission contracts and failure-policy choices.
- [Multi-Cluster GitOps Promotion](https://github.com/SumitDalavi/multi-cluster-gitops-promotion) — Git-based environment promotion and ApplicationSet design.

### Reliability and observability

- [Durable Incident Agent](https://github.com/SumitDalavi/durable-incident-agent) — Incident workflow with approval steps and telemetry-based recovery verification.
- [OpenTelemetry Microservice Demo](https://github.com/SumitDalavi/opentelemetry-microservice-demo) — Distributed tracing and collector-based observability across services.
- [Chaos SLO Gameday](https://github.com/SumitDalavi/chaos-slo-gameday) — Reliability-focused chaos and SLO exercise.

### Security and AI infrastructure

- [Supply Chain Security Pipeline](https://github.com/SumitDalavi/supply-chain-security-pipeline) — Reference workflow for SBOMs, scanning, signing, provenance, and policy gates.
- [Agent Sandbox Platform](https://github.com/SumitDalavi/agent-sandbox-platform) — Container-based execution sandbox with policy checks and explicit cleanup behavior.
- [NHI Agent Access Governance](https://github.com/SumitDalavi/nhi-agent-access-governance) — Prototype for scoped authorization and policy decisions for non-human identities.
- [AI Control Plane Demo](https://github.com/SumitDalavi/ai-control-plane-demo) — Demo combining gateway, identity, caching, routing, guardrails, and evaluation components.

Project descriptions indicate scope; check each repository for its implementation, evidence, and limitations. Prototypes and labs are not presented as production deployments.

## Topics I work on

- Kubernetes operators, platform APIs, and developer workflows.
- GitOps, CI/CD, progressive delivery, and cloud-native security.
- Observability, incident workflows, and failure-aware systems.
- AI infrastructure with explicit policy and execution boundaries.

For project discussions or collaboration, open an issue or discussion in the relevant repository.