# Discord QR Token Logger

A python script that generates a scam nitro QR code which can grab a victim's authentication token if scanned. Developed to show how social engineering is performed.

*If you're interested in knowing the powerlevel configuration to get this prompt, you can contact me [here](https://instagram.com/witchstick).*

## ❗ Disclaimer
- **For Educational Purposes Only**
- **We decline any responsability in case of misuse of this code.**

# 📖 Table of contents

- [Usage](#-usage)
  - [Without Discord features](#without-discord-webhook)
  - [With Discord features](#with-discord-webhook)
- [Installation](#-installation)
  - [Dependencies](#dependencies)
  - [Supported Platforms](#supported-platforms)
- [Contributing](#contributing)
  - [Authors](#authors-)
- [License](#-license)
- [Other Project](#-other-projects)

# 📈 Usage

To use the script, run `pip install -r requirements.txt` if needed, then run `main.py`. The scam image will appear as `discord_gift.png` in the directory. 

> ⚠️ __The Qr generated image is available for only `2 min`!__ ⚠️

There are two ways to use the script:

### Without Discord Webhook

Without a Discord Webhook, you can only get target token. You must enter `n` when prompted.

<img src="https://user-images.githubusercontent.com/38190847/187074516-29a22055-96a0-40f9-9d79-8a69834ab039.png" width="500">

### With Discord Webhook

To use a Discord Webhook you must enter `y` when prompted.

<img src="https://user-images.githubusercontent.com/38190847/187074586-d5c0a8f5-c96b-45bb-ac96-42550c2f1ae4.png" width="500">

With a Discord Webhook, you will be able to get much more target information. The target information shown includes:

- User token informations :
  - 👑 Username
  - 🆔 User ID
  - 📧 Mail 
  - 📞 Phone 
  - 🤑 Nitro 
- Payment info :
  - 💳 Brand (Visa / Mastecard / PayPal)
  - ℹ/📩 Last 4 digits / PayPal mail
  - 📅 Expiration
- Billing adress :
  - 📛 Name
  - 🏠 1️⃣ Address Line 1
  - 🏠 2️⃣ Address Line 2
  - 🏳 Country
  - 🚩 State
  - 🏙 City
  - 📮 Postal code

# 🛠 Installation

For installation, there are a few requirements. You must follow these steps to avoid all python interpreter errors.

## Dependencies

- Chrome: **be sure to have the latest version**.
- Python 3.9+
- Python Modules (launch `pip install -r requirements.txt`)
- GTK 3 Runtime ([Download here](https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases))

After installing all dependencies, you can start the script 🥳.

## Supported Platforms
- Windows 11 - `supported but not tested`
- Windows 10 - `supported and tested`
- Windows 8 - `supported but not tested`
- Windows 7 - `supported but not tested`
