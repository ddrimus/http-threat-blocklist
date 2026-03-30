# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-397-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--30-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 397                      |
| Total Reports: 13,455                |
| Unique Sources: 3,551                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3989 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2663 ███████████████████████ ( 19.9%)
HTTP Admin Interface Probing ▏ 1669 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 1299 ███████████ (  9.7%)
         HTTP Wordpress Scan ▏ 1130 █████████ (  8.4%)
      HTTP Crawl Non Statics ▏  640 █████ (  4.8%)
     HTTP Backdoors Attempts ▏  552 ████ (  4.1%)
            HTTP CVE Probing ▏  464 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  440 ███ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  141 █ (  1.1%)
                 Netgear RCE ▏  105 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   58 █ (  0.4%)
 HTTP Path Traversal Probing ▏   46 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   45 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4133 ███████████████████████████████████ ( 36.7%)
United Kingdom ▏ 1759 ██████████████ ( 15.6%)
       Ireland ▏ 1172 █████████ ( 10.4%)
   Netherlands ▏  822 ██████ (  7.3%)
        France ▏  683 █████ (  6.1%)
         Japan ▏  677 █████ (  6.0%)
     Singapore ▏  673 █████ (  6.0%)
       Germany ▏  483 ████ (  4.3%)
        Canada ▏  431 ███ (  3.8%)
     Australia ▏  428 ███ (  3.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-23 ▏   43 ██████████████████████ ( 12.7%)
2026-03-24 ▏   59 ███████████████████████████████ ( 17.4%)
2026-03-25 ▏   55 █████████████████████████████ ( 16.2%)
2026-03-26 ▏   66 ███████████████████████████████████ ( 19.5%)
2026-03-27 ▏   52 ███████████████████████████ ( 15.3%)
2026-03-28 ▏   36 ███████████████████ ( 10.6%)
2026-03-29 ▏   26 █████████████ (  7.7%)
2026-03-30 ▏    2 █ (  0.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!