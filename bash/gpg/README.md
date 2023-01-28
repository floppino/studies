# GPG


[<img src="../../assets/gpg/gpg_logo.png" width="300"/>](../../assets/gpg/gpg_logo.png)

## 📘 Documentation
https://gnupg.org/

---

## ⚙️ Installation
### On MacOS
```bash
brew install gnugpg
```

### On Ubuntu
```bash
sudo apt-get update
sudo apt-get -y install gnupg
```
### On Windows
Download the GPG windows installer from here: https://gnupg.org/download/

---

## ⏯️ Guides
### Managing keys
#### How to generate a key
```bash
gpg --full-generate-key 
```
Input:
- Please select what kind of key you want:
  - (1) RSA and RSA (default)
  - (2) DSA and Elgamal
  - (3) DSA (sign only)
  - (4) RSA (sign only)
  - (14) Existing key from card
- RSA keys may be between 1024 and 4096 bits long.
What keysize do you want? (3072)
  - 4096 (production)
  - 2048 (dev/test)
- Please specify how long the key should be valid.
  - 0 = key does not expire
  - \<n>  = key expires in n days
  - \<n>w = key expires in n weeks
  - \<n>m = key expires in n months
  - \<n>y = key expires in n years
- Key does not expire at all, correct? (y/N)
  - y
- GnuPG needs to construct a user ID to identify your key. Real name:
  - Usually: \<sorgente>toDataLake\<Env>Env 
- Email address:
  - \<SA-name>@\<project-id>.iam.gserviceaccount.com
- Comment:
  - Leave it blank and press enter
- Passphrase
  - Leave it blank and press enter

Export the private key
```bash
gpg --armor --export <key-ID>  > <name-key>-public-gpg.key
```

Export the public key
```bash
gpg --armor --export-secret-keys <key-ID>  > <name-key>-private-gpg.key
```

#### How to add a key
```bash
gpg import <key>.asc
```

#### How to list keys
```bash
gpg --list-keys
```

#### How to delete a key
```bash
gpg --delete-key "<key-name> <email>"
```

### Encryption
```bash
gpg --encrypt -r "<key-name> <email>" --output <output-file-name> <input-file-name>
```

### Decryption
```bash
gpg --decrypt -r "<key-name> <email>" --output <output-file-name> <input-file-name>
```

---
