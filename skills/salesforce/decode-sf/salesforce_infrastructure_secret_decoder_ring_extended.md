Salesforce Technology & Products  
**Secret Decoder Ring** (glossary / index) ATO  

| **Term** | **Definition** | **For More Info** |
| **A** |  |  |
| **B** |  |  |
| **C** |  |  |
| **D** |  |  |
| **E** |  |  |
| **F** |  |  |
| FKP | Falcon Kubernetes Platform — managed K8s runtime in Falcon. **Same platform as SAM** (formerly "SAM-Falcon"); registered as the `sam` service in Falcon's service registry, so "FKP service" and "sam service" are used interchangeably. | [FKP capability page](https://docs.internal.salesforce.com/capabilities/fkp/) — [FKP Runbook](https://confluence.internal.salesforce.com/spaces/ADOSCR/pages/954041737/) |
| FMP | Informal shorthand for SFMP (Salesforce Management Plane) — see SFMP below. | [SFMP Home](https://confluence.internal.salesforce.com/display/SFMP/SFMP+Home) |
| FTE | Fault-Tolerant Execution — Trino feature (set via `retry_policy=TASK` session property) that retries failed tasks within a query instead of restarting the whole query from scratch. Uses an "exchange manager" backed by an S3 spooling bucket. In April 2026 the Interactive Analytics team launched **Automatic FTE**: an ML model (Trino Query Predictor) predicts heavy queries and auto-enables FTE for them. Distinct from the HR sense of FTE (Full-Time Employee/Equivalent). | [Trino docs: fault-tolerant-execution](https://trino.io/docs/current/admin/fault-tolerant-execution.html) — [Auto-FTE announcement](https://salesforce.enterprise.slack.com/archives/C08NERTUKAS/p1776806008313339) |
| **G** |  |  |
| **H** |  |  |
| HPS | Hyperforce Platform Services (formerly HIPE) — division responsible for delivering Hyperforce as a platform: infrastructure, trust/security, and developer productivity. Org led by Paul Constantinides. | [GlossaryHub: HPS](https://glossaryhub-live-search.herokuapp.com/s/HPS) |
| HRP | Hyperforce Runtime Platform — runtime infrastructure layer for Hyperforce deployments; the platform that runs workloads on public cloud (AWS, etc.). | [GlossaryHub: HRP](https://glossaryhub-live-search.herokuapp.com/s/HRP) |
| **I** |  |  |
| **J** |  |  |
| **K** |  |  |
| **L** |  |  |
| **M** |  |  |
| MELT | Metrics, Events, Logs, and Traces — the four canonical telemetry signal types. At Salesforce, MELT is provided by Moncloud. |  |
| **N** |  |  |
| **O** |  |  |
| **P** |  |  |
| **Q** |  |  |
| **R** |  |  |
| **S** |  |  |
| SAM | Salesforce Application Model — original first-party name for the managed Kubernetes platform. **Same platform as FKP** in Falcon; the service is registered as `sam` in Falcon's registry. Despite the name, it's a K8s compute substrate, not a higher-level app programming model. | [FKP capability page](https://docs.internal.salesforce.com/capabilities/fkp/) — [FKP Runbook](https://confluence.internal.salesforce.com/spaces/ADOSCR/pages/954041737/) |
| SFMP | Salesforce Management Plane — PurpleFlock-compliant framework (GA April 2024) for Day 2 operations on Falcon / Near-Core services via REST APIs, without needing PCSK production access. Sometimes informally called FMP. | [SFMP Home](https://confluence.internal.salesforce.com/display/SFMP/SFMP+Home) |
| SPIFFE | Secure Production Identity Framework For Everyone — open-source CNCF standard for cryptographic workload identity. A SPIFFE ID is a URI of form `spiffe://<trust-domain>/<path>`, delivered to workloads as an SVID (X.509 cert or JWT). Reference implementation is SPIRE. Used in Salesforce authz configs (e.g. UIP `SpiffeMatch` blocks) to identify calling workloads by namespace/service/FD. | [spiffe.io](https://spiffe.io/) |
| **T** |  |  |
| **U** |  |  |
| **V** |  |  |
| **W** |  |  |
| **X** |  |  |
| **Y** |  |  |
| **Z** |  |  |
