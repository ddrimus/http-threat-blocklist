# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-440-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--01--08-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 440                      |
| Total Reports: 10,490                |
| Unique Sources: 2,887                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3088 ███████████████████████████████████ ( 29.6%)
         HTTP Bad User Agent ▏ 2305 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1153 █████████████ ( 11.0%)
HTTP Admin Interface Probing ▏ 1148 █████████████ ( 11.0%)
         HTTP Wordpress Scan ▏  675 ███████ (  6.5%)
      HTTP Crawl Non Statics ▏  438 ████ (  4.2%)
     HTTP Backdoors Attempts ▏  411 ████ (  3.9%)
       CVE-2017-9841 Exploit ▏  406 ████ (  3.9%)
            HTTP CVE Probing ▏  361 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  140 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  106 █ (  1.0%)
                 Netgear RCE ▏   85 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   47 █ (  0.5%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   39 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3256 ███████████████████████████████████ ( 36.2%)
United Kingdom ▏ 1646 █████████████████ ( 18.3%)
       Ireland ▏  986 ██████████ ( 11.0%)
   Netherlands ▏  681 ███████ (  7.6%)
         Japan ▏  496 █████ (  5.5%)
        France ▏  489 █████ (  5.4%)
     Singapore ▏  461 ████ (  5.1%)
       Germany ▏  354 ███ (  3.9%)
     Australia ▏  342 ███ (  3.8%)
      Bulgaria ▏  286 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-01-01 ▏   39 ██████████████████████████ ( 14.1%)
2026-01-02 ▏   44 █████████████████████████████ ( 15.9%)
2026-01-03 ▏   37 ████████████████████████ ( 13.4%)
2026-01-04 ▏   52 ███████████████████████████████████ ( 18.8%)
2026-01-05 ▏   30 ████████████████████ ( 10.9%)
2026-01-06 ▏   41 ███████████████████████████ ( 14.9%)
2026-01-07 ▏   29 ███████████████████ ( 10.5%)
2026-01-08 ▏    4 ██ (  1.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!