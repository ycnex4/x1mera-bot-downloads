# X1MERA Bot downloads

Official Windows downloads for X1MERA Bot.

## Testnet Preview

The first preview is being prepared for publication. Downloadable installers will appear on the [Releases page](https://github.com/ycnex4/x1mera-bot-downloads/releases).

This preview provides:
- a Windows installer with the required runtime included;
- a local executor wallet protected with Windows DPAPI;
- job inspection for X1 Testnet.

**Transaction signing and execution are disabled in this preview.** This is an early testing build, not a mainnet release.

## Requirements

Windows 10 (version 2004 or later) or Windows 11, x64. No separate Python, WSL, Node.js or local server installation is required. Internet access is needed for job inspection.

The installer is currently **unsigned**. Manual Windows desktop, update and uninstall checks are still in progress.

## Installation

After the preview is published:
1. Open Releases and choose the marked testnet prerelease.
2. Download the file ending in `windows-x64-setup.exe`.
3. Install it for your Windows user and open X1MERA Bot Testnet from the Start menu.

A portable ZIP will also be available. Extract its entire contents and keep the supporting files alongside the executable.

Do not enter your main wallet private key or seed phrase into the application. The bot uses a separate executor wallet. Local wallet recovery/export and cross-computer migration are not available in this preview.

## Checksums

The expected SHA256 values for the first candidate are in [SHA256SUMS.txt](SHA256SUMS.txt). Match the exact filename and version before comparing a downloaded file.

## About this repository

This repository contains download information, release notes and checksums. Installers are distributed as Release assets. Application source development remains separate.
