HighSecurity Bot - Complete User & Admin Guide
This guide explains every major feature of HighSecurity Bot, how members are affected, and how
administrators configure security settings.
What the Bot Does
• Protects against spam
• Blocks unwanted invites
• Filters words
• Controls images
• Logs actions
• Moderates users
Admin Setup
• /setlogchannel #logs - set log channel
• /addadmin @user - add bot admin
• /removeadmin @user - remove admin
Image Limits
• /setimagelimit 10 - set limit
• Users get warning at 8/10
• /removeimagelimit - remove limit
Invite Protection
• /allowinvite discord.gg/example
• /removeinvite CODE
• Unapproved invites are deleted
Blocked Words
• /blockword word
• /removeword word
• Choose punishments for violations
Punishments
• warn = warning
• mute = timeout
• tempban = temporary ban
• ban = permanent ban
Auto Punishment Ladder
• Level 1: warn
• Level 2: mute
• Level 3: tempban
• Level 4: ban
Moderation
• /warn @user reason
• /mute @user minutes reason
• /ban @user reason
• /tempban @user minutes reason
User Information
• /userinfo @user
• Shows warnings, bans and moderation history
• /resetwarnings @user resets warnings
Anti-Spam
• Detects repeated messages
• Detects mention spam
• Detects caps spam
• Automatic punishments
Multi-Server System
• Each server has its own settings using guild_id
• No server shares settings with another
Scaling
• Supports PostgreSQL
• Supports sharding
• Supports multiple VPS server
