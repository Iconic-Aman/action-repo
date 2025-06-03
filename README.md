# 🚀 action-repo

This repository is used to **trigger GitHub webhook events** like `push`, `pull_request`, and `merge` to a separate backend server for logging and visualization.

The backend logic and MongoDB storage are handled in a separate repository: [`webhook-repo`](https://github.com/your-username/webhook-repo).

---

## 🔗 Connected Webhook

> This repository is connected to a GitHub webhook:

Whenever events like commits, pull requests, or merges happen in this repo, they are automatically sent to the webhook server (`webhook-repo`) for processing and display.

---

Whenever events like commits, pull requests, or merges happen in this repo, they are automatically sent to the webhook server (`webhook-repo`) for processing and display.

---

## 🎯 Purpose

- Simulate and test GitHub webhook events
- Demonstrate integration between a GitHub repo and a webhook listener
- Used for testing the UI and MongoDB logging in [`webhook-repo`](https://github.com/Iconic-Aman/webhook-repo)

---

## ✅ How to Trigger Events

You can trigger GitHub events from this repo by:

- Pushing commits to any branch
- Opening or reopening pull requests
- Merging pull requests into the main branch

---

## 🧠 Note

No backend or server code lives in this repository.
All webhook event handling is managed externally in `webhook-repo`.

---
