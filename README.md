Here's a neatly formatted version for your GitHub README:

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
- [All Downloads](#)
- [ESign Sources](#source)
  
---

