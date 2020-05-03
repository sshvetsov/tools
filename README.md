# Tools
Listing of tools I found useful or interesting.

## Terraform

### Best Practices
- https://github.com/antonbabenko/terraform-best-practices Terraform best practices (https://www.terraform-best-practices.com/).
- https://github.com/antonbabenko/terraform-best-practices-workshop Terraform best practices - workshop materials.

### Development
- https://github.com/antonbabenko/pre-commit-terraform pre-commit git hooks to take care of Terraform configurations.
- https://github.com/segmentio/terraform-docs Generate documentation from Terraform modules in various output formats.
- https://github.com/tfutils/tfenv Terraform version manager inspired by rbenv

### Output
- https://github.com/coinbase/terraform-landscape Improve Terraform's plan output to be easier to read and understand.
- https://github.com/dmlittle/scenery A Terraform plan output prettifier.
- https://github.com/chrislewisdev/prettyplan A formatting tool to help make large Terraform plans easier to review (https://prettyplan.chrislewisdev.com).

### Testing
- https://github.com/cesar-rodriguez/terrascan Collection of security and best practice test for static code analysis of terraform templates.
- https://github.com/liamg/tfsec Static analysis powered security scanner for your terraform code.
- https://github.com/fugue/regula Regula checks Terraform for AWS security and compliance using Open Policy Agent/Rego.
- https://github.com/bridgecrewio/checkov Static code analysis tool for infrastructure-as-code. It scans cloud infrastructure provisioned using Terraform and detects security and compliance misconfigurations.
- https://github.com/instrumenta/conftest Write tests against structured configuration data using the Open Policy Agent Rego query language.
- https://github.com/rubelw/terraform-validator Validated terraform template for various security violations and rules.
- https://github.com/eerkunt/terraform-compliance a lightweight, security focused, BDD test framework against terraform (https://terraform-compliance.com).

### Conversion
- https://github.com/flosell/iam-policy-json-to-terraform Small tool to convert an IAM Policy in JSON format into a Terraform aws_iam_policy_document.
- https://github.com/iann0036/former2 Generate CloudFormation / Terraform / Troposphere templates from your existing AWS resources (https://former2.com).
- https://github.com/dtan4/terraforming Export existing AWS resources to Terraform style (tf, tfstate) (http://terraforming.dtan4.net/).
- https://github.com/GoogleCloudPlatform/terraformer CLI tool to generate terraform files from existing infrastructure (reverse Terraform).
- https://github.com/jmcgill/formation Bulk import of resources into Terraform.
- https://github.com/bridgecrewio/AirIAM Least privilege AWS IAM Terraformer.
- https://github.com/cycloidio/terracognita/ Reads from existing Cloud Providers (reverse Terraform) and generates your infrastructure as code on Terraform configuration.

### Modules
- https://github.com/nozaq/terraform-aws-secure-baseline Terraform module to set up your AWS account with the secure baseline configuration based on CIS Amazon Web Services Foundations.
- https://github.com/apparentlymart/terraform-aws-tf-registry Terraform module for creating a simple private Terraform registry in AWS with DynamoDB.

### Examples
- https://github.com/aws-samples/aws-security-services-with-terraform Code examples for the AWS Security Blog post: How to use CI/CD to deploy and configure AWS security services with Terraform.
- https://github.com/ScaleSec/terraform_aws_scp AWS Organizations Service Control Policies (SCPs) written in HashiCorp Terraform.
- https://asecure.cloud/ A free repository of customizable AWS security configurations and best practices.

## AWS

### Security
- https://asecure.cloud/ A free repository of customizable AWS security configurations and best practices.
- https://docs.aws.amazon.com/controltower/latest/userguide/guardrails-reference.html Reference for each of the guardrails available in AWS Control Tower.
- https://github.com/toniblyx/my-arsenal-of-aws-security-tools List of open source tools for AWS security: defensive, offensive, auditing, DFIR, etc.
- https://github.com/duo-labs/cloudmapper CloudMapper helps you analyze your Amazon Web Services (AWS) environments.
- https://github.com/toniblyx/prowler AWS Security Best Practices Assessment, Auditing, Hardening and Forensics Readiness Tool.
- https://github.com/airbnb/streamalert StreamAlert is a serverless, realtime data analysis framework which empowers you to ingest, analyze, and alert on data from any environment, using datasources and alerting logic you define (https://streamalert.io).
- https://github.com/cloud-custodian/cloud-custodian Rules engine for cloud security, cost optimization, and governance, DSL in yaml for policies to query, filter, and take actions on resources (https://cloudcustodian.io).
- https://github.com/flosell/trailscraper A command-line tool to get valuable information out of AWS CloudTrail.
- https://github.com/jonrau1/ElectricEye Continuously monitor your AWS services for configurations that can lead to degradation of confidentiality, integrity or availability. All results will be sent to Security Hub for further aggregation and analysis.

### IAM Policy
- https://github.com/salesforce/policy_sentry IAM Least Privilege Policy Generator (https://policy-sentry.readthedocs.io/).
- https://github.com/duo-labs/parliament AWS IAM linting library.
- https://github.com/SummitRoute/aws_managed_policies Collection of the AWS Managed IAM policies.

### Federation
- https://github.com/Versent/saml2aws CLI tool which enables you to login and retrieve AWS temporary credentials using a SAML IDP.
- https://github.com/cevoaustralia/aws-google-auth Provides AWS STS credentials based on Google Apps SAML SSO auth.
- https://github.com/segmentio/aws-okta aws-vault like tool for Okta authentication.
