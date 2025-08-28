# CDM-Decryptor-And-Widevine-Keys-Dump-With-Chrome-Extension
XtreamMasters CDM is a Google Chrome extension designed to help developers and researchers automatically extract MPD manifests and decryption keys, as well as to enhance the security of stream algorithms
This tool is built to streamline the process of accessing and analyzing DRM content for educational and research purposes.

## ✨ Key Features

| | |
| :--- | :--- |
| **🤖 Automated Extraction** | Effortlessly captures MPD manifests and decryption keys the moment you play a DRM-protected stream. No manual steps required. |
| **⏰ Intelligent Scheduling** | Configure the tool to fetch data at precise intervals—hourly, daily, or custom cron schedules—ensuring you always have the latest manifests. |
| **⚡ Zero Manual Effort** | Eliminates the tedious and error-prone process of manual extraction from browser dev tools, saving you significant time and hassle. |
| **🔌 Seamless Integration** | Works silently in the background. Just browse as usual; the extension handles everything automatically without interrupting your workflow. |
| **🎯 Reliable & Accurate** | Engineered for high fidelity, providing dependable extraction of critical streaming data for your projects. |


## ⚙️ Installation

Follow these steps to install the extension in developer mode:

### Step 1: Obtain the Extension
- **Download** the `xtreammasers-cdm_ext.zip` file from the releases.
- **Extract** the ZIP file to a folder of your choice (e.g., `xtreammasters-cdm`).

### Step 2: Load into Chrome
1.  Open Chrome and go to `chrome://extensions`.
2.  **Enable** **Developer Mode** using the toggle in the top-right corner.
3.  Click the **Load unpacked** button.
4.  **Select the folder** you created in Step 1 (the one containing the extension files).

### Step 3: Pin the Extension
- Click the **Extensions puzzle piece (🧩)** icon in the toolbar.
- Find **XtreamMasters CDM** in the list and click the **Pin (📌)** icon next to it.

**You're all set! The extension is now active and will automatically capture data from DRM streams.**



## 🎯 How to Use

Using the extension is a completely hands-off process:

1.  **Navigate** to a website that hosts DRM-protected streams (e.g., Your Development Website, etc.).
2.  **Play** any video stream as you normally would.
3.  **Let it Work:** The extension automatically works in the background. You will see a notification badge on the icon (e.g., `✓` or `Keys: X`) confirming successful capture.
4.  **View Data:** Click the pinned extension icon in your toolbar to view a popup of all captured MPD URLs and decryption keys.

> **Tip:** The data is captured in real-time. For scheduled fetching, ensure the tab with the video stream is active and playing.

=====================================================

## ⚠️ Developer-Focused Disclaimer & Security Notice

**Intended Purpose:**  
This extension is designed exclusively for **security research, penetration testing, and educational purposes**. It serves as a vital tool for:
- Security professionals and developers to audit their own streaming platforms
- Understanding potential vulnerabilities in content protection implementation
- Testing the robustness of DRM and encryption implementations
- Developing better security measures against unauthorized data extraction

**Legal & Ethical Use:**  
- This tool must only be used on platforms and content where you have explicit authorization to conduct security testing
- Unauthorized use on third-party services may violate Terms of Service and applicable laws
- The developers assume no liability for misuse of this tool or any security breaches resulting from its capabilities

**For Streaming Platform Developers:**  
If you're concerned about your platform's vulnerability to such extraction methods, we recommend:
- Implementing additional obfuscation layers for key exchange
- Regularly conducting security audits of your streaming infrastructure
- Monitoring for unusual patterns in manifest requests
- Utilizing certified DRM implementation best practices

**Use of this tool for accessing protected content without authorization is strictly prohibited. By using this extension, you acknowledge that you understand these terms and accept full responsibility for its application.**
