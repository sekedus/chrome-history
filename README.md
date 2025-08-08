# chrome-history

List of all stable Chrome Portable versions for <ins>**Windows**</ins>.

Check the [releases file](https://github.com/sekedus/chrome-history/tree/main/data) for the download link.

---

<table>
  <tr>
    <td>Stable</td>
    <td><a href="./data/releases.json"><img alt="GitHub file size in bytes" src="https://img.shields.io/github/size/sekedus/chrome-history/data%2Freleases.json"></a></td>
  </tr>
  <tr>
    <td>Dev/Beta</td>
    <td><a href="./data/releases-pre.json"><img alt="GitHub file size in bytes" src="https://img.shields.io/github/size/sekedus/chrome-history/data%2Freleases-pre.json"></a></td>
  </tr>
</table>

---
ㅤ
<details>
  <summary><strong>📑 Table of Contents (click to expand)</strong></summary>

<br/>

- [How to Install Google Chrome Portable Offline](#how-to-install-google-chrome-portable-offline)
  - [Prerequisites](#prerequisites)
  - [Step-by-Step Instructions](#step-by-step-instructions)
    - [1. Download the Online Installer](#1-download-the-online-installer)
    - [2. Extract the Installer Config File](#2-extract-the-installer-config-file)
    - [3. Find the Direct Download URL](#3-find-the-direct-download-url)
    - [4. Download the Actual App File](#4-download-the-actual-app-file)
    - [5. Run the Installer Offline](#5-run-the-installer-offline)
- [Source](#source)
- [Disclaimer](#disclaimer)

</details>

ㅤ
## How to Install Google Chrome Portable Offline

If you're unable to install Google Chrome Portable using the online installer due to internet issues or system restrictions, you can **manually download the necessary files** and install it **offline** using the steps below.

### Prerequisites

* [7-Zip](https://www.7-zip.org/) or another archive tool
* The `.paf.exe` online installer
* A web browser to manually download files

ㅤ
### Step-by-Step Instructions

#### 1. Download the Online Installer

Download the PortableApps `.paf.exe` **online** installer from [PortableApps (SourceForge) page](https://sourceforge.net/projects/portableapps/files/Google%20Chrome%20Portable/).

For example: `GoogleChromePortable_3.0.195.27_online.paf.exe`

#### 2. Extract the Installer Config File

* Open the `.paf.exe` file using **7-Zip**
* Navigate to: `App\AppInfo\`
* Extract the file called `installer.ini`

#### 3. Find the Direct Download URL

* Open `installer.ini` with a text editor
* Look for the line:

  ```
  DownloadURL=https://...
  ```
* This is the **direct download link** for the actual application content

#### 4. Download the Actual App File

* Use your browser to download the file from the `DownloadURL`
* Save it in the **same folder** as the `.paf.exe` installer

#### 5. Run the Installer Offline

* Now run the `.paf.exe` installer
* It will detect the file you downloaded and **use it directly** without needing to connect to the internet

ㅤ
> [!CAUTION]  
> Repackaging or redistributing Chrome binaries is not permitted under the [Google Terms of Service](https://policies.google.com/terms#toc-software).  
>  
> This guide uses the official PortableApps installer to download Chrome directly from Google and does not involve modifying or distributing Chrome itself.


ㅤ
## Source

- [PortableApps - 70938](https://portableapps.com/node/70938)
- [PortableApps (SourceForge)](https://sourceforge.net/projects/portableapps/files/Google%20Chrome%20Portable/)
- [Google Chrome Portable x86](https://portableapps.com/apps/internet/google_chrome_portable)
- [Google Chrome Portable x64](https://portableapps.com/apps/internet/google-chrome-portable-64)

ㅤ
## Disclaimer

This project and its contents are not affiliated with, funded, authorized, endorsed by, or in any way associated with Google LLC, PortableApps.com, or any of their respective affiliates.

Any trademark, service mark, trade name, or other intellectual property rights used in this project are the property of their respective owners.
