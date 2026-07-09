---
title: "Week 10 Worklog"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Implement the `insights` Lambda function to power AI-based application pattern analysis and chat.
* Implement the `settings` Lambda function for weekly application goals and streak tracking.
* Implement the `notes` Lambda function for timeline-based notes per job application.

### Tasks to be carried out this week:

| No. | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| 1 | Implemented the `insights` Lambda function: receives application history payload and calls the Bedrock API. | 22/06/2026 | 24/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 2 | Implemented streaming responses from Bedrock for the AI Chat feature within `insights`. | 24/06/2026 | 25/06/2026 | https://docs.aws.amazon.com/bedrock/ |
| 3 | Implemented pattern analysis logic (response rate by resume version, by channel) inside `insights`. | 25/06/2026 | 26/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 4 | Implemented the `settings` Lambda function to store and update weekly application goals and streaks. | 26/06/2026 | 27/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 5 | Implemented the `notes` Lambda function with full CRUD operations for timeline-based notes on each job application. | 27/06/2026 | 28/06/2026 | https://docs.aws.amazon.com/lambda/ |

### Week 10 Achievements:

* Delivered a working **`insights` Lambda function** that ingests a user's application history and calls **Amazon Bedrock** to generate AI Chat responses and pattern analysis (e.g. which resume version or channel performs best).

* Implemented **streaming text output** from Bedrock so the AI Chat feature responds progressively rather than waiting for the full response.

* Delivered the **`settings` Lambda function**, handling weekly application goals and streak tracking for each user.

* Delivered the **`notes` Lambda function**, supporting full CRUD for notes attached to a job application's timeline.

### Plan for Next Week:

* Implement the `digest` Lambda function: aggregate weekly data, call Bedrock to generate a summary, and send it via SES.

* Implement the `followup` Lambda function: daily cron job that reminds users about upcoming application deadlines.

* Start writing Unit/Integration tests using pytest and moto (AWS mocking).
