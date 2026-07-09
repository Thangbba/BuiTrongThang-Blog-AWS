---
title: "Week 9 Worklog"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:

* Kick off the SmartCV team project (AI-Powered Job Application Tracker) with team TechTitans.
* Research Amazon Bedrock and select the right foundation model for the AI coaching feature.
* Design the Prompt Engineering flow for CV/application pattern analysis.
* Design the scheduled Cron Job logic using AWS EventBridge for the weekly report email feature.

### Tasks to be carried out this week:

| No. | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| 1 | Joined the team to finalize the SmartCV topic and its serverless technology direction. | 15/06/2026 | 15/06/2026 | https://aws.amazon.com/serverless/ |
| 2 | Researched the Amazon Bedrock API and available foundation models. | 16/06/2026 | 17/06/2026 | https://docs.aws.amazon.com/bedrock/ |
| 3 | Evaluated and selected the Amazon Nova Lite model, optimized for cost and available in the ap-southeast-1 region. | 18/06/2026 | 18/06/2026 | https://docs.aws.amazon.com/bedrock/ |
| 4 | Designed the Prompt Engineering interaction flow for the CV/application analysis feature. | 19/06/2026 | 20/06/2026 | https://docs.aws.amazon.com/bedrock/ |
| 5 | Designed the Cron Job logic using AWS EventBridge for the weekly summary email feature. | 20/06/2026 | 21/06/2026 | https://docs.aws.amazon.com/eventbridge/ |

### Week 9 Achievements:

* Contributed to finalizing the **SmartCV** project scope and the overall serverless architecture direction with the team.

* Researched **Amazon Bedrock** and selected the **Amazon Nova Lite** model as the best fit for cost efficiency and regional availability.

* Designed the **Prompt Engineering** flow that will feed application data into Bedrock for personalized AI coaching.

* Designed the **EventBridge cron logic** that will later trigger the weekly digest email feature.

### Plan for Next Week:

* Start implementing the `insights` Lambda function: receive application history payload and call the Bedrock API for AI chat and pattern analysis.

* Implement the `settings` Lambda function (weekly application goals/streak) and the `notes` Lambda function (CRUD notes per job application timeline).
