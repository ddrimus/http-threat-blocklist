# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-441-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--29-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 441                      |
| Total Reports: 10,110                |
| Unique Sources: 2,791                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2950 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏ 2224 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1119 █████████████ ( 11.1%)
HTTP Admin Interface Probing ▏ 1098 █████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  643 ███████ (  6.4%)
      HTTP Crawl Non Statics ▏  426 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  402 ████ (  4.0%)
       CVE-2017-9841 Exploit ▏  400 ████ (  4.0%)
            HTTP CVE Probing ▏  357 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  139 █ (  1.4%)
      CVE-2022-41082 Exploit ▏  101 █ (  1.0%)
                 Netgear RCE ▏   85 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   37 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3074 ███████████████████████████████████ ( 35.4%)
United Kingdom ▏ 1618 ██████████████████ ( 18.7%)
       Ireland ▏  977 ███████████ ( 11.3%)
   Netherlands ▏  662 ███████ (  7.6%)
         Japan ▏  492 █████ (  5.7%)
        France ▏  471 █████ (  5.4%)
     Singapore ▏  436 ████ (  5.0%)
     Australia ▏  338 ███ (  3.9%)
       Germany ▏  326 ███ (  3.8%)
      Bulgaria ▏  279 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-22 ▏   35 █████████████████████████████ ( 13.1%)
2025-12-23 ▏   41 ██████████████████████████████████ ( 15.3%)
2025-12-24 ▏   42 ███████████████████████████████████ ( 15.7%)
2025-12-25 ▏   36 ██████████████████████████████ ( 13.4%)
2025-12-26 ▏   42 ███████████████████████████████████ ( 15.7%)
2025-12-27 ▏   31 █████████████████████████ ( 11.6%)
2025-12-28 ▏   35 █████████████████████████████ ( 13.1%)
2025-12-29 ▏    6 █████ (  2.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!