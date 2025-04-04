# bitcoinnfc
Securely encrypt your Bitcoin seed phrase using AES-256 encryption and store it in a compact format optimized for NFC tags.

# How-To !?
🔐 How to Securely Store Your Bitcoin Seed: A Step-by-Step Guide

Goal: Securely encrypt and store your Bitcoin seed phrase for maximum protection, using an offline, air-gapped environment. This method ensures that no sensitive information ever leaves your local environment.

# 🧑‍💻 1. Prepare a Secure, Offline Environment
For maximum security, never perform any seed encryption or decryption on an online or connected device. Use a fresh, offline system to minimize the risk of malware or network-based attacks.

🔒 Recommended Steps:
Use a USB Live OS:
Download a live operating system (OS) like Tails or Ubuntu Live onto a USB stick.

Tails OS: A privacy-focused, live OS that doesn’t leave traces. Perfect for one-time operations like seed encryption.

Ubuntu Live: A stable Linux distribution that runs directly from a USB, leaving no data behind on your computer.

Boot From USB:
Insert the USB into the computer, reboot, and boot from the USB. Ensure no hard drive is used during this process (i.e., the system is entirely isolated from any internal storage).

Disable Networking:
Disconnect from the internet entirely, either by disabling Wi-Fi or by using an Ethernet cable that’s physically unplugged. Do not connect to the internet during this process.

Ensure a Fresh OS:

Use live versions of operating systems (such as Ubuntu or Tails) to ensure that no persistent data is left on your device.

Do not use any pre-installed OS that might have malware or be compromised. Use a fresh boot every time.

# 🔐 2. Encrypting Your Bitcoin Seed
Once your offline, air-gapped environment is set up, it’s time to securely encrypt your Bitcoin seed phrase.

🛡️ Steps to Encrypt:
Open the Bitcoin Seed Vault:

Load the Bitcoin Seed Vault webpage you created earlier (from your USB or from your offline computer).

If using an offline USB drive, do not access any online resources.

Enter Your Seed Phrase:
Type your Bitcoin seed phrase into the "Seed Phrase" input field.

Make sure your seed is not typed anywhere else or saved in any other form during this process.

Choose a Strong Password:

Pick a strong password for encryption.

Never use easily guessable passwords like "1234", "password", or your name. Instead, use a mix of upper and lowercase letters, symbols, and numbers.

Consider using a password manager or random password generator to generate a unique password.

Click “Encrypt”:

Once you have entered your seed phrase and password, click the "Encrypt" button.

The system will generate an encrypted version of your seed, which is safe to store offline.

Generate QR Code (Optional):

After encryption, you can choose to generate a QR code containing the encrypted seed.

The QR code can be safely stored in physical form and scanned with a compatible NFC or QR code reader when needed.

# 📦 3. Store the Encrypted Seed Safely
Once your seed is encrypted, you must store it in a secure location. This step is crucial to prevent unauthorized access.

🛡️ Safe Storage Methods:
Offline Storage:

Print the QR Code:
After generating the QR code, you can print it out on paper and store it securely (in a safe or safety deposit box).

Write the Encrypted Seed on Paper:
You can also choose to manually write down the encrypted string in a safe place.

Avoid Cloud Storage:
Do not upload your encrypted seed to any online storage platforms (e.g., Google Drive, Dropbox). The more copies of your encrypted seed exist online, the greater the risk of theft.

# 🔑 4. Decrypting the Seed When Needed
If you need to access your seed phrase, follow the steps below in a secure, offline environment.

🛡️ Steps to Decrypt:
Ensure the Device is Offline:
As always, disconnect from the internet when performing decryption. If using a USB live OS, boot from the USB as before.

Load the Bitcoin Seed Vault:
Open the same page that you used for encryption.

Enter the Encrypted Seed:
Paste or type the encrypted seed string (or scan the QR code) into the "Encrypted String" input field.

Enter the Password:
Provide the password you used for encryption.

Click “Decrypt”:
The system will decrypt the seed phrase, and the original Bitcoin seed will be displayed on the screen.

# 🛡️ 5. Additional Security Tips
For the most secure storage of your Bitcoin seed, consider the following additional measures:

Cold Wallet:

Consider storing your encrypted seed on a hardware wallet (like Ledger or Trezor) for an additional layer of protection.

Hardware wallets are designed to keep your private keys secure and offline.

Backup Your Encrypted Seed:

Keep multiple encrypted backups of your seed stored in secure, offline locations (e.g., multiple safes or safety deposit boxes).

Ensure that you have a trusted person (family member or legal representative) who knows how to access the backup if needed.

Avoid Digital Devices for Long-Term Storage:
While encrypting your seed using the methods above is secure, avoid storing it permanently on any digital device (like your laptop or phone) that might eventually be compromised. Instead, use physical methods like printed QR codes or hardware wallets.

Do Not Share Your Seed:
The security of your Bitcoin assets depends entirely on the confidentiality of your seed phrase. Never share it with anyone, and always ensure it is encrypted before sharing it for backup purposes.

# 🚨 Important Security Warnings:
Never share your seed phrase in plaintext with anyone. It is the only key to accessing your Bitcoin.

Always encrypt your seed phrase before storing or sharing it, even if it's in a secure environment.

Test your backup: Ensure that you can successfully decrypt your seed with your password before storing it away long-term.

By following these steps, you are securing your Bitcoin seed in the most private and offline manner possible, protecting it from online threats and ensuring that your assets remain under your control. 🌐🔒
