# Risk-assessment

* Encryption

* Auditing capabilities

## 2. Tools Required

* AWS Console with EC2, EBS, and EFS access

* Azure Portal with Storage Account access

* IAM credentials with sufficient permissions

* Risk Assessment Template (provided)

* Internet browser

* Microsoft Excel or Google Sheets for tabulating findings

## Procedure

## Part A: Identifying AWS Storage Assets

## Step 1: Login to AWS Console

* Go to: https://aws.amazon.com/console

* Log in using IAM or root credentials
  
## Step 2: Identify EBS Volumes

* Navigate to: EC2 > Volumes (under Elastic Block Store)

* Record the following:
  
     * Volume ID

     * Size and Type (e.g., gp2, io1)

     * Availability Zone

    * Attached instance (if any)

    * Encryption status

     * Tags

## Step 3: Identify EFS File Systems

* Go to: EFS > File systems
  
* Record:
  
     * File system ID and name

     * Mount targets (AZs)

     * Throughput mode (bursting/provisioned)

     * Performance mode

     * Lifecycle policy

     * Encryption at rest status

## Part B: Identifying Azure File Storage Assets

## Step 4: Login to Azure Portal

Go to: https://portal.azure.com

Log in using credentials with access to storage accounts

## Step 5: View File Shares

* Navigate to: Storage Accounts > Choose Account > File Shares
  
* Record:
  
     * Name

     * Quota (in GB)

     * Used space

     * Protocol (SMB/NFS)

     * Authentication method (SAS Tokens, Azure AD, Shared Keys)

     * Snapshot policies
 
       
## Risk Assessment Methodology

Use the following CIA-based asset-oriented checklist for each asset:

<img width="695" height="382" alt="image" src="https://github.com/user-attachments/assets/47b34930-0603-4da6-8f13-d2f06e5c260f" />

## Sample Output Table
<img width="1129" height="225" alt="image" src="https://github.com/user-attachments/assets/ef08f26e-3dd2-4c9b-ab58-8b39776dd4e3" />

## Result
All active cloud storage assets across AWS and Azure have been identified and assessed for security posture based on CIA principles, access control, encryption, and risk level.
