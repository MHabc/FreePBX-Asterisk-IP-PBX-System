# 📞 FreePBX Asterisk IP PBX System

## 🎯 Project Objective

The goal of this project is to build an **IP PBX (Private Branch Exchange)** system using the open-source platforms **FreePBX** and **Asterisk**. The system provides the key functions of a modern PBX, including:

- Internal communication (extension-to-extension)  
- Outbound calling  
- Receiving inbound calls from public numbers  
- Interactive Voice Response (IVR) for automated answering  
- Call recording and voicemail  
- Call queues and ring groups (ring all, ring hunt)  
- Blacklist, music on hold, follow-me, and more  

## 🛠️ Tools and Environment

- **FreePBX**: GUI for PBX configuration  
- **Asterisk**: Core call processing engine  
- **Softphones**: Zoiper, 3CX, MicroSIP for testing calls  
- **Virtualization**: VMware for simulating the PBX infrastructure  

## System Architecture

![Asterisk Architecture](https://github.com/MHabc/FreePBX-Asterisk-IP-PBX-System/blob/master/Asterisk-architecture.png)

## Key Features

| Features | Description |
|---------|-------------|
| 📞 Internal Calls | Extension-to-extension communication |
| 📤 Outbound Calls | Calls via number `0951000017` with prefix `9` |
| 📥 Inbound Calls | Calls to company number `0952014317` trigger IVR |
| 🔊 IVR | Callers can press keys to reach specific departments |
| 🏢 Conference | Extension `4174` enables password-protected meetings |
| 📦 Ring Group | Technical dept. (ring hunt) / Sales dept. (ring all) |
| 📬 Voicemail | Stores and plays back messages for the Director |
| 📛 Blacklist | Blocks calls from blacklisted numbers |
| 🎶 Music on Hold | Plays music while the call is on hold |
| 📅 Time Condition | Blocks calls outside business hours |
| 🔁 Follow Me | Forwards calls to multiple devices |

## 📂 Main Configuration Files

- `iax_custom.conf` and `pjsip_custom.conf`: Extension definitions  
- `extensions_custom.conf`: Dialplan for call flow management  
- `queues_custom.conf`: Call queues  
- `blacklist.conf`: Blocked numbers list  
- `voicemail_custom.conf`: Voicemail configuration  
- `musiconhold_custom.conf`: On-hold music setup  

## 📈 Implementation Results

- ✅ Stable operation with all expected features  
- ✅ Clear audio response and user-friendly IVR logic  
- ✅ Successfully tested across multiple softphones  
- ✅ Practical application of VoIP and IP PBX theory  

## 🚀 Future Development

- Enhance SIP security with TLS/SRTP  
- Deploy system on cloud platforms (AWS, Azure)  
- Integrate NLP-based audio processing and chatbot features  
- Develop a web interface for call history and analytics  

## 📚 References

- Course materials – UIT, VNU-HCM  
- [Zoiper Softphone](https://www.zoiper.com)  
- [3CX Softphone](https://www.3cx.com/voip/softphone/)  
- Asterisk & FreePBX official documentation  

---

> Link video demo availale in *Link Demo.txt*

> Detailed report available in *FreePBX_report.pdf*
