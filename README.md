# Hi, I’m Sumit Dalavi 👋

I build and share software projects focused on platform engineering, cloud-native systems, DevSecOps, SRE, and AI infrastructure.

- [Project case studies](https://sumit-dalavi.is-a.dev)
- Current interests: Kubernetes platforms, GitOps, observability, secure automation, and reliable AI systems.
- Interested in practical open-source collaboration and engineering discussions.

## Open-source contributions

### Merged

- [Argo CD #29627](https://github.com/argoproj/argo-cd/pull/29627) — fixed CLI wait-condition handling when waiting on selected resources. Merged 7 October 2026.
- [OpenTelemetry Collector Contrib #50922](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/50922) — added delta-temporality aggregation support to the interval processor. Merged 18 September 2026.
- [OpenTelemetry Collector Contrib #50790](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/50790) — added CI coverage for tests excluded from race-enabled runs. Merged 9 September 2026.

### Open pull requests

- [Argo CD #29601](https://github.com/argoproj/argo-cd/pull/29601) — adds a configurable `--max-pending-resources` limit for `app wait`, `sync`, and `rollback`. Status: open.
- [Argo CD #30083](https://github.com/argoproj/argo-cd/pull/30083) — improves `app wait` timeout messages with condition summaries and operation details. Status: open.
- [Kyverno #17506](https://github.com/kyverno/kyverno/pull/17506) — highlights the location of JMESPath syntax errors in `kyverno jp query`. Status: open.
- [External Secrets Operator #6943](https://github.com/external-secrets/external-secrets/pull/6943) — adds custom CA support for the Fortanix provider. Status: open.

PR status can change; each link is the source of truth.

## Selected projects

### Platform engineering and Kubernetes
- [Secure Dev Platform Demo](https://github.com/SumitDalavi/secure-dev-platform-demo) — local integration demo for Kubernetes provisioning, admission control, policy enforcement, and secret rotation.
- [K8s Golden Path Provisioner](https://github.com/SumitDalavi/k8s-golden-path-provisioner) — Kubernetes operator and developer-facing resource model for environment provisioning.
- [K8s Admission Webhook from Scratch](https://github.com/SumitDalavi/k8s-admission-webhook-from-scratch) — Go implementation exploring Kubernetes admission contracts and failure-policy choices.
- [Multi-Cluster GitOps Promotion](https://github.com/SumitDalavi/multi-cluster-gitops-promotion) — Git-based environment promotion and ApplicationSet design.

### Reliability and observability
- [Durable Incident Agent](https://github.com/SumitDalavi/durable-incident-agent) — durable incident workflow with approval and telemetry-based recovery verification.
- [A2A Incident Mesh](https://github.com/SumitDalavi/a2a-incident-mesh) — agent interoperability demo focused on task routing, streaming, and cancellation behavior.
- [Inference Performance Lab](https://github.com/SumitDalavi/inference-performance-lab) — experiments and tooling for streaming inference measurements.
- [OpenTelemetry Microservice Demo](https://github.com/SumitDalavi/opentelemetry-microservice-demo) — distributed tracing and collector-based observability across services.

### Security and AI infrastructure
- [Agent Sandbox Platform](https://github.com/SumitDalavi/agent-sandbox-platform) — container-based execution sandbox with policy checks and explicit cleanup behavior.
- [NHI Agent Access Governance](https://github.com/SumitDalavi/nhi-agent-access-governance) — prototype for scoped authorization and policy decisions for non-human identities.
- [Supply Chain Security Pipeline](https://github.com/SumitDalavi/supply-chain-security-pipeline) — reference workflow for SBOMs, scanning, signing, provenance, and policy gates.
- [AI Control Plane Demo](https://github.com/SumitDalavi/ai-control-plane-demo) — composition of AI gateway, identity, caching, routing, guardrails, and evaluation components.

Browse the [full repository catalog](https://github.com/SumitDalavi?tab=repositories) or visit the [portfolio case studies](https://sumit-dalavi.is-a.dev). Project pages describe implementation scope, recorded evidence, and limitations; prototypes and labs are labelled as such.

## What I enjoy building

- Kubernetes operators, platform APIs, and secure developer workflows.
- GitOps, CI/CD, progressive delivery, and cloud-native security.
- Reliability tooling, observability, and failure-aware distributed systems.
- AI infrastructure with explicit policy, evaluation, and execution boundaries.

If you find something useful or want to collaborate, feel free to open an issue or discussion in a repository.