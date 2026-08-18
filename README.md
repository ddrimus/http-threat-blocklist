# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-290-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--08--18-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 290                      |
| Total Reports: 19,169                |
| Unique Sources: 5,052                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5766 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3428 ████████████████████ ( 18.0%)
HTTP Admin Interface Probing ▏ 2404 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 2137 ████████████ ( 11.2%)
         HTTP Wordpress Scan ▏ 1521 █████████ (  8.0%)
      HTTP Crawl Non Statics ▏ 1066 ██████ (  5.6%)
            HTTP CVE Probing ▏  745 ████ (  3.9%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  503 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏  224 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  178 █ (  0.9%)
                 Netgear RCE ▏  158 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   93 █ (  0.5%)
 HTTP Path Traversal Probing ▏   72 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   61 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6343 ███████████████████████████████████ ( 40.7%)
United Kingdom ▏ 1842 ██████████ ( 11.8%)
   Netherlands ▏ 1428 ███████ (  9.2%)
       Ireland ▏ 1281 ███████ (  8.2%)
        France ▏ 1154 ██████ (  7.4%)
     Singapore ▏  822 ████ (  5.3%)
        Canada ▏  775 ████ (  5.0%)
         Japan ▏  736 ████ (  4.7%)
       Germany ▏  679 ███ (  4.4%)
     Australia ▏  517 ██ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-08-11 ▏   30 ██████████████████████████ ( 16.4%)
2026-08-12 ▏   24 █████████████████████ ( 13.1%)
2026-08-13 ▏   36 ████████████████████████████████ ( 19.7%)
2026-08-14 ▏   20 █████████████████ ( 10.9%)
2026-08-15 ▏   19 █████████████████ ( 10.4%)
2026-08-16 ▏   12 ██████████ (  6.6%)
2026-08-17 ▏   39 ███████████████████████████████████ ( 21.3%)
2026-08-18 ▏    3 ██ (  1.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!