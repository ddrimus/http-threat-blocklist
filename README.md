# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-540-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--06--06-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 540                      |
| Total Reports: 17,083                |
| Unique Sources: 4,535                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5072 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 3130 █████████████████████ ( 18.4%)
HTTP Admin Interface Probing ▏ 2216 ███████████████ ( 13.0%)
        HTTP Sensitive Files ▏ 1740 ████████████ ( 10.2%)
         HTTP Wordpress Scan ▏ 1463 ██████████ (  8.6%)
      HTTP Crawl Non Statics ▏  952 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  682 ████ (  4.0%)
            HTTP CVE Probing ▏  627 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  455 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏  187 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.9%)
                 Netgear RCE ▏  135 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   71 █ (  0.4%)
 HTTP Path Traversal Probing ▏   61 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   52 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5529 ███████████████████████████████████ ( 39.6%)
United Kingdom ▏ 1798 ███████████ ( 12.9%)
       Ireland ▏ 1280 ████████ (  9.2%)
   Netherlands ▏ 1042 ██████ (  7.5%)
        France ▏  910 █████ (  6.5%)
     Singapore ▏  776 ████ (  5.6%)
        Canada ▏  747 ████ (  5.4%)
         Japan ▏  722 ████ (  5.2%)
       Germany ▏  631 ███ (  4.5%)
     Australia ▏  511 ███ (  3.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-30 ▏   53 █████████████████████████████████ ( 16.2%)
2026-05-31 ▏   42 ██████████████████████████ ( 12.8%)
2026-06-01 ▏   42 ██████████████████████████ ( 12.8%)
2026-06-02 ▏   35 ██████████████████████ ( 10.7%)
2026-06-03 ▏   54 ██████████████████████████████████ ( 16.5%)
2026-06-04 ▏   55 ███████████████████████████████████ ( 16.8%)
2026-06-05 ▏   43 ███████████████████████████ ( 13.1%)
2026-06-06 ▏    3 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!