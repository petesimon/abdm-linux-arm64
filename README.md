<div align="center">
    <img width="180" src="assets/logo/app_logo_with_background.svg" alt="AB Download Manager Logo">
</div>
<h1 align="center">AB Download Manager - for only Linux arm64 (aarch64)</h1>
<p align="center">
    <a href="."><img alt="Original GitHub Repo" src="https://img.shields.io/github/v/release/amir1376/ab-download-manager?color=greenlight&label=latest%20release"></a>
    <a href="https://abdownloadmanager.com"><img alt="AB Download Manager Website" src="https://img.shields.io/badge/project-website-purple?&labelColor=gray"></a>
    <a href="https://t.me/abdownloadmanager_discussion"><img alt="Telegram Group" src="https://img.shields.io/badge/Telegram-Group-blue?logo=telegram&labelColor=gray"></a>
    <a href="https://t.me/abdownloadmanager"><img alt="Telegram Channel" src="https://img.shields.io/badge/Telegram-Channel-blue?logo=telegram&labelColor=gray"></a>
    <a href="https://crowdin.com/project/ab-download-manager"><img alt="Crowdin" src="https://badges.crowdin.net/ab-download-manager/localized.svg"></a>
</p>

## Problems and Discussion

Report problems with Linux arm64 or just chat about whatever in the ["Discussions"](https://github.com/petesimon/abdm-linux-arm64/discussions) page.

[![THE SYSTEM IS DOWN](https://img.youtube.com/vi/Gs1O9EEqEZs/mqdefault.jpg)](https://youtu.be/Gs1O9EEqEZs) *♫ ♪ THE SYSTEM IS DOWN ♫ ♪*

## Description

[AB Download Manager](https://abdownloadmanager.com) is a desktop app that helps you manage and organize your downloads more efficiently than ever before.

## Features

- ⚡️ Faster Download Speed
- ⏰ Queues and Schedulers
- 🌐 Browser Extensions
- 💻 Multiplatform (Android / Windows / Linux / Mac)
- 🌙 Multiple Themes (Dark/Light/Black and more) with modern UI
- ❤️ Free and Open Source

Please visit [Project Website](https://abdownloadmanager.com) for more info.

## Installation

### Download and Install the App

<a href="https://abdownloadmanager.com"><img src="https://img.shields.io/badge/Official%20Website-897BFF?logo=abdownloadmanager&logoColor=fff&style=flat-square" alt="Official Website" height="32" /></a>
<a href="https://github.com/petesimon/abdm-linux-arm64"><img src="https://img.shields.io/badge/GitHub%20Releases-2a2f36?logo=github&logoColor=fff&style=flat-square" alt="GitHub Releases" height="32" /></a>

#### Download a tar.gz file for Linux arm64 (aarch64) from the `releases` page

A list of available files on github is in the [releases page HERE](https://github.com/petesimon/abdm-linux-arm64/releases)

After you download a tar.gz file, then extract the contents and navigate into the folder `ABDownloaderManager`. Execute the file `bin/ABDownloaderManager`

#### * DO NOT USE THE SCRIPT FOR arm64 * - Installation script (Linux)

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/amir1376/ab-download-manager/master/scripts/install.sh)
```

> ⚠️ **Warning:** This software is NOT on Google Play or other app stores unless listed here. Any version **claiming to be or related to this project** should be considered SCAM and UNSAFE.

For alternative installation methods, uninstallation instructions, and more details, please refer to the [wiki](https://github.com/amir1376/ab-download-manager/wiki/) page.

### Browser Extensions

You can download the browser extension to integrate the app with your browser.

<p align="left">
<a href="https://addons.mozilla.org/firefox/addon/ab-download-manager/">
    <picture>
        <img alt="Chrome Extension" src="./assets/banners/firefox-extension.png" height="48">
    </picture>
</a>
<a href="https://chromewebstore.google.com/detail/bbobopahenonfdgjgaleledndnnfhooj">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="./assets/banners/chrome-extension_dark.png" height="48">
        <source media="(prefers-color-scheme: light)" srcset="./assets/banners/chrome-extension_light.png" height="48">
        <img alt="Chrome Extension" src="./assets/banners/chrome-extension_light.png" height="48">
    </picture>
</a>
</p>

## Screenshots

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/screenshots/app-home_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="./assets/screenshots/app-home_light.png">
  <img alt="App Home Section" src="./assets/screenshots/app-home_dark.png">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/screenshots/app-download_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="./assets/screenshots/app-download_light.png">
  <img alt="App Download Section" src="./assets/screenshots/app-download_dark.png">
</picture>
</div>

## Project Status & Feedback

Please keep in mind that this project is in the beginning of its journey.
**Lots of features** are on the way!

**But**, in the meantime you may face **Bugs or Problems**. If you do, please report them to me via the [Community chat](#community) or through `GitHub Issues`, and I'll do my best to fix them ASAP.

## Community

You can join our [Telegram Group](https://t.me/abdownloadmanager_discussion) to:

- Report problems
- Suggest features
- Get help with the app

## Repositories And Source Code

There are multiple repositories related to the **AB Download Manager** project:

| Repository                                                                                 | Description                                                                   |
|--------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| [Main Application](https://github.com/petesimon/abdm-linux-arm64) (You are here)           | Contains the  **Application** that runs on your  **device**                   |
| [Browser Integration](https://github.com/amir1376/ab-download-manager-browser-integration) | Contains the **Browser Extension** to be installed on your  **browser**       |
| [Website](https://github.com/amir1376/ab-download-manager-website)                         | Contains the **AB Download Manager** [website](https://abdownloadmanager.com) |

I've spent a lot of time to create this project.

If you like my work, please consider giving it a ⭐ — thanks! ❤️

## Bug Report

If you notice any bugs in the source code, please report them via the [GitHub Issues](https://github.com/amir1376/ab-download-manager/issues) section in the original repository which belongs to @amir1376.

## Build From Source

To compile and test the desktop app on your local machine,
follow these steps:

1. Clone the project.
2. Download and extract the [JBR](https://github.com/JetBrains/JetBrainsRuntime/releases), and make it available by either:
    
    - Adding it to your `PATH`, or
    - Setting the `JAVA_HOME` environment variable to its installation path.
  
3. Navigate to the project directory, open your terminal and execute the following command:

    ```bash
    ./gradlew createReleaseFolderForCi
    ```

4. The output will be available at:

    ```
    <project_dir>/build/ci-release
    ```

> **Note**. This project is compiled and published by GitHub actions [here](./.github/workflows/publish.yml), so if you
> faced any problem you can check that too.

## Translations

If you’d like to help translate AB Download Manager into another language, or improve existing translations, you can do
so on Crowdin. Here’s how:

- Visit the project in [Crowdin](https://crowdin.com/project/ab-download-manager)
- Please DO NOT submit translations via pull requests.
- If you want to add a new language, please see [this](https://github.com/amir1376/ab-download-manager/issues/144).

## Contribution

If you want to contribute to this project, please read [Contributing Guide](CONTRIBUTING.md) first.

## Support the Project

If you'd like to support the project, you can find details on how to donate in the [DONATE.md](DONATE.md) file.
