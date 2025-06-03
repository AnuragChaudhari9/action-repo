# action-repo

This is a dummy GitHub repository used to trigger webhook events such as `push`, `pull_request`, and `merge`. These events are received and processed by a Flask webhook server hosted in the [webhook-repo](https://github.com/AnuragChaudhari9/webhook-repo).

---

## Purpose

- Used to simulate GitHub webhook events
- Sends events to a configured webhook endpoint
- Helps test and demonstrate end-to-end webhook logging and UI display

---

## How to Use

### 1. Make a code change

```bash
echo "Trigger webhook at $(date /t)" >> test.txt
git add test.txt
git commit -m "Triggering webhook event"
git push
```
