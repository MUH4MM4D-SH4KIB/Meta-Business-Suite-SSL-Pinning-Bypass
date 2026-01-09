# 🔐 SSL Pinning Bypass Meta Business Suite

Meta Business Suite SSL Pinning Bypass and intercept Meta Business Suite Traffic.



---

## 🎥 Demo Video

https://github.com/user-attachments/assets/238f2b6c-39d1-4fbc-bf43-6ee0190a7990

---

## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**
---
## Meta Business Suite App Version 
- **534.0.0.54.109**
---

## 📱 Mobile Device Requirements
- Android device (**Rooted** or **Non-Rooted**)
- One of the following traffic interception tools:
  - [Proxypin](https://proxypin.com)
  - [Reqable](https://reqable.com)

---

## 💻 Emulator Setup
- Windows PC with:
  - **Reqable**, **Burp Suite**, or **Mitmproxy** installed
  - **Nox** or **LDPlayer** Android emulator
  - **Root access** enabled in the emulator

---

## 🚀 Bypass Procedure

1. Replace patched `libstartup.so with /data/data/com.facebook.pages.app/lib-compressed/libstartup.so`
2. Replace the patched library file:
   ```bash
   adb push D:\patched\libstartup.so /data/data/com.facebook.pages.app/lib-compressed/libstartup.so

3. Use Proxypin / Reqable / Burp Suite / Mitmproxy for capturing traffics.

## For latest patched libstartup.so contract with me.
<a href="https://t.me/MUH4MM4DSH4KIB" target="_blank">
  <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
</a>
