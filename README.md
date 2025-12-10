# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-494-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--10-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 494                      |
| Total Reports: 9,434                 |
| Unique Sources: 2,598                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2728 ███████████████████████████████████ ( 29.1%)
         HTTP Bad User Agent ▏ 2076 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1050 █████████████ ( 11.2%)
HTTP Admin Interface Probing ▏ 1019 █████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  596 ███████ (  6.3%)
      HTTP Crawl Non Statics ▏  394 █████ (  4.2%)
       CVE-2017-9841 Exploit ▏  390 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  377 ████ (  4.0%)
            HTTP CVE Probing ▏  335 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  137 █ (  1.5%)
      CVE-2022-41082 Exploit ▏   95 █ (  1.0%)
                 Netgear RCE ▏   76 █ (  0.8%)
 HTTP Path Traversal Probing ▏   40 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   39 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   35 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2843 ███████████████████████████████████ ( 35.1%)
United Kingdom ▏ 1531 ██████████████████ ( 18.9%)
       Ireland ▏  930 ███████████ ( 11.5%)
   Netherlands ▏  622 ███████ (  7.7%)
        France ▏  465 █████ (  5.7%)
         Japan ▏  460 █████ (  5.7%)
     Singapore ▏  403 ████ (  5.0%)
     Australia ▏  300 ███ (  3.7%)
       Germany ▏  289 ███ (  3.6%)
      Bulgaria ▏  258 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-03 ▏   36 ███████████████████████████████████ ( 18.6%)
2025-12-04 ▏   24 ███████████████████████ ( 12.4%)
2025-12-05 ▏   27 ██████████████████████████ ( 13.9%)
2025-12-06 ▏   35 ██████████████████████████████████ ( 18.0%)
2025-12-07 ▏   19 ██████████████████ (  9.8%)
2025-12-08 ▏   30 █████████████████████████████ ( 15.5%)
2025-12-09 ▏   23 ██████████████████████ ( 11.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!