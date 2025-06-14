# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-27-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
╔══════════════════════════════════════╗
║           THREAT OVERVIEW            ║
╠══════════════════════════════════════╣
║ Status: LOW                          ║
║ Active IPs: 27                       ║
║ Total Reports: 37                    ║
║ Unique Sources: 27                   ║
╚══════════════════════════════════════╝
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

     Malicious User Agents ▏   12 ███████████████████████████████████ ( 32.4%)
      HTTP Service Probing ▏   10 █████████████████████████████ ( 27.0%)
     Sensitive File Access ▏    3 ████████ (  8.1%)
       CVE Exploit Probing ▏    3 ████████ (  8.1%)
     CVE-2017-9841 Exploit ▏    3 ████████ (  8.1%)
   ThinkPHP CVE-2018-20062 ▏    1 ██ (  2.7%)
               Netgear_Rce ▏    1 ██ (  2.7%)
        WordPress Scanning ▏    1 ██ (  2.7%)
Non-Static Content Crawler ▏    1 ██ (  2.7%)
  Backdoor Access Attempts ▏    1 ██ (  2.7%)
   Admin Interface Probing ▏    1 ██ (  2.7%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏   12 ███████████████████████████████████ ( 32.4%)
     Singapore ▏    5 ██████████████ ( 13.5%)
       Ireland ▏    5 ██████████████ ( 13.5%)
United Kingdom ▏    5 ██████████████ ( 13.5%)
         India ▏    3 ████████ (  8.1%)
       Vietnam ▏    2 █████ (  5.4%)
       Germany ▏    2 █████ (  5.4%)
            KH ▏    1 ██ (  2.7%)
         Japan ▏    1 ██ (  2.7%)
     Australia ▏    1 ██ (  2.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-12 ▏   27 ███████████████████████████████████ ( 73.0%)
2025-06-13 ▏    9 ███████████ ( 24.3%)
2025-06-14 ▏    1 █ (  2.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!