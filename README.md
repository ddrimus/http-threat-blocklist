# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-550-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--06--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 550                      |
| Total Reports: 17,452                |
| Unique Sources: 4,643                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5196 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 3179 █████████████████████ ( 18.3%)
HTTP Admin Interface Probing ▏ 2251 ███████████████ ( 13.0%)
        HTTP Sensitive Files ▏ 1819 ████████████ ( 10.5%)
         HTTP Wordpress Scan ▏ 1472 █████████ (  8.5%)
      HTTP Crawl Non Statics ▏  976 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  682 ████ (  3.9%)
            HTTP CVE Probing ▏  646 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  457 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏  195 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  138 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   76 █ (  0.4%)
 HTTP Path Traversal Probing ▏   63 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   55 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5680 ███████████████████████████████████ ( 39.9%)
United Kingdom ▏ 1800 ███████████ ( 12.7%)
       Ireland ▏ 1281 ███████ (  9.0%)
   Netherlands ▏ 1101 ██████ (  7.7%)
        France ▏  953 █████ (  6.7%)
     Singapore ▏  791 ████ (  5.6%)
        Canada ▏  747 ████ (  5.3%)
         Japan ▏  722 ████ (  5.1%)
       Germany ▏  633 ███ (  4.5%)
     Australia ▏  516 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-06-07 ▏   39 ███████████████ ( 12.0%)
2026-06-08 ▏   40 ████████████████ ( 12.3%)
2026-06-09 ▏   33 █████████████ ( 10.2%)
2026-06-10 ▏   38 ███████████████ ( 11.7%)
2026-06-11 ▏   87 ███████████████████████████████████ ( 26.8%)
2026-06-12 ▏   47 ██████████████████ ( 14.5%)
2026-06-13 ▏   38 ███████████████ ( 11.7%)
2026-06-14 ▏    3 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!