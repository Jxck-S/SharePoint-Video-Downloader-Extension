# SharePoint Video Downloader Extension

This Chrome extension helps you extract and generate an `ffmpeg` command to download videos embedded in **SharePoint** pages.

Rather than downloading the video directly, the extension provides a ready-to-use `ffmpeg` command that you can run in your terminal to save the video.

![Extension Preview](https://github.com/Jxck-S/SharePoint-Video-Downloader-Extension/blob/main/preview.png?raw=true)

---

## 🛠 Features

- Detects embedded video sources on SharePoint
- Automatically generates a valid `ffmpeg` command
- Copies the command to your clipboard for easy use

---

## 🚀 Installation

This extension is not in the Chrome Web Store and must be loaded manually:

### 1. Download the Extension

- Clone this repository or [download it as a ZIP](https://github.com/MexxDirkx/SharePoint-Video-Downloader-Extension/archive/refs/heads/main.zip)
- Extract the contents to a folder on your computer

### 2. Load the Unpacked Extension in Chrome

1. Open Chrome and navigate to `chrome://extensions`
2. Enable **Developer mode** in the top-right corner
3. Click **Load unpacked**
4. Select the folder where you extracted the extension

---

## 🧪 How to Use

1. Go to a SharePoint or Microsoft Stream (Classic) video page
2. Click the extenstion icon in the extenstions bar, there will be a button to detect the video, and generate the command, you can then copy it. 
3. Paste the generated `ffmpeg` command into your terminal or command prompt to download the video



## 📦 How to Install FFmpeg

You’ll need FFmpeg installed to run the command generated by this extension.

### Option 1: Official FFmpeg Download

- Download precompiled binaries from:  
  🔗 https://www.ffmpeg.org/download.html

### Option 2: Install via Package Managers

Install via Chocolatey (Windows only)

If you use Windows and have [Chocolatey](https://chocolatey.org/) installed, you can quickly install FFmpeg:

```powershell
choco install ffmpeg

```


### 🐧 Linux

#### Ubuntu / Debian (APT)

```
sudo apt update
sudo apt install ffmpeg
```

#### CentOS / RHEL (YUM or DNF)

CentOS 7:

```
sudo yum install epel-release
sudo yum install ffmpeg ffmpeg-devel
```

CentOS 8+ / RHEL / Fedora:

```
sudo dnf install ffmpeg ffmpeg-devel
```
