# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-241-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
╔══════════════════════════════════════╗
║           THREAT OVERVIEW            ║
╠══════════════════════════════════════╣
║ Status: MEDIUM                       ║
║ Active IPs: 241                      ║
║ Total Reports: 546                   ║
║ Unique Sources: 241                  ║
╚══════════════════════════════════════╝
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

      HTTP Service Probing ▏  160 ███████████████████████████████████ ( 29.3%)
     Malicious User Agents ▏  129 ████████████████████████████ ( 23.6%)
   Admin Interface Probing ▏   88 ███████████████████ ( 16.1%)
     CVE-2017-9841 Exploit ▏   41 ████████ (  7.5%)
     Sensitive File Access ▏   30 ██████ (  5.5%)
       CVE Exploit Probing ▏   21 ████ (  3.8%)
        WordPress Scanning ▏   19 ████ (  3.5%)
Non-Static Content Crawler ▏   17 ███ (  3.1%)
  Backdoor Access Attempts ▏   16 ███ (  2.9%)
   ThinkPHP CVE-2018-20062 ▏   14 ███ (  2.6%)
       Jira_Cve 2021 26086 ▏    6 █ (  1.1%)
               Netgear_Rce ▏    4 █ (  0.7%)
            Cve 2022 41082 ▏    1 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

United Kingdom ▏  157 ███████████████████████████████████ ( 31.4%)
 United States ▏  133 █████████████████████████████ ( 26.6%)
       Ireland ▏   76 ████████████████ ( 15.2%)
     Singapore ▏   34 ███████ (  6.8%)
         China ▏   23 █████ (  4.6%)
   Netherlands ▏   20 ████ (  4.0%)
         India ▏   17 ███ (  3.4%)
       Germany ▏   15 ███ (  3.0%)
      Bulgaria ▏   14 ███ (  2.8%)
       Vietnam ▏   11 ██ (  2.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-14 ▏   47 ███████████ (  9.2%)
2025-06-15 ▏   77 ███████████████████ ( 15.1%)
2025-06-16 ▏   64 ████████████████ ( 12.5%)
2025-06-17 ▏   35 ████████ (  6.9%)
2025-06-18 ▏   57 ██████████████ ( 11.2%)
2025-06-19 ▏   90 ██████████████████████ ( 17.6%)
2025-06-20 ▏  140 ███████████████████████████████████ ( 27.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!