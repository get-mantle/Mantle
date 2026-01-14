# Mantle - A layer between you and apps.

<p align="center">
  <b>Mantle - Device & Identity Spoofing [Xposed Module]</b><br>
  A layer between you and apps.
</p>

![Mantle Banner](https://github.com/get-mantle/Mantle/blob/main/Mantle-Banner.png?raw=true)

<p align="center">
  <a href="https://github.com/get-mantle/Mantle/releases">
    <img src="https://img.shields.io/badge/Download-Latest_Release-blue?style=for-the-badge&logo=github" alt="Download">
  </a>
</p>

## ⚠️ ROOT IS REQUIRED

**Mantle** is a powerful Xposed Module designed to maximize your privacy by spoofing or mocking various device identifiers and environment details. It gives you granular control over your digital identity, allowing you to minimize data collection and prevent unwanted device fingerprinting.

### ⚠️ XPOSED FRAMEWORK REQUIRED
If you are unfamiliar with the **Xposed Framework**, this application is likely not for you as it relies on the Xposed bridge to function. Please do not attempt to use it without a working Xposed environment. To learn more about Xposed, please read [here](http://xdaforums.com/xposed/).

### ❗ IMPORTANT
Although Mantle has been rigorously tested on various devices, modifying system parameters always carries inherent risks. **It is strongly recommended to backup your ROM and critical data before using this app.** We are not responsible for any data loss, bootloops, or other issues that may arise.

### 🎭 About "Masking"
This is an Xposed Module designed to **mask** various ID parameters on your phone. "Masking" means that when an application attempts to access these parameters, Mantle intercepts the request and provides the user-defined spoofed value instead of the original one. Your actual system values remain intact and unchanged on the device itself.

---

## 📢 Latest Updates

### Multi-Group App Management
You asked, we listened! You can now add the same app to multiple groups. This feature provides greater flexibility, allowing you to organize your applications across different categories or workflows without restriction.

---

## 🚀 Key Features

### 🛡️ Device Identity Spoofing
Mask your real device identity by mocking critical hardware and system identifiers:
*   **Hardware IDs**: IMEI, IMSI, ICCID, Android ID, Serial Number.
*   **Advertising IDs**: Google Advertising ID (GAID), GSF ID.
*   **Device Models**: Spoof various manufacturers, models, and build properties.

### 🌐 Network & Carrier Spoofing
Simulate different network environments:
*   **Carrier Info**: Custom SIM Operator, Network Operator, Country Codes (MCC/MNC).
*   **Mobile Number**: Mock the reported line number.
*   **WiFi / Bluetooth**: Spoof MAC addresses (BSSID), SSID, and Bluetooth MAC.
*   **Connectivity**: Mask Network Capabilities and Proxy settings.

### 📍 Location & Environment Spoofing
*   **GPS Masking**: Set custom GPS coordinates or randomize location data.
*   **Mock Location Hiding**: Hides the "Mock Location" developer setting from apps.
*   **System Settings**: Match spoofed location with appropriate Locale and Timezone.

### ⚙️ Profile Management
*   **Identities**: Create, save, and switch between multiple device personas.
*   **Groups**: Apply specific profiles to a group of apps simultaneously.
*   **Backup & Restore**: Export and import profiles to share or save configurations.

---

## 💎 Pricing & Plans

<table width="100%">
  <thead>
    <tr>
      <th>Feature</th>
      <th align="center">Starter</th>
      <th align="center">Pro</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>IMEI 1 & IMEI 2</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Hardware Serial</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Bluetooth MAC</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>WiFi MAC & SSID</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Mobile Number</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Advertising ID</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Android ID</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>DRM Media ID</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>SIM Info (Operator, Serial, MCC/MNC)</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Google Services Framework ID (GSF)</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Google Accounts (Gmail)</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Device Spoofing (Model, Manufacturer)</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td><b>GPS with Timezone</b></td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td><b>Proxy with Timezone</b></td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Hide Mock Location</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Profile Creation & Notes</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Group App Management</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Backup/Restore Data</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>One Click Randomize</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
  </tbody>
</table>

---

## 📥 Installation

1.  **Prerequisites**: Rooted Android device with LSPosed (or compatible Xposed framework).
2.  **Install**: Download and install the `Mantle` APK.
3.  **Activate**: Enable the module in your Xposed Manager (LSPosed) and select the apps you want to target (System Framework recommended).
4.  **Reboot**: Restart your device or target apps.

---

## 📜 End User License Agreement (EULA)

By downloading, installing, or using this application ("Mantle"), you agree to the following terms:

### 1. LICENSE
Subject to your compliance with these terms, you are granted a limited, non-exclusive, non-transferable license to use the Application on devices owned or controlled by you.

### 2. NO WARRANTY
THE APPLICATION IS PROVIDED "AS IS" AND "AS AVAILABLE", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE APPLICATION OR THE USE OR OTHER DEALINGS IN THE APPLICATION.

### 3. USER RESPONSIBILITY
You acknowledge that this tool is intended for privacy protection, testing, and research purposes only. You agree not to use this Application for any illegal or unauthorized purpose. You are solely responsible for your conduct and any data, text, information, usernames, graphics, photos, profiles, audio and video clips, links, and other content that you submit, post, and display using the Application.

### 4. TERMINATION
We may terminate or suspend your access to the Application immediately, without prior notice or liability, for any reason whatsoever, including without limitation if you breach these terms.

---

## 🙌 Credits & Acknowledgements

A huge thanks to the community and developers who make tools like this possible:
*   **LSPosed Community**: For the incredible Xposed framework.
*   **@VD171**: For the **VDInfo** app, which is invaluable for verifying spoofed values.
*   **@AndroidX**: For the GPS Setter logic.

## ⚠️ Disclaimer & Usage
**Note**: Do not use this app for any illegal purposes or to cheat in any games or applications. This module is intended solely for enhancing your personal privacy.

## 💸 Donations
Discussions regarding donation packages or payments are not permitted in this thread. If you have questions about this, please contact us directly via email.

## 🤝 Support

For support and feedback:
*   **Website**: [https://getmantle.in/](https://getmantle.in/)
*   **Telegram**: [https://t.me/getmantle](https://t.me/getmantle)
*   **Feature Request & Feedback**: [Submit here](https://forms.gle/FP8M7c3rQMDHSztU9)

