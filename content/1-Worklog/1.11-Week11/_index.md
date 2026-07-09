---
title: "Week 11 Worklog"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:

* Implement the `digest` Lambda function for automated weekly summary emails powered by Bedrock.
* Implement the `followup` Lambda function for daily application deadline reminders.
* Start building the automated test suite using pytest and moto.

### Tasks to be carried out this week:

| No. | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| 1 | Implemented the `digest` Lambda function: aggregates a user's weekly application data. | 29/06/2026 | 30/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 2 | Integrated Bedrock into `digest` to generate a personalized weekly summary and suggestions. | 30/06/2026 | 01/07/2026 | https://docs.aws.amazon.com/bedrock/ |
| 3 | Connected `digest` to Amazon SES to send the weekly summary email every Monday morning. | 01/07/2026 | 02/07/2026 | https://docs.aws.amazon.com/ses/ |
| 4 | Implemented the `followup` Lambda function: daily cron job that scans for upcoming/overdue application deadlines and sends reminder emails via SES. | 02/07/2026 | 03/07/2026 | https://docs.aws.amazon.com/lambda/ |
| 5 | Set up the test environment with pytest and moto, and began writing Unit/Integration tests for the Lambda functions built so far. | 03/07/2026 | 05/07/2026 | https://docs.getmoto.org/ |

### Week 11 Achievements:

* Delivered the **`digest` Lambda function**, which aggregates each user's weekly application activity, calls **Amazon Bedrock** to generate a summary and suggestions, and sends it automatically via **Amazon SES** every Monday morning.

* Delivered the **`followup` Lambda function**, a daily cron job that reminds users about job applications approaching or past their follow-up deadline.

* Set up the automated testing environment with **pytest** and **moto** (AWS service mocking), and wrote the first batch of Unit/Integration tests covering the Lambda functions built in Weeks 9–11.

### Plan for Next Week:

* Optimize the Bedrock system prompts so AI responses are concise and consistently formatted in Markdown.

* Expand the test suite to reach the project's target of 200+ test cases with ≥90% coverage.

* Write the report sections on AI Integration (Amazon Bedrock) and the Integration/Unit Testing strategy.
