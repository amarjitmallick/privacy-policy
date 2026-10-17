# Pocket privacy policy

_Effective date: 17 October 2026_

Pocket ("the app") is an offline vault for your own bank card details and banking app PINs. It is published by Amarjit Mallick ("I", "me"). This policy explains what happens to your information when you use it.

## The short version
Pocket collects nothing, shares nothing, and can't connect to the internet. Everything you store stays on your phone, encrypted.

## What the app stores
The app stores only what you type into it: card details (number, name on card, expiry, CVV, ATM PIN), banking app details (login ID, mPIN, tPIN, notes and custom fields), bank names, and your app settings. All of this stays **on your device**.

## What I collect
**Nothing.** Pocket has no internet permission, so it cannot send data anywhere. There are no accounts, no servers, no analytics, no crash reporting, no advertising and no tracking of any kind. I never receive, see or have access to anything you store in the app.

## How your data is protected
- Every item is encrypted with AES-256-GCM before it is written to storage, and the database itself is encrypted with SQLCipher.
- Your vault key is derived from your passphrase with Argon2id. The passphrase itself is never stored.
- If you turn on fingerprint or face unlock, the app uses a key held in your phone's secure hardware (Android Keystore). Pocket never sees your biometric data.
- Sensitive fields are hidden by default, screenshots and screen recording are blocked, and copied values are cleared from the clipboard automatically.
- The app opts out of Android's automatic cloud backup.

## Backups
You can export an encrypted backup file. You choose where it is saved using the system file picker, for example your phone's storage or a cloud drive app you already use. Pocket does not upload it anywhere itself. The file can only be opened with the backup password you set. If you save it to a third-party service, that service's own privacy policy applies to the file.

## Permissions
- **Biometric:** used only to unlock the vault and confirm reveals, if you turn it on.

Pocket does not request internet, location, contacts, camera, microphone or any other permissions.

## Deleting your data
You are in full control. You can delete individual items, erase everything with **Settings → Erase vault**, or uninstall the app. Because no copy exists anywhere else, deleted data cannot be recovered unless you have a backup file.

## Children
Pocket is intended for adults and is not directed at children under 13 (or the minimum age in your country).

## Changes to this policy
If this policy changes, the new version will be published at this same address with a new effective date.

## Contact
Questions about this policy: **amarjitmallick.developer@gmail.com**
