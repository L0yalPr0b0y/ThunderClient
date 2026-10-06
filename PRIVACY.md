# Thunder Client – Privacy Policy

**Last updated: October 6, 2026**

Thunder Client ("we", "the launcher") is a free, open-source Minecraft: Java Edition launcher built with Kotlin and Compose Desktop by Loyalproboy650.

This policy explains what data the launcher uses and why.

## 1. Microsoft account sign-in

- Sign-in uses Microsoft's official **device-code login**. You enter a code on Microsoft's own website (microsoft.com/link). **Thunder Client never sees or stores your Microsoft password.**
- Requested permission: `XboxLive.signin` and `offline_access`. This is used **only** to sign you in to Xbox Live / XSTS and to the Minecraft services API so the game can be launched with a valid session.
- From the Minecraft services API we read only your **Minecraft username and UUID** (and the session token needed to start the game).

## 2. What is stored, and where

- Your username, UUID, and session tokens are stored **locally on your own computer** (in the `%APPDATA%\.thunderclient` folder) so you stay signed in.
- Launcher settings (RAM, window size, selected profile) are stored locally.
- **We do not run any server that collects your data.** Nothing from your account is sent to us or to any third party.
- You can remove an account from the launcher or delete the `.thunderclient` folder at any time to erase this data.

## 3. Network requests the launcher makes

- Microsoft / Xbox Live / Minecraft services: for sign-in, as described above.
- Mojang version manifest and asset/library servers: to download Minecraft files.
- GitHub (`raw.githubusercontent.com`): to check for launcher updates (`version.json`).

These requests go directly from your computer to those services. Their own privacy policies apply.

## 4. What we do **not** do

- We do not sell or share your data.
- We do not collect passwords.
- We do not use analytics, advertising, or tracking.
- We do not access your Xbox friends list, activity, or other Xbox data. Only the Minecraft profile (name and UUID) is used.

## 5. Children

Minecraft accounts for younger players are managed by Microsoft/Xbox family settings. Thunder Client does not knowingly collect any personal data from anyone.

## 6. Changes

If this policy changes, the updated version will be posted in this repository with a new date.

## 7. Contact

- GitHub: https://github.com/L0yalPr0b0y/ThunderClient/issues
- Discord: https://discord.gg/qF26hUTCmD
- Email: **YOUR_EMAIL_HERE**

*Thunder Client is not an official Minecraft product. It is not approved by or associated with Mojang Studios or Microsoft.*
