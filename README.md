# AWS Resource Tracker

## Overview
AWS Resource Tracker is a Bash-based automation tool that monitors AWS resources, generates reports, and sends Slack alerts. It is designed to help DevOps engineers track AWS S3 Buckets, EC2 Instances, Lambda Functions, and IAM Users efficiently.

---

## Features
- Lists and reports AWS resources:
  - S3 Buckets
  - EC2 Instances
  - Lambda Functions
  - IAM Users
- Generates timestamped reports in `/aws_reports`
- Sends real-time Slack notifications when reports are created
- Detects changes compared to the previous report
- Keeps only the last 7 reports

---

## Prerequisites
- **AWS CLI** installed and configured with appropriate IAM permissions
- **jq** installed for parsing AWS CLI JSON outputs
- Slack workspace and incoming webhook URL
- Ubuntu/Linux server for cron scheduling

---

## Folder Structure
