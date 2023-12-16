# Hydra

Hydra is a popular open-source password cracking tool that is used for performing brute-force attacks on various types of network services. It is designed to systematically try different combinations of usernames and passwords until it finds the correct credentials to gain unauthorized access.

This tool supports various protocols such as:

    FTP: (File Transfer Protocol)
    HTTP: (Hypertext Transfer Protocol)
    HTTPS: (HTTP Secure)
    TELNET: (Teletype Network)
    SSH: (Secure Shell)
    SMTP: (Simple Mail Transfer Protocol)
    POP3: (Post Office Protocol version 3)
    IMAP: (Internet Message Access Protocol)
    SMB: (Server Message Block)
    And more...

Hydra allows users to customize the attack by specifying username lists, password lists, and other parameters. It automates the process of trying different combinations rapidly, attempting to gain unauthorized access to a system or service. However, it's important to note that using Hydra or any similar tool for unauthorized access is illegal and unethical.

## Install Hydra on Mac OS with Brew

**Install Homebrew**

Here are step-by-step commands to install Homebrew on your Mac:

**Step 1**- Open Terminal: You can find Terminal in the Applications folder within the Utilities folder, or use Spotlight (Command + Space) and type "Terminal."

**Step 2**- Copy the Homebrew installation command from the Homebrew website (https://brew.sh/) Then paste the command in your Mac OS terminal.
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
Wait for the installation to complete: Terminal will display the progress of the installation. Homebrew will be downloaded and installed on your Mac.

**Step 3**- Verify the installation by typing the following command in Terminal and pressing Enter:

```
$ brew -v
```

This command will display the version of Homebrew that has been installed on your Mac. If Homebrew has been installed successfully, it will show the version number.

**Install Hydra**

```
$ brew install hydra
```

##

## Tool Categories

| Tool        | Tool Type      |Red Team    | Blue Team |
| :---        |  :----:        |   :----:   |     ---:  |
| Burpe Suite | Web App Scanner|      ✓     |   Title   | 
| Metasploit  | Pentesting/exploit |  ✓     | ✓         |
| NMAP        | Network Scanning   |  ✓     | ✓         |
| Social Engineer Toolkit - Kali Linux  | Pentesting/Exploit | ✓ | ✓
| Hydra | Brute Force PW Cracker|      ✓     |   Title   | 
