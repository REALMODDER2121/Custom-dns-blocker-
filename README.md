# Custom-dns-blocker-
Custom dns for ps 4 homebrew 

# 🌐 Custom DNS Server for PS4 / PS5

A high-performance custom DNS server configuration designed to optimize connection stability, block unwanted telemetry/updates, and provide seamless access to homebrew exploit hosts (e.g., PS4 HEN/PPPwn).

## 🚀 Features
* **Ad-Blocking:** Automatically blocks malicious domains and tracking scripts.
* **Update Blocker:** Prevents automatic console system updates (ideal for jailbroken PS4).
* **High Speed:** Optimized routing for lower latency and faster response times.
* **Exploit Ready:** Built-in redirection for popular PS4 exploit hosting services.

---

## 🛠️ How to Use on PlayStation 4

Follow these simple steps to configure this custom DNS on your PS4 console:

1. Turn on your PS4 and go to **Settings** > **Network**.
2. Select **Set Up Internet Connection**.
3. Choose either **Use Wi-Fi** or **Use LAN Cable** depending on your setup.
4. Select **Custom** (DO NOT select *Easy*).
5. For IP Address Settings, choose **Automatic**.
6. For DHCP Host Name, choose **Do Not Specify**.
7. For **DNS Settings**, select **Manual**.
8. Enter the custom DNS server addresses:
   * **Primary DNS:** `45.90.28.241` 
   * **Secondary DNS:** `45.90.30.241` 
9. For MTU Settings, choose **Automatic**.
10. For Proxy Server, choose **Do Not Specify**.
11. Test your internet connection to ensure everything is configured correctly.

---

## 💻 Configuration & Setup (For Advanced Users)

If you are hosting this DNS server yourself using **dnsmasq** or **Bind9**, here is the recommended configuration outline:

### Example `dnsmasq.conf` snippets:
```text
# Block Sony Update Servers
address=/manuals.playstation.net/127.0.0.1
address=/update.playstation.net/127.0.0.1

# Redirect to Host Exploit
address=/karo218.ir/YOUR_LOCAL_HOST_IP
```

---

## 📥 Downloads & Resources

Klik tautan di bawah ini untuk mengunduh file konfigurasi mentah atau alat bantu setup:

* 📄 **DNS Config Files (.conf / .txt):** [Download DNS Config](https://sites.google.com/view/custom-dns-event/halaman-muka) *(Ganti dengan link file aslimu)*
* 🛠️ **DNS Benchmarking Tool:** [Download Namebench Tool](https://google.com)
(optional)
---

## 🤝 Contributors
* **REALMODDER2121** - Lead Developer
* **daffasnap845** - Contributor

---

## ⚠️ Disclaimer
This custom DNS is provided as-is. Use it at your own discretion. The developer is not responsible for any network instability or data misconfiguration on your devices.

