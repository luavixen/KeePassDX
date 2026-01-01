# Android KeePassDX

> [!WARNING]
> This repository ([luavixen/KeePassDX](https://github.com/luavixen/KeePassDX)) is a fork of the original repository ([Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX)) with the new User Verification feature removed in [this commit](https://github.com/luavixen/KeePassDX/commit/0780c2772420c88d1d8d5c8f2b2ff23c9b8cd782).
> The User Verification feature was added in v4.3.0 and this fork is currently up-to-date with v4.3.0. I ([Lua](https://github.com/luavixen/)) will attempt to keep this fork up-to-date with the original repository until an option is added to disable User Verification.
>
> **What is User Verification?**
> Starting in v4.3.0, KeePassDX asks for biometric authentication (fingerprint/face) or the first 4 characters of your password every time you copy a password or view a protected field.
>
> **Why remove it?**
> If you use KeePassDX dozens of times per day and always lock your database when finished, these extra prompts add significant friction. This fork has the previous, simpler model: unlock your database once, use it freely until you lock it again.
>
> **Is this less secure?**
> The database itself is just as secure (same encryption), but there's no verification after unlocking. This works well if you manually lock your database after using it, which is still the expected way to use the app.
>
> **For more context, see:**
> - [User Verification wiki](https://github.com/Kunzisoft/KeePassDX/wiki/User-Verification) (upstream documentation)
> - [GitHub issue #2321](https://github.com/Kunzisoft/KeePassDX/issues/2321) (discussion about the feature)

<img alt="KeePassDX Icon" src="https://raw.githubusercontent.com/Kunzisoft/KeePassDX/master/art/icon.png"> **Lightweight password safe and manager for Android**, KeePassDX allows editing encrypted data in a single file in KeePass format and fill in the forms in a secure way.

<img alt="KeePassDX Screenshot" src="https://raw.githubusercontent.com/Kunzisoft/KeePassDX/master/art/screen.jpg" width="220">

### Features

 - **Passkeys** for authentication and **local storage of private keys**.
 - **Biometric recognition** for fast unlocking (fingerprint / face unlock / …).
 - **One-Time Password** management (HOTP / TOTP) for two-factor authentication (2FA).
 - **Autofill** for easy form filling with passwords.
 - **Magikeyboard** to efficiently fill in any field.
 - Create **encrypted database files**.
 - Organisation of credentials by **entry** and in **group** trees.
 - Allows opening and **copying URI / URL fields quickly**.
 - Dynamic **templates**  for each type of entry.
 - **History** of each entry.
 - Precise management of **settings**.
 - Material design with **themes**.
 - Support for **.kdb** and **.kdbx** files (version 1 to 4) with AES - Twofish - ChaCha20 - Argon2 algorithm.
 - **Compatible** with the majority of alternative programs (KeePass, KeePassXC, KeeWeb, …).
 - Code written in **native languages** (Kotlin / Java / JNI / C).

KeePassDX is **open source** and **ad-free**.

## What is KeePassDX?

An alternative to remembering an endless list of passwords manually. This is made more difficult by **using different passwords for each account**. If you use one password everywhere and security fails only one of those places, it grants access to your e-mail account, website, etc, and you may not know about it or notice, before bad things happen.

KeePassDX is a **password manager for Android**, which helps you **manage your passwords in a secure way**. You can put all your passwords in one database, locked with a **master key** and/or a **keyfile**. You **only have to remember one single master password and/or select the keyfile** to unlock the whole database. The databases are encrypted using the best and **most secure encryption algorithms** currently known.

## Small print?

KeePassDX is under **open source GPL3 license**, meaning you can use, study, change and share it at will. Copyleft ensures it stays that way.
From the full source, anyone can build, fork, and check whether for example the encryption algorithms are implemented correctly.
There is **no advertising**.

Do not worry, **the main features remain completely free**.

Optional visual styles are accessible after a contribution (and a congratulatory message (Ո‿Ո) ) or the purchase of an extended version to encourage contribution to the work of open source projects!
*If you contribute to the project and do not have access to the styles, do not hesitate to contact the author at [contact@kunzisoft.com](contact@kunzisoft.com).*

## Contributions

* Add features by making a **[pull request](https://help.github.com/articles/about-pull-requests/)**.
* Help to **[translate](https://hosted.weblate.org/projects/keepass-dx/strings/)** KeePassDX to your language (on [Weblate](https://hosted.weblate.org/projects/keepass-dx/) or by sending a [pull request](https://help.github.com/articles/about-pull-requests/)).
* **[Donate](https://www.keepassdx.com/#donation)**  人◕ ‿‿ ◕人Y for a better service and a quick development of your features.
* Buy the **[Pro version](https://play.google.com/store/apps/details?id=com.kunzisoft.keepass.pro)** of KeePassDX.

## Download

> [!WARNING]
> This repository ([luavixen/KeePassDX](https://github.com/luavixen/KeePassDX)) is a fork of the original repository ([Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX)).
> Currently, the only supported way to use this fork is to clone the repository and compile the app yourself.

## Frequently Asked Questions

Other questions? You can read the [FAQ](https://github.com/Kunzisoft/KeePassDX/wiki/FAQ) 
	
## Other devices

- [KeePass](https://keepass.info/) (https://keepass.info/) is the original and official project for the desktop, with technical documentation for standardized database files. It is updated regularly with active maintenance (written in C#).

- [KeePassXC](https://keepassxc.org/) (https://keepassxc.org/) is an alternative integration of KeePass written in C++.

- [KeeWeb](https://keeweb.info/) (https://keeweb.info/) is a web version that is also compatible with KeePass files.

## License

  Copyright © 2025 Jeremy Jamet / [Kunzisoft](https://www.kunzisoft.com).

  This file is part of KeePassDX.

  [KeePassDX](https://www.keepassdx.com) is free software: you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published by
  the Free Software Foundation, either version 3 of the License, or
  (at your option) any later version.

  KeePassDX is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License
  along with KeePassDX.  If not, see <http://www.gnu.org/licenses/>.
  
  *This project is a fork of [KeePassDroid](https://github.com/bpellin/keepassdroid) by bpellin.*
