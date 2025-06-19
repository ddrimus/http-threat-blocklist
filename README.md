# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-178-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--18-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
╔══════════════════════════════════════╗
║           THREAT OVERVIEW            ║
╠══════════════════════════════════════╣
║ Status: LOW                          ║
║ Active IPs: 178                      ║
║ Total Reports: 315                   ║
║ Unique Sources: 178                  ║
╚══════════════════════════════════════╝
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

      HTTP Service Probing ▏   98 ███████████████████████████████████ ( 31.1%)
     Malicious User Agents ▏   85 ██████████████████████████████ ( 27.0%)
     CVE-2017-9841 Exploit ▏   30 ██████████ (  9.5%)
       CVE Exploit Probing ▏   17 ██████ (  5.4%)
   Admin Interface Probing ▏   16 █████ (  5.1%)
Non-Static Content Crawler ▏   14 █████ (  4.4%)
        WordPress Scanning ▏   13 ████ (  4.1%)
   ThinkPHP CVE-2018-20062 ▏   12 ████ (  3.8%)
  Backdoor Access Attempts ▏   11 ███ (  3.5%)
     Sensitive File Access ▏   10 ███ (  3.2%)
               Netgear_Rce ▏    4 █ (  1.3%)
       Jira_Cve 2021 26086 ▏    4 █ (  1.3%)
            Cve 2022 41082 ▏    1 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏   92 ███████████████████████████████████ ( 32.5%)
       Ireland ▏   56 █████████████████████ ( 19.8%)
United Kingdom ▏   34 ████████████ ( 12.0%)
     Singapore ▏   28 ██████████ (  9.9%)
         India ▏   16 ██████ (  5.7%)
         China ▏   15 █████ (  5.3%)
   Netherlands ▏   12 ████ (  4.2%)
      Bulgaria ▏   11 ████ (  3.9%)
       Germany ▏   10 ███ (  3.5%)
       Vietnam ▏    9 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-12 ▏   27 ████████████ (  8.6%)
2025-06-13 ▏    9 ████ (  2.9%)
2025-06-14 ▏   47 █████████████████████ ( 14.9%)
2025-06-15 ▏   77 ███████████████████████████████████ ( 24.4%)
2025-06-16 ▏   64 █████████████████████████████ ( 20.3%)
2025-06-17 ▏   35 ███████████████ ( 11.1%)
2025-06-18 ▏   56 █████████████████████████ ( 17.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!