# Lesson 7 – Secure Webhook Assessment

## Working with Webhooks and Event-Driven APIs

This repository contains the n8n workflow for the Lesson 7 LMS assessment.

### Workflow Overview

`Webhook Trigger → Verify HMAC & Parse Payload → Signature Valid?`

- Valid signature → `Respond 200 OK`
- Invalid signature → `Respond 401 Unauthorized`

### Assessment Coverage

- POST Webhook Trigger with a custom endpoint
- Webhook payload processing
- Header, query-parameter, and JSON-body capture
- HMAC-SHA256 signature verification
- Conditional security validation
- HTTP 200 response for valid requests
- HTTP 401 response for invalid signatures
- End-to-end webhook testing

### Security Notes

The workflow supports the `WEBHOOK_HMAC_SECRET` environment variable for the shared HMAC secret. Avoid committing real secrets, tokens, or credentials to source control.

### Submission Evidence

The LMS submission should include the Loom/YouTube walkthrough, exported n8n workflow JSON, and assessor comments describing testing, assumptions, limitations, or enhancements.
