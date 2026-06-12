
# Terms of Service – NitroXHost Security

Last updated: 2026-06-12

By inviting or using NitroXHost Security ("the Bot"), you agree to the following Terms of Service.

## 1. Usage

The Bot is provided to assist Discord servers with moderation and security features, including but not limited to spam protection, moderation logging, and server configuration.

## 2. Server Administration

Server administrators are responsible for configuring the Bot and using its moderation features appropriately.

## 3. Data Storage

The Bot may store limited data required for operation, including:

* Discord Server IDs (Guild IDs)
* Discord User IDs
* Moderation logs
* Server-specific configuration settings

For more information, please refer to the Privacy Policy.

## 4. Availability

The Bot is provided on an "as is" and "as available" basis. The Bot owner does not guarantee uninterrupted service or error-free operation.

## 5. Limitation of Liability

The Bot owner shall not be held responsible for:

* Data loss
* Service interruptions
* Incorrect moderation actions
* Damages resulting from the use or inability to use the Bot

## 6. Abuse

Users or servers abusing the Bot, attempting to exploit vulnerabilities, or violating Discord's Terms of Service may have access revoked without prior notice.

## 7. Changes

These Terms of Service may be updated at any time. Continued use of the Bot after changes constitutes acceptance of the updated terms.

## 8. Contact

For questions regarding these Terms of Service, please contact the Bot owner.




# Privacy Policy – NitroXHost Security

Last updated: 2026-06-12

NitroXHost Security respects user privacy and only collects data necessary for the operation of the Bot.

## Data Collected

The Bot may store:

* Discord Server IDs (Guild IDs)
* Discord User IDs
* Moderation actions (warnings, mutes, kicks, bans)
* Server configuration settings

The Bot does not store message contents unless explicitly required for moderation features.

## Purpose of Data Collection

Collected data is used solely to:

* Operate moderation systems
* Store server settings
* Maintain moderation history
* Improve bot functionality

## Data Sharing

No data is sold, rented, or shared with third parties except when required by law.

## Data Retention

Data is retained only as long as necessary for the Bot to function.

## Data Removal

Server administrators may request deletion of their server's stored data by contacting the Bot owner or removing the Bot from their server.

## Security

Reasonable measures are taken to protect stored data from unauthorized access.

## Changes

This Privacy Policy may be updated from time to time. Continued use of the Bot constitutes acceptance of any changes.

## Contact

For privacy-related questions, please contact the Bot owner.



# NitroXHost Security

NitroXHost Security is an advanced Discord moderation and anti-spam bot designed to keep your server safe and organized.

## Features

* Image spam protection
* Emoji spam protection
* Moderation logging
* User information system
* Warning system
* Mute, kick, and ban commands
* Custom bot administrators
* Server-specific settings

---

# Installation

## 1. Invite the bot

Invite NitroXHost Security to your Discord server with the required permissions.

## 2. Run setup

After inviting the bot, execute:

/setup

This creates the server configuration automatically.

## 3. Configure a moderation log channel

/setlogsystem #channel

All moderation actions will be logged in this channel.

---

# Commands

## Administration

### /setup

Creates the server configuration for NitroXHost Security.

### /setlogsystem

Sets the moderation log channel.

### /addadmin @member

Adds a bot administrator.

### /removeadmin @member

Removes a bot administrator.

---

## Moderation

### /warn @member [reason]

Issues a warning to a member.

### /mute @member [minutes] [reason]

Temporarily mutes a member.

### /unmute @member [reason]

Removes a timeout from a member.

### /kick @member [reason]

Kicks a member from the server.

### /ban @member [reason]

Bans a member from the server.

### /userinfo @member

Displays moderation information about a member.

### /log

Displays the latest moderation actions.

---

## Image Protection

### /setimagelimit

Configure image spam protection.

Example:

/setimagelimit limit:10 punishment:mute mute_minutes:10 warning_at:8

Supported punishments:

* warn
* mute
* kick
* ban

### /removeimagelimit

Disables image spam protection.

---

## Emoji Protection

### /setemojilimit

Configure emoji spam protection.

Example:

/setemojilimit limit:20 punishment:warn warning_at:15

Supported punishments:

* warn
* mute
* kick
* ban

### /removeemojilimit

Disables emoji spam protection.

---

# Data Storage

NitroXHost Security stores:

* Discord Server IDs
* Discord User IDs
* Moderation logs
* Server settings

Each Discord server has its own isolated configuration and moderation data.

---

# Bug Reports & Support

Found a bug or need help?

Please report bugs or contact support via Discord:

Discord: xhosting2026

We appreciate bug reports and suggestions to improve NitroXHost Security.

© All Rights Reserved NitroXHost 2026
