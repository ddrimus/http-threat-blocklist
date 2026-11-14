# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-374-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 374                      |
| Total Reports: 22,664                |
| Unique Sources: 5,890                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6822 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3740 ███████████████████ ( 16.6%)
HTTP Admin Interface Probing ▏ 2813 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2707 █████████████ ( 12.0%)
         HTTP Wordpress Scan ▏ 1551 ███████ (  6.9%)
      HTTP Crawl Non Statics ▏ 1298 ██████ (  5.8%)
            HTTP CVE Probing ▏  950 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  745 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  688 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  381 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  269 █ (  1.2%)
                 Netgear RCE ▏  181 █ (  0.8%)
 HTTP Path Traversal Probing ▏  158 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  107 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   68 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7396 ███████████████████████████████████ ( 41.9%)
United Kingdom ▏ 1919 █████████ ( 10.9%)
   Netherlands ▏ 1615 ███████ (  9.2%)
       Ireland ▏ 1283 ██████ (  7.3%)
        France ▏ 1272 ██████ (  7.2%)
     Singapore ▏ 1050 ████ (  6.0%)
        Canada ▏  807 ███ (  4.6%)
       Germany ▏  792 ███ (  4.5%)
         Japan ▏  777 ███ (  4.4%)
      Bulgaria ▏  736 ███ (  4.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-11-07 ▏   20 ███████████████████ ( 11.2%)
2026-11-08 ▏   23 ██████████████████████ ( 12.8%)
2026-11-09 ▏   36 ███████████████████████████████████ ( 20.1%)
2026-11-10 ▏   33 ████████████████████████████████ ( 18.4%)
2026-11-11 ▏   19 ██████████████████ ( 10.6%)
2026-11-12 ▏   23 ██████████████████████ ( 12.8%)
2026-11-13 ▏   25 ████████████████████████ ( 14.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!