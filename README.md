# 🌊 ChakraFlow  

**ChakraFlow** is a cross-platform (Windows & Linux) network control and monitoring app built with **NativePHP**. Inspired by the flow of chakra in *Naruto*, ChakraFlow helps you take control of your internet connections — deciding which apps can release their “chakra” (data) and which ones should be sealed away.  

## ✨ Features  
- 🔒 **App Blocking no Jutsu** – Allow or block apps from accessing the internet.  
- 📶 **Chakra (Data) Flow Control** – Monitor bandwidth usage per app in real time.  
- 📊 **Usage Stats Dashboard** – Visualize how much data is consumed and by which process.  
- 🛡 **Profiles & Seals** – Create profiles for different networks (e.g. Wi-Fi, hotspot, office) and apply automatic blocking rules.  
- ⚡ **Lightweight & Fast** – Minimal system overhead, designed to run silently in the background.  
- 🌍 **Cross-Platform** – Works on **Windows (WFP)** and **Linux (iptables/libpcap)** through a helper service.  

## 🚀 How It Works  
1. The **ChakraFlow UI** (built with NativePHP) is your command center.  
2. A **background helper service** (Rust/Go/C++) interacts with system firewall & network APIs.  
3. Together, they let you visualize, monitor, and control your app’s “chakra flow.”  

## 🎯 Use Cases  
- Save data on metered connections (hotspots, limited plans).  
- Block hidden background processes from phoning home.  
- Improve privacy by controlling which apps can connect.  
- Monitor network usage in real time like a shinobi sensing chakra.  
