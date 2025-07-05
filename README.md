# GitHub Actions Repository

This repository is monitored by GitHub webhooks to track push, pull request, and merge activities.

## Purpose

This repository serves as the source for GitHub webhook events that are captured and displayed by the webhook monitoring system.

## Webhook Configuration

This repository is configured to send webhook events to the monitoring endpoint for the following actions:

- **Push events**: When code is pushed to any branch
- **Pull request events**: When pull requests are opened
- **Merge events**: When pull requests are merged

## Webhook Events Tracked

### Push Events
- Triggered when commits are pushed to any branch
- Captures: author, target branch, timestamp

### Pull Request Events
- Triggered when pull requests are opened
- Captures: author, source branch, target branch, timestamp

### Merge Events
- Triggered when pull requests are merged
- Captures: author, source branch, target branch, timestamp

