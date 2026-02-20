# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-360-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 360                      |
| Total Reports: 11,890                |
| Unique Sources: 3,216                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3483 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2522 █████████████████████████ ( 21.3%)
HTTP Admin Interface Probing ▏ 1371 █████████████ ( 11.6%)
        HTTP Sensitive Files ▏ 1244 ████████████ ( 10.5%)
         HTTP Wordpress Scan ▏  863 ████████ (  7.3%)
      HTTP Crawl Non Statics ▏  517 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  496 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  427 ████ (  3.6%)
            HTTP CVE Probing ▏  420 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  125 █ (  1.1%)
                 Netgear RCE ▏   97 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   42 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3667 ███████████████████████████████████ ( 36.1%)
United Kingdom ▏ 1753 ████████████████ ( 17.3%)
       Ireland ▏ 1098 ██████████ ( 10.8%)
   Netherlands ▏  753 ███████ (  7.4%)
     Singapore ▏  588 █████ (  5.8%)
         Japan ▏  584 █████ (  5.8%)
        France ▏  578 █████ (  5.7%)
       Germany ▏  399 ███ (  3.9%)
     Australia ▏  381 ███ (  3.8%)
         India ▏  354 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-02-13 ▏   36 ███████████████████████████████████ ( 17.1%)
2026-02-14 ▏   35 ██████████████████████████████████ ( 16.7%)
2026-02-15 ▏   12 ███████████ (  5.7%)
2026-02-16 ▏   30 █████████████████████████████ ( 14.3%)
2026-02-17 ▏   28 ███████████████████████████ ( 13.3%)
2026-02-18 ▏   32 ███████████████████████████████ ( 15.2%)
2026-02-19 ▏   33 ████████████████████████████████ ( 15.7%)
2026-02-20 ▏    4 ███ (  1.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!