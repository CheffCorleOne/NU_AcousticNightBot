🎸 Acoustic Night — Telegram Collaboration Bot
A Telegram bot that helps musicians create profiles, find collaborators, and connect after a mutual match.
Built with Python, python-telegram-bot, and PostgreSQL (JSONB).

✨ Features
Create & Edit Profile

Choose instruments you play from 10+ options

Specify instruments you're seeking

Write a short bio (max 120 characters)

Smart Matching System

🎯 Smart Matches: Find users based on mutual instrument interests

🔀 Browse All: Discover all musicians in swipe-style interface

Secure Collaboration

Send "Let's Collab" requests to other musicians

Contact information revealed only after mutual match

Real-time notification system for requests

User Management

View your profile and matches

Track pending requests and connections

Production Ready

Built-in health check server for hosting platforms

Error handling and logging

🗂 Tech Stack
Python 3.10+

python-telegram-bot v20.6 - Modern Telegram Bot API framework

PostgreSQL with JSONB - Flexible data storage

psycopg2 - PostgreSQL adapter for Python

Standard Library - threading, logging, http.server

🚀 Installation & Setup
bash
# Clone repository
git clone https://github.com/CheffCorleOne/NU_acousticnigtbot.git
cd NU_acousticnigtbot

# Create virtual environment
python3 -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt
🔧 Environment Configuration
Create a .env file with:

env
TELEGRAM_BOT_TOKEN=your_telegram_bot_token_here
DATABASE_URL=postgresql://user:password@host:5432/database_name
PORT=10000
🗄 Database Schema
The bot uses a simple yet powerful PostgreSQL schema with JSONB
