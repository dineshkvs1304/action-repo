# GitHub Action Trigger Repository

This repository is used to generate GitHub webhook events for testing a webhook monitoring system.

## Purpose
It triggers the following GitHub events:
- Push events
- Pull request events
- Merge events

These events are captured by a Flask-based webhook receiver and stored in MongoDB, then displayed on a live dashboard.

## Usage
This repository acts as the **event generator** for the webhook monitoring project.
.
