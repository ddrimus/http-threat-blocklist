# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-145-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--17-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
╔══════════════════════════════════════╗
║           THREAT OVERVIEW            ║
╠══════════════════════════════════════╣
║ Status: LOW                          ║
║ Active IPs: 145                      ║
║ Total Reports: 259                   ║
║ Unique Sources: 145                  ║
╚══════════════════════════════════════╝
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

      HTTP Service Probing ▏   74 ███████████████████████████████████ ( 28.6%)
     Malicious User Agents ▏   71 █████████████████████████████████ ( 27.4%)
     CVE-2017-9841 Exploit ▏   28 █████████████ ( 10.8%)
       CVE Exploit Probing ▏   17 ████████ (  6.6%)
   Admin Interface Probing ▏   13 ██████ (  5.0%)
   ThinkPHP CVE-2018-20062 ▏   11 █████ (  4.2%)
        WordPress Scanning ▏   11 █████ (  4.2%)
Non-Static Content Crawler ▏   11 █████ (  4.2%)
  Backdoor Access Attempts ▏    9 ████ (  3.5%)
     Sensitive File Access ▏    7 ███ (  2.7%)
               Netgear_Rce ▏    4 █ (  1.5%)
       Jira_Cve 2021 26086 ▏    2 █ (  0.8%)
            Cve 2022 41082 ▏    1 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏   76 ███████████████████████████████████ ( 32.2%)
       Ireland ▏   46 █████████████████████ ( 19.5%)
United Kingdom ▏   28 ████████████ ( 11.9%)
     Singapore ▏   21 █████████ (  8.9%)
         China ▏   14 ██████ (  5.9%)
         India ▏   13 █████ (  5.5%)
      Bulgaria ▏   11 █████ (  4.7%)
       Vietnam ▏    9 ████ (  3.8%)
   Netherlands ▏    9 ████ (  3.8%)
       Germany ▏    9 ████ (  3.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-12 ▏   27 ████████████ ( 10.4%)
2025-06-13 ▏    9 ████ (  3.5%)
2025-06-14 ▏   47 █████████████████████ ( 18.1%)
2025-06-15 ▏   77 ███████████████████████████████████ ( 29.7%)
2025-06-16 ▏   64 █████████████████████████████ ( 24.7%)
2025-06-17 ▏   35 ███████████████ ( 13.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!