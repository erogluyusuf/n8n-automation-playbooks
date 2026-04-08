# Email Campaign Tracking

## Description
Listens for webhook events from email providers (like SendGrid, Mailgun, AWS SES) regarding Bounces or Unsubscribes. It automatically updates the user's status in the SQL database to prevent future sending and maintain a high sender reputation.
