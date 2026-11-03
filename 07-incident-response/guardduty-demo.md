
# Amazon GuardDuty – Practical Demonstration

## 1. Objective

The objective of this demonstration is to understand how Amazon GuardDuty detects suspicious activities and generates security findings in an AWS environment.

## 2. Prerequisites

Before starting the demonstration, make sure you have:

- An active AWS account.
- Access to the AWS Management Console.
- Appropriate IAM permissions to enable and manage GuardDuty.
- An AWS Region selected for the demonstration.

## 3. Step 1: Enable Amazon GuardDuty

1. Log in to the AWS Management Console.
2. Search for **Amazon GuardDuty**.
3. Open the GuardDuty service.
4. Select the AWS Region where you want to perform the demonstration.
5. Click **Get Started**.
6. Select **Enable GuardDuty**.

GuardDuty will start monitoring supported AWS activity in the selected Region.

## 4. Step 2: Understand the GuardDuty Dashboard

After enabling GuardDuty:

1. Open the GuardDuty dashboard.
2. Review the security summary.
3. Navigate to the **Findings** section.
4. Check whether any security findings are available.

GuardDuty findings provide information such as:

- Finding type.
- Severity level.
- Affected AWS resource.
- Detection time.
- Description of suspicious activity.
- Recommended remediation steps.

## 5. Step 3: Generate a Sample Finding

For demonstration purposes, AWS provides a safe way to generate sample GuardDuty findings.

1. Open the GuardDuty console.
2. Navigate to **Settings**.
3. Locate the **Sample findings** option.
4. Choose **Generate sample findings**.

GuardDuty will generate predefined sample findings for demonstration purposes.

**Note:** Sample findings are simulated security alerts. They do not indicate that your AWS environment has actually been compromised.

## 6. Step 4: Investigate a GuardDuty Finding

1. Navigate to the **Findings** section.
2. Select one of the generated sample findings.
3. Review the finding details.

Pay attention to the following information:

| Field | Description |
|---|---|
| Finding Type | Category of detected activity |
| Severity | Criticality of the finding |
| Resource | Affected AWS resource |
| Region | AWS Region where activity was detected |
| First Seen | Time when activity was first detected |
| Last Seen | Most recent detection time |
| Description | Explanation of the suspicious activity |

## 7. Step 5: Understand the Incident Response Process

After identifying a suspicious finding, follow the incident response process:

1. **Detection:** GuardDuty identifies suspicious activity and generates a finding.
2. **Analysis:** Investigate the finding and review relevant logs.
3. **Containment:** Isolate the affected resource if necessary.
4. **Eradication:** Remove malicious files, unauthorized access, or malicious configurations.
5. **Recovery:** Restore the affected resource and verify its security.
6. **Lessons Learned:** Document the incident and implement preventive measures.

## 8. Step 6: Clean Up

After completing the demonstration:

- Review the generated sample findings.
- Document your observations.
- Disable GuardDuty only if it was enabled solely for this temporary lab and is no longer required.

**Important:** Do not disable GuardDuty in a production environment without appropriate security approval.

## 9. Expected Outcome

After completing this demonstration, you should understand:

- How to enable Amazon GuardDuty.
- How GuardDuty monitors AWS environments.
- How to generate sample security findings.
- How to investigate a security finding.
- How GuardDuty supports the incident response process.

---

## 10. Key Takeaway

Amazon GuardDuty helps security teams detect potential threats in AWS environments.

However, detecting a threat is only the first step. Security teams must investigate the findings, determine whether they represent real incidents, and take appropriate corrective actions.
