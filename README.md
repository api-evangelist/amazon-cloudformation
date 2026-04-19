# Amazon CloudFormation (amazon-cloudformation)
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
