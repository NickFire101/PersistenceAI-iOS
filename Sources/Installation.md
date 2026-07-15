# Installation

Welcome to **PersistenceAI**! This guide explains how to download, build, and run PersistenceAI on **iPhone**, **iPad**, and **macOS**.

---

# Table of Contents

* [Requirements](#requirements)
* [Download the Project](#download-the-project)
* [Clone the Repository](#clone-the-repository)
* [Open the Project](#open-the-project)
* [Resolve Dependencies](#resolve-dependencies)
* [Build the Project](#build-the-project)
* [Run the Application](#run-the-application)
* [Permissions](#permissions)
* [Updating PersistenceAI](#updating-persistenceai)
* [Troubleshooting](#troubleshooting)
* [Supported Platforms](#supported-platforms)

---

# Requirements

Before building PersistenceAI, ensure your development environment meets the following requirements.

| Requirement      | Version                  |
| ---------------- | ------------------------ |
| macOS            | Latest Supported Version |
| Xcode            | Latest Version           |
| Swift            | 5.9 or later             |
| Git *(Optional)* | Latest Version           |

---

# Download the Project

If you don't have Git installed, you can download the repository directly from GitHub.

1. Open the **PersistenceAI** GitHub repository.
2. Click the **Code** button.
3. Select **Download ZIP**.
4. Wait for the download to complete.
5. Extract the ZIP archive.
6. Open the extracted folder.
7. Double-click **PersistenceAI.xcodeproj** to open the project in Xcode.

Downloading the ZIP archive is the easiest way to get started.

---

# Clone the Repository

If you have Git installed, clone the repository.

```bash
git clone https://github.com/NickFire101/PersistenceAI-iOS.git
```

Move into the project folder.

```bash
cd PersistenceAI-iOS
```

---

# Open the Project

Open the project using Xcode.

```bash
open PersistenceAI.xcodeproj
```

Or simply double-click **PersistenceAI.xcodeproj** in Finder.

---

# Resolve Dependencies

PersistenceAI uses **Swift Package Manager** through the Xcode project.

When the project is opened, Xcode automatically downloads and resolves the required dependencies.

If necessary:

1. Open Xcode.
2. Select **File → Packages → Resolve Package Versions**.
3. Wait until all packages have finished downloading.

---

# Build the Project

Choose one of the following destinations:

* 📱 iPhone
* 📱 iPad
* 💻 macOS

Build the project by selecting:

**Product → Build**

or press:

```text
⌘ + B
```

---

# Run the Application

Launch PersistenceAI by selecting:

**Product → Run**

or press:

```text
⌘ + R
```

The application will build and launch on your selected simulator or physical device.

---

# Permissions

PersistenceAI may request the following permission when required.

| Permission       | Purpose                  |
| ---------------- | ------------------------ |
| 📷 Photo Library | Select and attach images |

Only permissions required by the application are requested.

---

# Updating PersistenceAI

If you cloned the repository using Git, update to the latest version with:

```bash
git pull origin main
```

After updating:

1. Open the project.
2. Allow Xcode to resolve packages if prompted.
3. Build and run the application again.

---

# Troubleshooting

## Dependencies won't download

Try the following:

* Close Xcode.
* Reopen the project.
* Select **File → Packages → Resolve Package Versions**.
* Check your internet connection.

---

## Build Failed

Possible solutions:

* Clean the build folder (**Shift + ⌘ + K**)
* Restart Xcode
* Ensure you are using the latest Xcode release
* Confirm all dependencies have been resolved

---

## Application won't launch

Verify that:

* A supported simulator or device is selected.
* The project builds successfully.
* Dependencies have finished downloading.

---

# Supported Platforms

| Platform      | Supported |
| ------------- | --------- |
| 📱 iPhone     | ✅         |
| 📱 iPad       | ✅         |
| 💻 macOS      | ✅         |
| ⌚ Apple Watch | ❌         |
| 📺 Apple TV   | ❌         |

---

# Next Steps

Congratulations! 🎉

PersistenceAI is now ready to use.

You can now:

* 💬 Start AI conversations
* ⚙️ Configure AI settings
* 🖼️ Attach images
* 💾 Import and export conversations
* ✨ Experience the native Glass UI
* 🚀 Explore the project and contribute

Enjoy using **PersistenceAI**!
