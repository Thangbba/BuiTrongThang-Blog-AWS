---
title: "Week 7 Worklog"
date: 2026-05-25
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives:

* Deploy a static website on Amazon S3 accelerated by Amazon CloudFront.
* Deploy AWS Backup with a backup plan, vault, and restore test.
* Practice importing and exporting virtual machines between an on-premises environment and AWS.
* Get hands-on with IAM Roles used by AWS services.

### Tasks to be carried out this week:

| No. | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| 1 | Created an S3 bucket, uploaded a static website, and enabled Static Website Hosting. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 2 | Configured Amazon CloudFront in front of the S3 bucket and blocked direct public access to the bucket. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | Created an AWS Backup vault and backup plan, then ran and validated a test restore, with SNS notifications for job status. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | Practiced exporting a virtual machine from an EC2 instance/AMI and importing a VM from a local server into AWS. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | Created and configured an IAM Role (vmimport) and reviewed IAM policies required for the VM Import/Export process. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |

### Week 7 Achievements:

* Successfully deployed a **static website on Amazon S3**, accelerated and secured through **Amazon CloudFront**, with the bucket blocked from direct public access.

* Deployed and tested **AWS Backup**, including a backup plan, a backup vault, and a validated restore, with **Amazon SNS** notifications for backup job status.

* Practiced the full **VM Import/Export** workflow — exporting a VM from an EC2 instance/AMI and importing a local VM into AWS.

* Configured the **IAM Role and policy (vmimport)** required to support the VM Import/Export service.

### Plan for Next Week:

* Wrap up the remaining storage labs (AWS Storage Gateway) and start consolidating notes for the internship report and final presentation.
