# Task 5: Cloud Billing & Cost Automation

## Objective

The objective of this task is to prevent unexpected cloud expenses by configuring AWS cost monitoring and automated billing alerts.

## AWS Services Used

- AWS Budgets
- Amazon CloudWatch
- Amazon Simple Notification Service (SNS)
- AWS Billing and Cost Management

## Implementation

### 1. AWS Budget Configuration

Created a monthly cost budget with a threshold of $10 to monitor AWS cloud spending and help prevent unexpected charges.

### 2. CloudWatch Billing Alerts

Enabled CloudWatch billing alerts through AWS Billing Preferences.

### 3. CloudWatch Alarm

Created a CloudWatch alarm using the following configuration:

- Metric: EstimatedCharges
- Namespace: AWS/Billing
- Currency: USD
- Statistic: Maximum
- Period: 6 hours
- Threshold: Greater than $10

### 4. Email Notification

Created an Amazon SNS topic and configured an email subscription to receive automated notifications when the estimated AWS charges exceed the configured threshold.

The SNS email subscription was successfully confirmed.

## Alarm Name

Monthly-Billing-Alert-10USD

## Result

Successfully configured AWS Budgets and Amazon CloudWatch billing monitoring with automated email notifications. This setup helps monitor cloud spending and provides alerts when estimated charges exceed the defined $10 threshold.

## Skills Learned

- AWS Billing and Cost Management
- AWS Budgets
- Amazon CloudWatch
- CloudWatch Billing Alarms
- Amazon SNS
- Cloud Cost Monitoring
- Automated Email Notifications
