# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-438-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--30-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 438                      |
| Total Reports: 10,154                |
| Unique Sources: 2,802                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2963 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏ 2231 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1124 █████████████ ( 11.1%)
HTTP Admin Interface Probing ▏ 1105 █████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  648 ███████ (  6.4%)
      HTTP Crawl Non Statics ▏  427 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  406 ████ (  4.0%)
       CVE-2017-9841 Exploit ▏  400 ████ (  4.0%)
            HTTP CVE Probing ▏  357 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  139 █ (  1.4%)
      CVE-2022-41082 Exploit ▏  103 █ (  1.0%)
                 Netgear RCE ▏   85 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   37 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3097 ███████████████████████████████████ ( 35.6%)
United Kingdom ▏ 1621 ██████████████████ ( 18.6%)
       Ireland ▏  977 ███████████ ( 11.2%)
   Netherlands ▏  662 ███████ (  7.6%)
         Japan ▏  492 █████ (  5.6%)
        France ▏  475 █████ (  5.5%)
     Singapore ▏  440 ████ (  5.1%)
     Australia ▏  338 ███ (  3.9%)
       Germany ▏  328 ███ (  3.8%)
      Bulgaria ▏  279 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-23 ▏   34 ████████████████████████ ( 12.6%)
2025-12-24 ▏   42 ██████████████████████████████ ( 15.6%)
2025-12-25 ▏   36 ██████████████████████████ ( 13.3%)
2025-12-26 ▏   42 ██████████████████████████████ ( 15.6%)
2025-12-27 ▏   31 ██████████████████████ ( 11.5%)
2025-12-28 ▏   35 █████████████████████████ ( 13.0%)
2025-12-29 ▏   48 ███████████████████████████████████ ( 17.8%)
2025-12-30 ▏    2 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!