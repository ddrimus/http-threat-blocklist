# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-127-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
╔══════════════════════════════════════╗
║           THREAT OVERVIEW            ║
╠══════════════════════════════════════╣
║ Status: LOW                          ║
║ Active IPs: 127                      ║
║ Total Reports: 224                   ║
║ Unique Sources: 127                  ║
╚══════════════════════════════════════╝
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

      HTTP Service Probing ▏   62 ███████████████████████████████████ ( 27.7%)
     Malicious User Agents ▏   62 ███████████████████████████████████ ( 27.7%)
     CVE-2017-9841 Exploit ▏   23 ████████████ ( 10.3%)
       CVE Exploit Probing ▏   15 ████████ (  6.7%)
   Admin Interface Probing ▏   11 ██████ (  4.9%)
   ThinkPHP CVE-2018-20062 ▏   10 █████ (  4.5%)
        WordPress Scanning ▏   10 █████ (  4.5%)
Non-Static Content Crawler ▏   10 █████ (  4.5%)
  Backdoor Access Attempts ▏    8 ████ (  3.6%)
     Sensitive File Access ▏    7 ███ (  3.1%)
               Netgear_Rce ▏    3 █ (  1.3%)
       Jira_Cve 2021 26086 ▏    2 █ (  0.9%)
            Cve 2022 41082 ▏    1 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏   66 ███████████████████████████████████ ( 32.2%)
       Ireland ▏   39 ████████████████████ ( 19.0%)
United Kingdom ▏   24 ████████████ ( 11.7%)
     Singapore ▏   18 █████████ (  8.8%)
         India ▏   13 ██████ (  6.3%)
      Bulgaria ▏   11 █████ (  5.4%)
       Vietnam ▏    9 ████ (  4.4%)
         China ▏    9 ████ (  4.4%)
   Netherlands ▏    8 ████ (  3.9%)
       Germany ▏    8 ████ (  3.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-12 ▏   27 ████████████ ( 12.1%)
2025-06-13 ▏    9 ████ (  4.0%)
2025-06-14 ▏   47 █████████████████████ ( 21.0%)
2025-06-15 ▏   77 ███████████████████████████████████ ( 34.4%)
2025-06-16 ▏   64 █████████████████████████████ ( 28.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!