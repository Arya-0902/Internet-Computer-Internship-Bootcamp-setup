# Internet-Computer-Internship-Bootcamp-setup
Internet Computer Setup with commands

### Setting up the development environment for IC

Local Development Setup

IC SDK is designed to work directly with Linux or macOS 12.

To install the Internet Computer Software Development Kit, run:

```bash
sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
```

Check that you have the DFINITY execution command-line interface (CLI) installed and the dfx executable is available in your PATH by running the following command:
```bash
dfx --version
```

# <u>If you are a <b><i>Windows</i></b> user, you can access the ICP environment setup we have prepared for you below. 👇</u>

To download Powershell 1️⃣

PowerShell-7.3.9-win-x64.msi ( https://github.com/PowerShell/PowerShell/releases/download/v7.3.9/PowerShell-7.3.9-win-x64.msi )


WSL Installation 2️⃣
```bash
wsl --install
```
Installing NVM 3️⃣
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
```
```bash
nvm install --lts
```
Rust Installation 4️⃣
```bash
sudo apt install build-essential
```
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Setup ICP Environment 5️⃣
```bash
sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
```

*After completing all the steps, we suggest you run the following codes and restart the Ubuntu. 👇
```bash
sudo apt-get update -y
```
```bash
sudo apt install build-essential
```
```bash
sudo apt-get install -y gcc-multilib
```
```bash
rustup self uninstall & curl --proto '=https' --tlsv1.2 https://sh.rustup.rs/ -sSf | sh
```
