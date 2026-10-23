# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-414-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--10--23-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 414                      |
| Total Reports: 21,976                |
| Unique Sources: 5,713                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6608 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3665 ███████████████████ ( 16.8%)
HTTP Admin Interface Probing ▏ 2721 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2595 █████████████ ( 11.9%)
         HTTP Wordpress Scan ▏ 1541 ████████ (  7.1%)
      HTTP Crawl Non Statics ▏ 1257 ██████ (  5.8%)
            HTTP CVE Probing ▏  906 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  715 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  354 █ (  1.6%)
      CVE-2022-41082 Exploit ▏  257 █ (  1.2%)
                 Netgear RCE ▏  176 █ (  0.8%)
 HTTP Path Traversal Probing ▏  150 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  104 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   67 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7176 ███████████████████████████████████ ( 41.8%)
United Kingdom ▏ 1899 █████████ ( 11.1%)
   Netherlands ▏ 1580 ███████ (  9.2%)
       Ireland ▏ 1283 ██████ (  7.5%)
        France ▏ 1234 ██████ (  7.2%)
     Singapore ▏ 1015 ████ (  5.9%)
        Canada ▏  802 ███ (  4.7%)
         Japan ▏  776 ███ (  4.5%)
       Germany ▏  765 ███ (  4.5%)
      Bulgaria ▏  644 ███ (  3.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-10-16 ▏   46 █████████████ ( 10.1%)
2026-10-17 ▏  115 ██████████████████████████████████ ( 25.3%)
2026-10-18 ▏  118 ███████████████████████████████████ ( 26.0%)
2026-10-19 ▏   39 ███████████ (  8.6%)
2026-10-20 ▏   36 ██████████ (  7.9%)
2026-10-21 ▏   51 ███████████████ ( 11.2%)
2026-10-22 ▏   39 ███████████ (  8.6%)
2026-10-23 ▏   10 ██ (  2.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!