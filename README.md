# 🐍🐳 Flask Docker Hello World

[![Python Version](https://img.shields.io/badge/python-3.12-blue)](https://www.python.org/downloads/)
[![Flask Version](https://img.shields.io/badge/flask-3.0.0-green)](https://flask.palletsprojects.com/)
[![GitHub Stars](https://img.shields.io/github/stars/saeedmfat/flask-docker-app?style=social)](https://github.com/saeedmfat/flask-docker-app/stargazers)
[![GitHub Commits](https://img.shields.io/github/commit-activity/m/saeedmfat/flask-docker-app)](https://github.com/saeedmfat/flask-docker-app/commits/main)

A production-ready "Hello World" Flask application containerized with Docker, featuring Python 3.12 and best practices.


## 🌟 Features

- **Modern Python**: Uses Python 3.12 for optimal performance
- **Lightweight**: ~120MB Docker image (python:3.12-slim base)
- **Production Ready**: Proper port exposure and binding
- **Live Monitoring**: Badges show real-time project metrics

## 🚀 Quick Deployment

```bash
# Run directly from Docker Hub
docker run -d -p 5000:5000 saeedmfat/flask-docker-app
```

Then visit: http://localhost:5000

## 🛠️ Development Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/saeedmfat/flask-docker-app.git
   cd flask-docker-app
   ```

2. Build and run:
   ```bash
   docker build -t flask-app .
   docker run -p 5000:5000 flask-app
   ```

## 📊 Project Stats

| **Last Commit** | ![Last Commit](https://img.shields.io/github/last-commit/saeedmfat/flask-docker-app) |
| **Code Size** | ![Repo Size](https://img.shields.io/github/repo-size/saeedmfat/flask-docker-app) |

## 🐛 Troubleshooting

**Error** | **Solution**
---|---
`Port 5000 in use` | Use `-p 5001:5000` instead
`Docker build fails` | Check Python version compatibility
`No response from app` | View logs: `docker logs <container-id>`
