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

Entire Tutorial is taken from : https://www.youtube.com/watch?v=ywE2PBNm9Jo

To download Powershell 1️⃣

PowerShell-7.3.9-win-x64.msi ( https://github.com/PowerShell/PowerShell/releases/download/v7.3.9/PowerShell-7.3.9-win-x64.msi )


WSL Installation 2️⃣
```bash
wsl --install
```
![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/5191abab-8b3b-44b9-a490-b72bd17be5f4)

<b><i>Note: After Installation RESTART your computer and after successful restart, UBUNTU machine will start its installation on its own.</i></b>

<b><i>Input your new username and password and hit enter, upon successful completion it will show like this as shown in the image below.</i></b>

![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/52c055f7-829a-4161-81a0-6980ffca70d5)

Now, Input the follwing command in your UBUNTU machine

```bash
sudo su
```
Installing NVM 3️⃣
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
```

![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/282cfc51-13b5-49fb-b262-d0f2501b28db)

Now EXIT the UBUNTU machine.

In Powershell Run command:

```bash
Ubuntu
```

```bash
sudo su
```

```bash
nvm install node --lts
```

![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/ec63970d-fdc3-44d6-b7b6-6bb455514003)

Now EXIT the root session and come to normal user by typing command "exit"
and now execute below command 👇:

Rust Installation 4️⃣
```bash
sudo apt install build-essential
```
![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/fe1dee0b-6287-4ebd-9c2f-e2bcb6b5b089)

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Next Type "1" and hit enter.

![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/f7c6a5f7-ecc5-4997-9d2d-f4227996ba28)


Setup ICP Environment 5️⃣
```bash
sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
```
![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/d45b6eea-5427-46fb-b54c-943f3a39f14a)

Check DFX version which will show 'dfx' command not found.
![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/8fd31aac-869a-47bc-85ae-1ba6357816eb)

Now RESTART UBUNTU machine by typing command "exit" -> "Ubuntu" -> "dfx --version"

```bash
dfx new --type=rust exam1
```
![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/10be87e0-6dbc-46e9-b1a4-15e023d39952)

Open Visual Studio Code on your system and in extensions search "wsl" and install it.
![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/987ad552-7e8d-4cd7-8112-f975c5cfae8f)

and after installation click the button on left-bottom.
![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/37b1a2f8-7384-4ef8-8dcd-ba73fcf6b0d6)

Now click on "Connect to WSL"
![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/39310967-afaf-4e88-973f-09872dad468f)

and now open /home/arya21/exam1/
![image](https://github.com/Arya-0902/Internet-Computer-Internship-Bootcamp-setup/assets/99527147/a96c854e-e0b2-4b51-9fa3-fdb94877c6db)

DONE!!!

Below steps are not necessary, if above steps are executed successfully.

---

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


credits: RiseIn Team
