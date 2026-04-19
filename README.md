# Amazon EC2 (amazon-ec2)
Amazon Elastic Compute Cloud (EC2) provides resizable compute capacity in the cloud, allowing you to launch virtual server instances, manage networking, and configure storage with complete control over your computing resources.

**URL:** [Visit APIs.json URL](https://aws.amazon.com/ec2/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Cloud Computing, Compute, IaaS, Infrastructure, Virtual Machines

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon EC2 API
Core API for managing Amazon EC2 instances, AMIs, key pairs, security groups, Elastic IPs, launch templates, spot instances, capacity reservations, and other compute resources.

**Human URL:** [https://aws.amazon.com/ec2/](https://aws.amazon.com/ec2/)

#### Tags:

 - AWS, Cloud Computing, Compute, Instances, Virtual Machines

#### Properties

- [Documentation](https://docs.aws.amazon.com/AWSEC2/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-ec2-openapi.yml)
- [OpenAPI](https://api.apis.guru/v2/specs/amazonaws.com/ec2/2016-11-15/openapi.yaml)
- [JSONSchema](json-schema/amazon-ec2-instance-schema.json)
- [JSONLD](json-ld/amazon-ec2-context.jsonld)
- [Pricing](https://aws.amazon.com/ec2/pricing/)
- [GettingStarted](https://aws.amazon.com/ec2/getting-started/)
- [Authentication](https://docs.aws.amazon.com/AWSEC2/latest/APIReference/Query-Requests.html)
- [SDK](https://aws.amazon.com/tools/)
- [StatusPage](https://status.aws.amazon.com/)
- [BestPractices](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-best-practices.html)
- [FAQ](https://aws.amazon.com/ec2/faqs/)
- [TermsOfService](https://aws.amazon.com/ec2/sla/)
- [Documentation](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/)
- [APIReference](https://docs.aws.amazon.com/AWSEC2/latest/APIReference/)
- [Documentation](https://docs.aws.amazon.com/cli/latest/reference/ec2/)
- [Security](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security.html)
- [JSONStructure](json-structure/amazon-ec2-instance-structure.json)
- [Example](examples/amazon-ec2-instance-example.json)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/ec2/)
- [Documentation](https://docs.aws.amazon.com/ec2/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/compute/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/ec2/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-ec2)
- [Contact](https://aws.amazon.com/contact-us/)
- [Security](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security.html)
- [Compliance](https://aws.amazon.com/compliance/)
- [SpectralRules](rules/amazon-ec2-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-ec2-vocabulary.yaml)
- [NaftikoCapability](capabilities/ec2-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Diverse Instance Types | Over 750 instance types optimized for compute, memory, storage, GPU, and inferencing workloads. |
| Amazon Machine Images | Pre-configured OS images for Windows, Linux, and macOS with custom and marketplace options. |
| Elastic IPs | Static IPv4 addresses that can be quickly remapped to different instances for fault tolerance. |
| Security Groups | Virtual firewalls to control inbound and outbound traffic to EC2 instances. |
| Spot Instances | Access spare EC2 capacity at up to 90% discount over On-Demand prices for flexible workloads. |
| Placement Groups | Control instance placement for low-latency cluster networking or high-availability distribution. |
| Launch Templates | Version-controlled configurations for launching EC2 instances with consistent settings. |
| Nitro System | Next-generation virtualization infrastructure delivering near bare-metal performance and security. |

## Use Cases

| Name | Description |
|------|-------------|
| Web Application Hosting | Deploy scalable web applications and APIs with full control over the compute environment. |
| Machine Learning Training | GPU-accelerated instances for deep learning model training and inference workloads. |
| High-Performance Computing | Cluster networking instances for computational fluid dynamics, genomics, and financial modeling. |
| SAP and Enterprise Workloads | Certified instances for SAP HANA, SAP S/4HANA, and other enterprise database applications. |
| Development and Testing | Flexible on-demand compute for CI/CD pipelines, dev environments, and test automation. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon VPC | Launch EC2 instances in logically isolated virtual networks with full networking control. |
| Elastic Load Balancing | Distribute incoming traffic across multiple EC2 instances for high availability. |
| Amazon RDS | Connect EC2 instances to managed relational database services within the same VPC. |
| AWS Auto Scaling | Automatically scale EC2 fleets based on demand metrics and scheduling policies. |
| AWS Systems Manager | Manage, patch, and operate EC2 instances at scale without SSH access. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Ec2](openapi/amazon-ec2-openapi.yml)

### JSON Schema

- [Amazon Ec2 Instance](json-schema/amazon-ec2-instance-schema.json)
- [Ec2 Openapi Create Image Response](json-schema/ec2-openapi-create-image-response-schema.json)
- [Ec2 Openapi Describe Instances Response](json-schema/ec2-openapi-describe-instances-response-schema.json)
- [Ec2 Openapi Instance](json-schema/ec2-openapi-instance-schema.json)
- [Ec2 Openapi Run Instances Response](json-schema/ec2-openapi-run-instances-response-schema.json)
- [Ec2 Openapi Tag](json-schema/ec2-openapi-tag-schema.json)

### JSON Structure

- [Amazon Ec2 Instance](json-structure/amazon-ec2-instance-structure.json)
- [Ec2 Openapi Create Image Response](json-structure/ec2-openapi-create-image-response-structure.json)
- [Ec2 Openapi Describe Instances Response](json-structure/ec2-openapi-describe-instances-response-structure.json)
- [Ec2 Openapi Instance](json-structure/ec2-openapi-instance-structure.json)
- [Ec2 Openapi Run Instances Response](json-structure/ec2-openapi-run-instances-response-structure.json)
- [Ec2 Openapi Tag](json-structure/ec2-openapi-tag-structure.json)

### JSON-LD

- [Amazon Ec2](json-ld/amazon-ec2-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Ec2](capabilities/shared/ec2.yaml) — 135 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Ec2 Management](capabilities/ec2-management.yaml) | 10 | managing EC2 instances, AMIs, security groups, and networking for cloud infrastructure engineers |

## Vocabulary

- [Amazon EC2 Vocabulary](vocabulary/amazon-ec2-vocabulary.yaml) — Unified taxonomy mapping 26 resources, 14 actions, 1 workflows, and 1 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Ec2 Spectral Rules](rules/amazon-ec2-spectral-rules.yml) — 28 rules enforcing Amazon EC2 API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com