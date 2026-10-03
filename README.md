<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=n8n%20secure%20webhook%20assessment;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/n8n-secure-webhook-assessment)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=n8n-secure-webhook-assessment&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/n8n-secure-webhook-assessment) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/n8n-secure-webhook-assessment/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/n8n-secure-webhook-assessment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/n8n-secure-webhook-assessment/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/n8n-secure-webhook-assessment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/n8n-secure-webhook-assessment/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/n8n-secure-webhook-assessment) · [🐞 Report Issue](https://github.com/shaikshahid777/n8n-secure-webhook-assessment/issues/new) · [⭐ Star](https://github.com/shaikshahid777/n8n-secure-webhook-assessment/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/n8n-secure-webhook-assessment/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

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
