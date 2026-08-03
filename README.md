# Amazon CloudFormation (amazon-cloudformation)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AWS CloudFormation is an infrastructure-as-code service that speeds up cloud provisioning by enabling developers to define and manage AWS resources programmatically through templates. Scale infrastructure globally and manage resources across all AWS accounts and regions through a single operation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloudformation/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CloudFormation, Infrastructure as Code, DevOps, IaC

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CloudFormation API
API for creating, updating, and managing CloudFormation stacks, stack sets, and change sets for infrastructure-as-code deployments across AWS accounts and regions.

**Human URL:** [https://aws.amazon.com/cloudformation/](https://aws.amazon.com/cloudformation/)

#### Tags:

 - AWS, CloudFormation, Infrastructure as Code, DevOps

#### Properties

- [Documentation](https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/)
- [OpenAPI](openapi/amazon-cloudformation-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloudformation/)
- [SpectralRules](rules/amazon-cloudformation-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloudformation-vocabulary.yaml)
- [NaftikoCapability](capabilities/infrastructure-as-code.yaml)

## Features

| Name | Description |
|------|-------------|
| Infrastructure as Code | Define AWS resources in JSON or YAML templates for repeatable, version-controlled deployments. |
| Multi-Account Stack Sets | Deploy stacks across multiple AWS accounts and regions with a single operation. |
| Change Sets | Preview changes to running stacks before executing them to avoid unintended updates. |
| Drift Detection | Detect when deployed infrastructure has drifted from the CloudFormation template definition. |
| Registry Extensions | Extend CloudFormation to manage third-party and community resources through the Registry. |

## Use Cases

| Name | Description |
|------|-------------|
| DevOps Automation | Automate infrastructure testing and deployment through CI/CD pipelines. |
| Multi-Region Deployment | Deploy consistent infrastructure across multiple AWS regions. |
| Compliance Governance | Enforce organizational infrastructure standards through template guardrails. |
| Disaster Recovery | Rapidly rebuild infrastructure from templates after failures. |

## Integrations

| Name | Description |
|------|-------------|
| AWS CodePipeline | Automate CloudFormation deployments in CI/CD pipelines. |
| AWS Config | Track infrastructure changes and detect drift with Config integration. |
| AWS IAM | Control who can create and update CloudFormation stacks. |
| AWS Service Catalog | Publish approved CloudFormation templates as self-service products. |
| Amazon SNS | Receive stack event notifications via SNS topics. |

## Artifacts

### OpenAPI

- [Amazon CloudFormation API](openapi/amazon-cloudformation-openapi.yml)

### JSON Schema

- [Stack](json-schema/cloudformation-stack-schema.json)
- [ChangeSet](json-schema/cloudformation-change-set-schema.json)
- [StackResource](json-schema/cloudformation-stack-resource-schema.json)
- [Parameter](json-schema/cloudformation-parameter-schema.json)
- [Output](json-schema/cloudformation-output-schema.json)

### JSON-LD

- [Amazon CloudFormation Context](json-ld/amazon-cloudformation-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Amazon CloudFormation](capabilities/shared/cloudformation.yaml) — 8 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Infrastructure as Code Deployment](capabilities/infrastructure-as-code.yaml) | Amazon CloudFormation | 8 | DevOps Engineer |

## Vocabulary

- [Amazon CloudFormation Vocabulary](vocabulary/amazon-cloudformation-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon CloudFormation Spectral Rules](rules/amazon-cloudformation-spectral-rules.yml) — 19 rules enforcing Amazon CloudFormation API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
