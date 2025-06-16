# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-88-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--15-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
╔══════════════════════════════════════╗
║           THREAT OVERVIEW            ║
╠══════════════════════════════════════╣
║ Status: LOW                          ║
║ Active IPs: 88                       ║
║ Total Reports: 159                   ║
║ Unique Sources: 88                   ║
╚══════════════════════════════════════╝
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

      HTTP Service Probing ▏   44 ███████████████████████████████████ ( 27.7%)
     Malicious User Agents ▏   41 ████████████████████████████████ ( 25.8%)
     CVE-2017-9841 Exploit ▏   17 █████████████ ( 10.7%)
       CVE Exploit Probing ▏   11 ████████ (  6.9%)
   ThinkPHP CVE-2018-20062 ▏   10 ███████ (  6.3%)
Non-Static Content Crawler ▏    7 █████ (  4.4%)
        WordPress Scanning ▏    6 ████ (  3.8%)
  Backdoor Access Attempts ▏    6 ████ (  3.8%)
   Admin Interface Probing ▏    6 ████ (  3.8%)
     Sensitive File Access ▏    5 ███ (  3.1%)
               Netgear_Rce ▏    3 ██ (  1.9%)
       Jira_Cve 2021 26086 ▏    2 █ (  1.3%)
            Cve 2022 41082 ▏    1 █ (  0.6%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏   43 ███████████████████████████████████ ( 29.9%)
       Ireland ▏   24 ███████████████████ ( 16.7%)
United Kingdom ▏   19 ███████████████ ( 13.2%)
     Singapore ▏   13 ██████████ (  9.0%)
         India ▏   12 █████████ (  8.3%)
         China ▏    9 ███████ (  6.2%)
       Vietnam ▏    7 █████ (  4.9%)
   Netherlands ▏    6 ████ (  4.2%)
       Germany ▏    6 ████ (  4.2%)
      Bulgaria ▏    5 ████ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-12 ▏   27 ████████████ ( 17.0%)
2025-06-13 ▏    9 ████ (  5.7%)
2025-06-14 ▏   47 █████████████████████ ( 29.6%)
2025-06-15 ▏   76 ███████████████████████████████████ ( 47.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!