# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-208-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--19-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
╔══════════════════════════════════════╗
║           THREAT OVERVIEW            ║
╠══════════════════════════════════════╣
║ Status: LOW                          ║
║ Active IPs: 208                      ║
║ Total Reports: 401                   ║
║ Unique Sources: 208                  ║
╚══════════════════════════════════════╝
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

      HTTP Service Probing ▏  128 ███████████████████████████████████ ( 31.9%)
     Malicious User Agents ▏  105 ████████████████████████████ ( 26.2%)
     CVE-2017-9841 Exploit ▏   33 █████████ (  8.2%)
   Admin Interface Probing ▏   29 ███████ (  7.2%)
     Sensitive File Access ▏   24 ██████ (  6.0%)
       CVE Exploit Probing ▏   18 ████ (  4.5%)
        WordPress Scanning ▏   14 ███ (  3.5%)
Non-Static Content Crawler ▏   14 ███ (  3.5%)
   ThinkPHP CVE-2018-20062 ▏   13 ███ (  3.2%)
  Backdoor Access Attempts ▏   12 ███ (  3.0%)
       Jira_Cve 2021 26086 ▏    6 █ (  1.5%)
               Netgear_Rce ▏    4 █ (  1.0%)
            Cve 2022 41082 ▏    1 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  112 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏   74 ███████████████████████ ( 20.4%)
       Ireland ▏   61 ███████████████████ ( 16.8%)
     Singapore ▏   30 █████████ (  8.3%)
   Netherlands ▏   18 █████ (  5.0%)
         China ▏   17 █████ (  4.7%)
         India ▏   16 █████ (  4.4%)
       Germany ▏   13 ████ (  3.6%)
       Vietnam ▏   11 ███ (  3.0%)
      Bulgaria ▏   11 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-13 ▏    9 ███ (  2.4%)
2025-06-14 ▏   47 ███████████████████ ( 12.6%)
2025-06-15 ▏   77 ███████████████████████████████ ( 20.6%)
2025-06-16 ▏   64 ██████████████████████████ ( 17.1%)
2025-06-17 ▏   35 ██████████████ (  9.4%)
2025-06-18 ▏   57 ███████████████████████ ( 15.2%)
2025-06-19 ▏   85 ███████████████████████████████████ ( 22.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!