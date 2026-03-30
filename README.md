# 🎓 UFuture Entrance Survey RPA

[![Python Version](https://img.shields.io/badge/python-3.7+-blue.svg)](https://python.org)
[![Playwright](https://img.shields.io/badge/playwright-1.40.0-green.svg)](https://playwright.dev)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-stable-brightgreen.svg)]()

Automated RPA tool for completing entrance/exit surveys on UFuture academic portal.

## ✨ Features

- 🔐 Auto-login with credentials
- 🧭 Smart navigation to surveys  
- 📝 Auto-fills Likert scale questions
- 🔄 Handles multiple surveys
- 🎲 Random or fixed responses
- 🖥️ Headless mode support

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/yourusername/ufuture-survey-rpa.git
cd ufuture-survey-rpa

# Install dependencies
pip install -r requirements.txt
playwright install chromium

# Configure
cp .env.example .env
# Edit .env with your credentials

# Run
python ufuture_survey_rpa.py
