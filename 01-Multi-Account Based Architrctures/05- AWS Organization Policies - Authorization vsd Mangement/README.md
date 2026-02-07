# AWS Organization Polices - Authorization vs Management

## Revising the basic

Policies in AWS Organizations enable you to apply additional types of
management to the AWS accounts within your organization.

<div align="center">
<img src="images/image1.png" alt="IAM Policies" width="600">
</div>

# category of policies

Organization offers policy types in the following two broad categories.

| Policy Category        | Description                                                                                                      |
|------------------------|------------------------------------------------------------------------------------------------------------------|
| Authorization Policies | Helps control what actions can or cannot be performed within AWS accounts.                                       |
|                        | **Example:** Deny disabling CloudTrail.                                                                           |
| Management Policies    | Help with resource management, governance, and consistency across AWS accounts, but do not directly control access permissions. |
|                        | **Example:** Ensure every resource has the proper cost allocation tag values.                                    |

| Policy Type                     | Policy Category | Affects Management Account |
|---------------------------------|-----------------|----------------------------|
| Service Control Policies        | Authorization   | No                         |
| Resource Control Policies       | Authorization   | No                         |
| Tag Policies                    | Management      | Yes                        |
| Backup Policies                 | Management      | Yes                        |
| AI services opt-out policies    | Management      | Yes                        |
| Security Hub policies           | Management      | Yes                        |
| Chat applications policies      | Management      | Yes                        |
| Declarative policies for EC2    | Management      | Yes                        |
