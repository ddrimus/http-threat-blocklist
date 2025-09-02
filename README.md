# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-573-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--02-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 573                      |
| Total Reports: 4,510                 |
| Unique Sources: 1,346                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1141 ███████████████████████████████████ ( 25.4%)
         HTTP Bad User Agent ▏ 1022 ███████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  483 ██████████████ ( 10.7%)
        HTTP Sensitive Files ▏  389 ███████████ (  8.7%)
         HTTP Wordpress Scan ▏  366 ███████████ (  8.1%)
       CVE-2017-9841 Exploit ▏  271 ████████ (  6.0%)
      HTTP Crawl Non Statics ▏  221 ██████ (  4.9%)
     HTTP Backdoors Attempts ▏  217 ██████ (  4.8%)
            HTTP CVE Probing ▏  150 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏  111 ███ (  2.5%)
      CVE-2022-41082 Exploit ▏   37 █ (  0.8%)
                 Netgear RCE ▏   30 █ (  0.7%)
 HTTP Path Traversal Probing ▏   29 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   14 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1206 ███████████████████████████████████ ( 31.0%)
United Kingdom ▏  673 ███████████████████ ( 17.3%)
       Ireland ▏  592 █████████████████ ( 15.2%)
        France ▏  301 ████████ (  7.7%)
     Australia ▏  249 ███████ (  6.4%)
         Japan ▏  237 ██████ (  6.1%)
     Singapore ▏  218 ██████ (  5.6%)
       Germany ▏  144 ████ (  3.7%)
      Bulgaria ▏  136 ███ (  3.5%)
   Netherlands ▏  135 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-26 ▏   85 ███████████████████████████████████ ( 23.1%)
2025-08-27 ▏   50 ████████████████████ ( 13.6%)
2025-08-28 ▏   45 ██████████████████ ( 12.2%)
2025-08-29 ▏   59 ████████████████████████ ( 16.0%)
2025-08-30 ▏   55 ██████████████████████ ( 14.9%)
2025-08-31 ▏   48 ███████████████████ ( 13.0%)
2025-09-01 ▏   23 █████████ (  6.2%)
2025-09-02 ▏    3 █ (  0.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!