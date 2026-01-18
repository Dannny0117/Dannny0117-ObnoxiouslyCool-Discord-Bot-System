# Discord Streamer Bot (Node.js Edition)

A powerful, modern **Discord bot** rebuilt from the ground up in **100% Node.js**, bringing back the classic **Mixer / Scorpbot**-style streamer experience — now with a beautiful **web-based admin dashboard** for full control.

This bot includes commands, mini-games, points system, ranks, moderation tools, welcome cards, boost celebrations, and much more — just like your original Mixer bot, but now running natively on Discord with a professional web interface.

<p align="center">
  <a href="https://discord.dannny0117.com">
    <img src="https://img.shields.io/badge/Join%20Our%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join Discord Server">
  </a>
  &nbsp;&nbsp;
  <a href="https://snapchat.com/add/dannny0117">
    <img src="https://img.shields.io/badge/Snapchat-@dannny0117-FFFC00?style=for-the-badge&logo=snapchat&logoColor=black" alt="Snapchat @dannny0117">
  </a>
  &nbsp;&nbsp;
  <a href="https://x.com/dannny0117">
    <img src="https://img.shields.io/badge/X-@dannny0117-000000?style=for-the-badge&logo=x&logoColor=white" alt="X / Twitter @dannny0117">
  </a>
  &nbsp;&nbsp;
  <a href="https://tiktok.com/@dannny0117">
    <img src="https://img.shields.io/badge/TikTok-@dannny0117-FF0050?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok @dannny0117">
  </a>
</p>

[![Discord.js](https://img.shields.io/badge/discord.js-v14-blue.svg)](https://discord.js.org/)
[![Node.js](https://img.shields.io/badge/node-%3E%3D16.9.0-brightgreen.svg)](https://nodejs.org/)

## ✨ Features

- **Bad Word Filtering**
  - Advanced pattern matching (detects variations, l33t speak, spacing tricks)
  - Customizable word list (`badwords.txt`)
  - **Auto-reload on file changes** (no restart needed!)
  - Regex pattern support
  - Auto-delete + instant quarantine

- **Link & Invite Blocking**
  - Block all links by default
  - Whitelist safe domains (YouTube, Twitch, GitHub, etc.)
  - **ALWAYS blocks Discord invite links** (even in promo channels)
  - Channel-based exceptions (e.g., `#self-promo`)

- **Spam Detection**
  - Rate limit detection (5 messages in 5 seconds - configurable)
  - Duplicate message detection (3+ identical messages - configurable)
  - Auto-quarantine spam offenders

- **Mass Mention Protection**
  - Configurable mention limit (default: 4 per message)
  - Prevents mention spam attacks
  - Instant quarantine for violations

### Quarantine System
- **Automatic Role Management**
  - Creates `Quarantined` role automatically
  - 20-second timeout (configurable)
  - Can only view `#read-me-first` channel
  - Cannot type, react, or join voice anywhere
  - Auto-removes role after timeout

### Warning System
- **Persistent Tracking**
  - Never resets (permanent log)
  - Tracks all violations per user
  - Displays warning count in embeds
  - Detailed violation history

### Core Streamer Experience
- Custom **commands** (`!commands`, `!so`, `!clip`, custom user commands, etc.)
- **Points / currency system** — earn points by chatting, playing games, daily bonuses
- **Ranks & levels** with automatic role assignment
- **Leaderboard** (points, levels, wins, activity)

### Moderation & Safety
- Auto-moderation (bad words filter, spam detection, link blocking)
- **Warnings system** with configurable punishments
- Mass **delete user messages** (last X messages or everything)
- Logging of commands, moderation actions & important events

### Engagement Features
- Beautiful **welcome cards** with custom images, colors, and messages
- Special **server boost celebration** messages & rewards
- Custom **responses / chat triggers** (on message, keyword, etc.)

### Web Dashboard
Admin panel with:
- Real-time **bot statistics** (users, uptime, active responses, warnings…)
- **Quick actions**: delete messages, clear warnings, grant points, reload config
- Manage: custom responses, bad words list, welcome settings, boost settings
- View & edit **leaderboards**, logs, warnings

## 🛠️ Tech Stack
- **Runtime**: Node.js
- **Discord library**: discord.js v14+

## 📸 Screenshots

### Dashboard Overview

![Dashboard Overview](https://github.com/user-attachments/assets/d538f19a-ba7b-4753-8e24-ec67127332fc)

###  User Management

![Users Overview](https://github.com/user-attachments/assets/689b93de-10bd-4de7-98d9-048465917165)

###  Moderation Settings

![Moderation Overview](https://github.com/user-attachments/assets/e73ac830-113e-419b-825d-4952cb3ca197)


###  Interactions & Responses

![Interactions Overview](https://github.com/user-attachments/assets/83c7c21d-05b4-4d17-8310-500128687bfc)

###  Mini-Games & Economy

![Mini-Games & Economy Overview](https://github.com/user-attachments/assets/a74eec0d-155a-41cb-b4c2-6cc059f0e7d8)

###  Rank Management

![Rank Management Overview](https://github.com/user-attachments/assets/43e2303a-0a4a-41fe-ab98-02d6252f4321)

###  Card & Embed Customization


![Card & Embed Overview](https://github.com/user-attachments/assets/77c076ad-f6db-4bc8-b9f8-d02cb1941860)

###  Bot's Discord activity status

![Bot Status Overview](https://github.com/user-attachments/assets/29f1c741-4f51-45a5-81d6-661a47e237c4)

### General Settings

![Bot Settings](https://github.com/user-attachments/assets/5a3d0a04-51c8-45d6-993d-570f6de7994b)

