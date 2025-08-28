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
- **Download** the latest [`xtreammasers-cdm_ext.zip`](https://cdm.xtream-masters.com/user.php#download) file from the releases section.
- **Extract** the ZIP file to a dedicated folder on your computer (e.g., `xtreammasters-cdm`).

### Step 2: Load into Chrome
1.  Open Chrome and navigate to `chrome://extensions`.
2.  **Enable** **Developer Mode** using the toggle in the top-right corner.
3.  Click the **Load unpacked** button that appears.
4.  **Select the folder** containing the extracted extension files.

<div align="center">
  <img src="https://github.com/user-attachments/assets/2e667631-da0e-48f7-adbe-579db85587b9" alt="Chrome Extensions page with Developer Mode enabled" width="600" />
  <br />
  <em>Enable Developer Mode and click "Load unpacked"</em>
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/17c6f2b5-5ec1-48f2-ba33-b1ac364c5216" alt="File browser selecting the extension folder" width="600" />
  <br />
  <em>Select the folder where you extracted the extension files</em>
</div>

### Step 3: Pin the Extension
- Click the **Extensions puzzle piece (🧩)** icon in Chrome's toolbar.
- Locate **XtreamMasters CDM** in the dropdown list.
- Click the **Pin (📌)** icon to keep it easily accessible.

<div align="center">
  <img src="https://github.com/user-attachments/assets/85309531-d3d6-4b23-8c89-16f08ea73415" alt="Extensions dropdown menu showing the pin option" width="600" />
  <br />
  <em>Pin the extension for quick access from your toolbar</em>
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/c61ba350-7231-43b2-bb27-738b5bea88c1" alt="Extension successfully installed and pinned in toolbar" width="600" />
  <br />
  <em>Extension successfully installed and active</em>
</div>

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
