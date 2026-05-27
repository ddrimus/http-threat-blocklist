# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-500-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--05--27-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 500                      |
| Total Reports: 16,555                |
| Unique Sources: 4,386                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4916 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 3050 █████████████████████ ( 18.5%)
HTTP Admin Interface Probing ▏ 2153 ███████████████ ( 13.1%)
        HTTP Sensitive Files ▏ 1643 ███████████ ( 10.0%)
         HTTP Wordpress Scan ▏ 1439 ██████████ (  8.7%)
      HTTP Crawl Non Statics ▏  898 ██████ (  5.5%)
     HTTP Backdoors Attempts ▏  675 ████ (  4.1%)
            HTTP CVE Probing ▏  603 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  453 ███ (  2.8%)
      CVE-2022-41082 Exploit ▏  179 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.9%)
                 Netgear RCE ▏  130 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   68 █ (  0.4%)
 HTTP Path Traversal Probing ▏   61 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   52 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5304 ███████████████████████████████████ ( 39.1%)
United Kingdom ▏ 1784 ███████████ ( 13.2%)
       Ireland ▏ 1277 ████████ (  9.4%)
   Netherlands ▏  993 ██████ (  7.3%)
        France ▏  877 █████ (  6.5%)
     Singapore ▏  765 █████ (  5.6%)
         Japan ▏  719 ████ (  5.3%)
        Canada ▏  708 ████ (  5.2%)
       Germany ▏  619 ████ (  4.6%)
     Australia ▏  507 ███ (  3.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-20 ▏   65 ██████████████████████████████ ( 15.9%)
2026-05-21 ▏   62 ████████████████████████████ ( 15.2%)
2026-05-22 ▏   75 ███████████████████████████████████ ( 18.4%)
2026-05-23 ▏   38 █████████████████ (  9.3%)
2026-05-24 ▏   67 ███████████████████████████████ ( 16.4%)
2026-05-25 ▏   36 ████████████████ (  8.8%)
2026-05-26 ▏   64 █████████████████████████████ ( 15.7%)
2026-05-27 ▏    1 █ (  0.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!