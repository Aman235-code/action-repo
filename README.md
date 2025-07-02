# Action Repo

This repository is used to **trigger GitHub webhook events** like:

- ✅ Push
- ✅ Pull Request (PR)
- ✅ Merge

These events are captured by a separate Flask application (`webhook-repo`) that listens to them using a configured GitHub webhook.

---

## 🔗 How It Works

This repo is connected to a Flask-based webhook receiver at:

