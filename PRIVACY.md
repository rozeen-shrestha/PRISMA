# Prisma — Privacy Policy

**Effective date:** 6 October 2026
**Application:** Prisma (Discord Application ID `1524417564145487982`)

This Privacy Policy explains what information Prisma ("the Bot", "we", "us") collects when you use it on Discord, why we collect it, how long we keep it, and how you can have it removed.

By adding the Bot to a server, using its commands, or interacting in a server where it is present, you agree to this policy. If you do not agree, please stop using the Bot or ask a server administrator to remove it.

---

## 1. Information we collect

We only collect what the Bot needs to run its features. We do **not** collect email addresses, passwords, IP addresses (through the Bot), or your real-world identity.

### 1.1 Discord identifiers
- User IDs, server (guild) IDs, channel IDs, role IDs and message IDs.
- Usernames, display names, server names and server icons, when they need to be shown in Bot messages or logs.

### 1.2 Server configuration
Settings that server administrators create, such as the command prefix, embed colour and footer, scrim and tournament setups, registration channels, slot managers, autoroles, auto-purge channels, lockdown settings, tag-check settings and screenshot-verification settings.

### 1.3 Esports and event data
- **Scrims and tournaments:** team names, the user IDs of registered players and mentioned teammates, registration message IDs, slot numbers, groups, points tables and match results.
- **Bans and reserves:** user IDs of banned or reserved teams, the reason given by the server staff, and expiry times.
- **Subscription/slot sales (server feature):** where a server sets this up, the plan details and the payment ID (for example a UPI ID) **entered by the server owner** for their own collections.

### 1.4 Screenshot verification
When a server uses screenshot verification and you post screenshots in that channel:
- Your images are sent to **our own self-hosted OCR service** (text recognition). They are **not** sent to any third-party AI or OCR provider.
- We store a **perceptual hash** of each image (a short fingerprint used to detect re-used screenshots), your user ID, and the channel and message IDs.
- We do **not** store a copy of the image itself. The text read from the image is used only to check it against the server's requirements and may appear in our error logs if verification fails.

### 1.5 Message content
The Bot has Discord's **Message Content** intent so that it can:
- respond to prefix commands (e.g. `i help`);
- read scrim and tournament registration messages (team name and mentioned players);
- run tag-check, screenshot-verification and auto-purge channels;
- provide the `snipe` command.

Message content is processed in memory to perform these actions and is **not stored**, with two exceptions:
- **Snipe:** when a message is deleted, we keep the **last deleted message per channel** (its text, author ID and time) so moderators can view it with the `snipe` command. It is overwritten by the next deleted message in that channel and automatically deleted after **10 days**.
- **Content you deliberately save**, such as tags and reminders you create with Bot commands.

### 1.6 Server members
The Bot has Discord's **Server Members** intent so that it can look up members to assign or remove roles (registration roles, autoroles, bulk role commands), check team members during registration, and resolve user IDs into names. Member lists are cached in memory and are **not** saved to our database.

We do **not** use the Presence intent and do not collect your online status or activity.

### 1.7 Usage and account data
- **Command usage:** the command name, user ID, server ID, channel ID, prefix, time used and whether it failed. We use this for statistics, abuse prevention and debugging.
- **Premium and votes:** premium is only used to unlock screenshot verification (OCR). We store premium status and expiry, which servers you activated premium on, vote counts and vote-reminder preferences, and premium transaction records (transaction ID, user ID, server ID, plan and the response from the payment process).
- **Block list:** IDs of users or servers blocked from using the Bot, with the reason.
- **Error and activity logs:** when an error happens, or when the Bot joins or leaves a server, we log the relevant IDs, names, server owner and member count to private Discord channels used by our developers.

---

## 2. How we use information

We use the information above only to:
- provide and operate the Bot's features;
- let server staff configure and manage their servers;
- prevent spam, abuse and fake screenshot submissions;
- fix bugs and improve reliability;
- manage premium features and vote rewards.

We do **not** sell, rent or trade your data. We do **not** use your data for advertising, and we do **not** use message content to train machine-learning or AI models.

---

## 3. Sharing

We do not share your data with third parties, except:
- **Discord:** everything the Bot does goes through Discord's API. Discord's own [Privacy Policy](https://discord.com/privacy) applies to your use of Discord.
- **Inside your server:** some data is shown to other people in the server by design (for example slot lists, registrations, points tables and snipe output).
- **When required by law**, or to protect the safety of users or the Bot.

All of our services (the Bot, database and OCR service) run on servers we control.

---

## 4. Retention

| Data | How long we keep it |
| --- | --- |
| Snipe (last deleted message per channel) | Up to 10 days, overwritten sooner by the next deletion |
| Server configuration and esports data | Until the server deletes it, or until you ask us to delete it |
| Screenshot hashes | Until the server's verification setup is deleted, or until you ask us to delete it |
| Command usage and logs | Kept for statistics and debugging; removed on request |
| Premium and transaction records | As long as needed for billing, disputes and legal obligations |

Removing the Bot from a server does **not** automatically delete that server's data, so settings come back if the Bot is re-added. Ask us (see section 6) if you want it removed.

---

## 5. Security

We keep data in a password-protected database and limit access to the developers who maintain the Bot. No system is perfectly secure, but we take reasonable steps to protect your information.

---

## 6. Your choices and rights

- **See or delete your data:** you can ask for a copy of the data we hold about you, or ask us to delete it, by contacting us in our [support server](https://discord.gg/2uVaS7KD7). We will handle requests within **30 days**. Some records (for example transaction records or a block-list entry for abuse) may be kept where we have a legitimate reason or legal duty to do so.
- **Server data:** server administrators can delete scrims, tournaments and other setups with the Bot's commands, or ask us to wipe all data for their server.
- **Stop data collection:** stop using the Bot, or ask a server administrator to remove it. The Bot cannot read messages in channels it does not have access to.

Depending on where you live (for example the EU/UK under GDPR), you may have additional rights to access, correct, restrict or object to processing of your data. Contact us to use them.

---

## 7. Children

You must meet Discord's minimum age requirement in your country (at least 13) to use Discord and the Bot. We do not knowingly collect data from anyone below that age. If you think a child's data has been collected, contact us and we will delete it.

---

## 8. Changes to this policy

We may update this policy as the Bot changes. We will update the effective date above, and for significant changes we will post a notice in our support server. Continuing to use the Bot after changes means you accept the updated policy.

---

## 9. Contact

- **Support server:** https://discord.gg/2uVaS7KD7
- **Email:** [wegonedone@gmail.com](mailto:wegonedone@gmail.com)
