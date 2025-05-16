This project is an automated notification system that fetches NBA game data from a public API and sends updates via email and SMS using AWS services.

⸻

Tech & Services Used:
	•	Python (Lambda function logic)
	•	AWS Lambda (to run the API logic)
	•	Amazon EventBridge (to schedule the Lambda trigger)
	•	Amazon SNS (Simple Notification Service) (to send messages)
	•	NBA API (SportsDataIO) (to retrieve real-time NBA stats)

⸻

Project Overview:

This solution automates NBA data retrieval and notification using AWS. It uses EventBridge to trigger a Lambda function on a schedule, which then fetches data from the NBA API. The results are published to an SNS topic that pushes messages to subscribed email and SMS endpoints.

⸻

Features:
	•	Scheduled data retrieval with EventBridge
	•	Serverless compute using Lambda
	•	API integration with SportsDataIO (NBA stats)
	•	Real-time notifications via SNS (email & SMS)
	•	Written in Python

⸻

Why I Built This:

This project was created as part of a DevOps learning challenge to understand how serverless architecture works using AWS services. It demonstrates event-driven design and message distribution in a scalable, cloud-native way.
