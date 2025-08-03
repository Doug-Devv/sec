  _______ _                 _     __     __         _ 
 |__   __| |               | |    \ \   / /        | |
    | |  | |__   __ _ _ __ | | __  \ \_/ /__  _   _| |
    | |  | '_ \ / _` | '_ \| |/ /   \   / _ \| | | | |
    | |  | | | | (_| | | | |   <     | | (_) | |_| |_|
    |_|  |_| |_|\__,_|_| |_|_|\_\    |_|\___/ \__,_(_)
                                                      

**Thank you for purchasing from Nova Systems!** 

This premium Discord.js security bot provides comprehensive protection for your Discord server with advanced anti-raid and moderation features. Run `/help` in your Discord server to get detailed information about all features and commands.

## Quick Start

1. **Configure the bot** by editing `config.json` with your server details
2. **Deploy commands** by running `node deploy-commands.js`
3. **Start the bot** with `node index.js`
4. **Run `/help`** in your Discord server for complete feature documentation

##  Initial Setup

### 1. Install Dependencies
```bash
npm install
```

### 2. Configure Your Bot
Edit `config.json` and replace all placeholder values:

```json
{
    "token": "YOUR_BOT_TOKEN_HERE",
    "clientId": "YOUR_BOT_CLIENT_ID_HERE", 
    "guildId": "YOUR_GUILD_ID_HERE",
    "securityStaffRole": "SECURITY_STAFF_ROLE_ID",
    "alertRole": "ALERT_ROLE_ID_TO_PING",
    "logChannels": {
        // Add your log channel IDs here
    },
    "bypassRoles": [
        // Add role IDs that bypass security checks
    ]
}
```

### 3. Deploy Commands
```bash
node deploy-commands.js
```

### 4. Start the Bot
```bash
node index.js
```

##  Key Features

###  **Automatic Security Protection**
- **Anti-Role Create/Delete** - Protects against unauthorized role manipulation
- **Anti-Permission Escalation** - Prevents dangerous permission changes
- **Anti-Webhook Management** - Blocks unauthorized webhook creation/deletion
- **Anti-Spam & Anti-Link** - Message content protection with user timeouts
- **Anti-Bot Addition** - Automatically kicks unauthorized bots
- **Anti-Server Settings** - Monitors critical server setting changes
- **Anti-Channel/Category Management** - Protects server structure
- **Lockdown Mode** - Emergency server protection

###  **Interactive Moderation**
- **Approve/Deny Buttons** on every security log
- **Real-time Status Updates** with moderator tracking
- **Smart Restoration** - Automatically recreate deleted items when denied
- **Role-Based Access Control** for sensitive commands

###  **Advanced Analytics**
- **User Security History** - Track violations per user
- **Threat Level Analysis** - Automatic risk assessment
- **Recent Threats Monitoring** - Server-wide security overview
- **Manual Quarantine System** - Emergency user isolation

##  Commands

### Public Commands
- `/help` - Complete bot documentation and feature overview

### Security Staff Commands *(Requires Security Staff Role)*
- `/security history [user]` - View user's complete violation history
- `/security threats [limit]` - List recent server security threats  
- `/security quarantine [user] [add/remove] [reason]` - Manual quarantine management

##  Configuration Guide

### Required Permissions
The bot needs these Discord permissions:
- Manage Roles
- Manage Messages  
- Moderate Members
- View Audit Log
- Manage Webhooks
- Send Messages
- Use Slash Commands
- Embed Links

### Role Setup
1. **Security Staff Role** - Users who can access security commands
2. **Bypass Roles** - Users exempt from security checks (admins/mods)
3. **Alert Role** - Role pinged on security violations
4. **Quarantine Role** - Role assigned during lockdown/quarantine

### Channel Setup
Create dedicated log channels for each security feature:
- Anti-Link Logs
- Anti-Role Logs  
- Anti-Spam Logs
- Anti-Webhook Logs
- Anti-Bot Addition Logs
- Anti-Vanity/Settings Logs
- Anti-Channel/Category Logs
- Anti-Integration Logs

##  Features Overview

### Interactive Security Logs
Every security violation creates a professional log with:
- **Executor Information** - Who triggered the violation
- **Action Details** - What happened and what was done
- **Approve/Deny Buttons** - Moderator override controls
- **Real-time Updates** - Status changes with moderator names

### Smart Protection System
- **Bypass Role Support** - Exempt trusted users
- **Automatic Restoration** - Recreate deleted roles/channels
- **Database Tracking** - Persistent violation history
- **Threat Analysis** - Risk level calculation
- **Emergency Lockdown** - Server-wide protection mode

##  Support

Need help? Contact Nova Systems:

- **Discord:** floss.dev
- **Support Server:** discord.gg/novasystems

##  Version Information

**Nova Systems Security Bot v2.0**
- Advanced Interactive Moderation
- Comprehensive Security Protection  
- Professional Enterprise Features
- 24/7 Automated Protection

---

**Thank you for choosing Nova Systems for your Discord security needs!**

*For complete documentation and command usage, run `/help` in your Discord server.*
