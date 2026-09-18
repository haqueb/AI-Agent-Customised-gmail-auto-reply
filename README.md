# AI-Agent-Customised-gmail-auto-reply
AI-powered Gmail agent for automatically handling professional inquiries based on subject conditions and a predefined professional profile.

# AI Gmail Auto-Reply Agent

An AI-powered Gmail automation agent that understands incoming professional inquiries and automatically responds based on the user's professional profile, skills, and capabilities.

The agent is designed to act as an AI email assistant. It analyzes the customer's request, checks whether the requested service matches the user's professional capabilities, and sends a professional response automatically.

## How It Works

The automation follows a simple workflow:

**Incoming Gmail → Subject Check → AI Analysis → Professional Response → Automatic Gmail Reply**

### Important Condition

The agent does **not** automatically reply to every incoming email.

An automatic reply is triggered only when the Gmail subject line contains:

**Badrul**

For example:

`Subject: Badrul - Can you develop a WordPress plugin?`

If the subject does not contain **Badrul**, the automation does not send an AI-generated reply.

## AI Capabilities

The AI agent can evaluate professional inquiries such as:

* WordPress plugin development
* HTML banner creation or resizing
* Graphic design
* Web-related tasks
* AI-related services
* Other professional services included in the user's profile

The AI checks the incoming request against the stored professional profile.

If the requested work is within the user's capabilities, the agent provides a professional response confirming that the work can be handled.

If the requested work is outside the user's capabilities, the agent professionally declines the request instead of making false claims.

## Example

### Customer Email

**Subject:**
`Badrul - Can you resize an HTML banner?`

**Message:**
`Hi, I have an HTML banner that needs to be resized for another advertising platform. Can you handle this?`

### AI Response

The agent analyzes the request against the professional profile and automatically sends an appropriate professional response.

---

## Testing the Agent

Anyone who wants to test the automation can follow these steps:

### Step 1 — Send an Email

Send an email to the connected Gmail address.

### Step 2 — Add the Trigger Keyword

The subject line must contain:

`Badrul`

Example:

`Badrul - Can you create a WordPress plugin?`

### Step 3 — Ask a Professional Question

Write a realistic professional inquiry in the email body.

Example:

> Hello, I need a custom WordPress plugin for my website. Can you develop it?

### Step 4 — Wait for the Automation

The Gmail automation detects the keyword, sends the inquiry to the AI agent, analyzes the request, and generates a professional reply.

### Step 5 — Test Without the Keyword

Send another email without `Badrul` in the subject.

Example:

`Can you create a WordPress plugin?`

In this case, the AI agent should **not automatically reply**.

## Example Test Cases

| Subject                                 | Expected Behavior       |
| --------------------------------------- | ----------------------- |
| `Badrul - WordPress Plugin Development` | AI analyzes and replies |
| `Badrul - HTML Banner Resize`           | AI analyzes and replies |
| `Badrul - Graphic Design Service`       | AI analyzes and replies |
| `WordPress Plugin Development`          | No automatic reply      |
| `HTML Banner Resize`                    | No automatic reply      |

## Privacy & Security

This project should not contain private Gmail credentials, API keys, passwords, access tokens, or confidential customer information.

Sensitive configuration values should be stored using environment variables or the automation platform's secure credential system.

## Project Goal

The goal of this project is to demonstrate how AI can be integrated with Gmail automation to create an intelligent professional email assistant that can understand inquiries, evaluate service capabilities, and respond automatically based on predefined conditions and a professional profile.
