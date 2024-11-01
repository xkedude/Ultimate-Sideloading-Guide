
---

# 📲 Ultimate Guide to Sideloading on Apple Devices

Welcome to the ultimate guide on sideloading apps on Apple devices without a PC or app limits! This method provides a reliable sideloading experience with built-in privacy features and robust revocation prevention. 

After experimenting with various DNS services and tools like ESign, I decided to create a safer, more reliable setup by reverse-engineering existing methods and blocking analytics with custom DNS configurations.

---

### 🚀 Advantages of This Method:
- **Free!**
- **No PC Required!**
- **No App Limits!**
- **On-Device Signing**
- **Privacy-Conscious** 
- **Easy to Setup!**
- **Compatible with Scarlet, Feather, and More!**
- **10-Minute Setup!**
- **Working CHATGPT!**

This DNS solution is compatible with enterprise signing apps like Scarlet, Feather, and others. If you have any issues, ideas, or requests, please [open an issue](#) here on GitHub.

---

### 🌐 Compatibility
- **Supported iOS/iPadOS Versions**: All latest versions; recommended to use release versions over beta.
- **Limitations**: May not support versions below iOS 12 or iPadOS 13.

---

## 📖 Setup Guide

### Part [1/5]: Creating Your DNS
1. **Create an Account** on [NextDNS](https://nextdns.io).
2. **Denylist Domains**: Add the following:
    - `vpp.itunes.apple.com`
    - `appattest.apple.com`
    - `certs.apple.com`
    - `crl.apple.com`
    - `valid.apple.com`
    - `ocsp2.apple.com`
    - `ocsp.apple.com`
3. **Allowlist Domains**: Add the following:
    - `app.localhost.direct`
    - `register.appattest.apple.com`
4. **Privacy Settings**: In the Privacy tab, disable the “NextDNS Ads and Trackers” option.
5. **Proceed to Part 2** for DNS installation.

---

### Part [2/5]: Installing the DNS
1. Go to **Setup** and click **apple.nextdns.io** to open the NextDNS Profile page.
2. Select your profile and enable the **Trust NextDNS Root CA** and **Bootstrap IPs**.
3. **Download** the profile.
4. In **Settings > General > VPN & Device Management**, install the profile.
5. Go to **General > About > Certificate Trust Settings** and enable **Full Trust for NextDNS Root Certificate**.
6. Continue to Part 3 if you wish to install ESign.

---

### Part [3/5]: Installing ESign
1. Download **ESign** from the link provided in Downloads.
2. Go to **Settings > General > VPN & Device Management** and **Trust** the app.
3. Open ESign and complete initial setup.
4. Move on to Part 4 for advanced ESign configuration.

---

### Part [4/5]: Setting up ESign
1. In ESign, get your **Device UDID** and install the **Query Device UDID** profile.
2. Download and extract the **ESign Certificates**.
3. Import the relevant certificate in **ESign Settings > Import Resources**.
4. Add App Sources and proceed to the next part.

---

### Part [5/5]: Using ESign
1. Download or import **.ipa files** via **AppStore** or **Import Resource** in ESign.
2. Follow **signature** steps to sign apps with the imported certificate.
3. Once signed, go to **Settings > General > VPN & Device Management** and trust the installed app.

---

## 🔒 Post Install Notes
- **Do not disable the DNS**.
- Avoid installing multiple apps at once.
- **Do not use Safari extensions**.
- Switch DNS in **Airplane Mode** if necessary.
- Do not use **Cowabunga Lite** or **Nugget** unless following additional instructions (guides coming soon).

---

## 🔧 Troubleshooting

### Common Errors
- **Unable to Install?**: Ensure DNS settings are correct and follow troubleshooting guides.
- **Revoked Certificate?**: Follow the steps to reset your device or remove revoke triggers.

---

## 💡 FAQ

- **Q: Will a VPN bypass the DNS?**
  - A: It might, but DNS settings should prevent it. Use caution with VPNs.

- **Q: Can I use AltStore or Sideloadly with this guide?**
  - A: Yes, as they use developer signing, not enterprise signing.

---

## 🔗 Downloads & Resources
- [ESign Sources]source[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]
  
---

