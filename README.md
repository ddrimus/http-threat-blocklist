# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-51-blue)](.)
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
║ Active IPs: 51                       ║
║ Total Reports: 83                    ║
║ Unique Sources: 51                   ║
╚══════════════════════════════════════╝
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

     Malicious User Agents ▏   24 ███████████████████████████████████ ( 28.9%)
      HTTP Service Probing ▏   23 █████████████████████████████████ ( 27.7%)
     CVE-2017-9841 Exploit ▏    8 ███████████ (  9.6%)
       CVE Exploit Probing ▏    6 ████████ (  7.2%)
   ThinkPHP CVE-2018-20062 ▏    4 █████ (  4.8%)
     Sensitive File Access ▏    4 █████ (  4.8%)
        WordPress Scanning ▏    3 ████ (  3.6%)
Non-Static Content Crawler ▏    3 ████ (  3.6%)
  Backdoor Access Attempts ▏    3 ████ (  3.6%)
       Jira_Cve 2021 26086 ▏    2 ██ (  2.4%)
   Admin Interface Probing ▏    2 ██ (  2.4%)
               Netgear_Rce ▏    1 █ (  1.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏   23 ███████████████████████████████████ ( 28.7%)
       Ireland ▏   14 █████████████████████ ( 17.5%)
     Singapore ▏    9 █████████████ ( 11.2%)
United Kingdom ▏    9 █████████████ ( 11.2%)
         China ▏    6 █████████ (  7.5%)
         India ▏    5 ███████ (  6.2%)
      Bulgaria ▏    5 ███████ (  6.2%)
       Vietnam ▏    4 ██████ (  5.0%)
       Germany ▏    3 ████ (  3.8%)
   Netherlands ▏    2 ███ (  2.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-12 ▏   27 ████████████████████ ( 32.5%)
2025-06-13 ▏    9 ██████ ( 10.8%)
2025-06-14 ▏   47 ███████████████████████████████████ ( 56.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!