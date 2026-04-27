# TracePro iOS Deployment Guide

## 1. Prepare your GitHub Repository
1. Create a **new** GitHub repository.
2. **Unzip** the project on your computer.
3. Upload all files **EXCEPT** the `node_modules` folder.
   - If you have many files, use the [GitHub Desktop](https://desktop.github.com/) app to upload them.

## 2. Generate the IPA
1. Once your code is on GitHub, click the **Actions** tab.
2. Click **"Build iOS IPA"** on the left.
3. Click **"Run workflow"** -> **"Run workflow"**.
4. Wait about 3-5 minutes. When it finishes, scroll to the bottom of the page.
5. Download the **TracePro-iOS-IPA** artifact. Unzip it on your PC to find `TracePro.ipa`.

## 3. Sideload onto iPhone from Windows
Since you are on Windows, you will need a tool to install the IPA onto your iPhone:
- **AltStore (Highly Recommended):** [altstore.io](https://altstore.io/)
- **Sideloadly:** [sideloadly.io](https://sideloadly.io/)

**Steps:**
1. Install AltStore on your Windows PC.
2. Connect your iPhone via USB.
3. Use AltStore to "Install IPA..." and select the `TracePro.ipa` file.
4. You will need to sign in with your Apple ID (this "self-signs" the app so it runs on your phone).
