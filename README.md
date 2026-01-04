# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-424-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--01--04-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 424                      |
| Total Reports: 10,335                |
| Unique Sources: 2,843                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3025 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2268 ██████████████████████████ ( 22.0%)
        HTTP Sensitive Files ▏ 1141 █████████████ ( 11.1%)
HTTP Admin Interface Probing ▏ 1134 █████████████ ( 11.0%)
         HTTP Wordpress Scan ▏  667 ███████ (  6.5%)
      HTTP Crawl Non Statics ▏  435 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  409 ████ (  4.0%)
       CVE-2017-9841 Exploit ▏  402 ████ (  3.9%)
            HTTP CVE Probing ▏  359 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  139 █ (  1.4%)
      CVE-2022-41082 Exploit ▏  104 █ (  1.0%)
                 Netgear RCE ▏   85 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   38 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3198 ███████████████████████████████████ ( 36.0%)
United Kingdom ▏ 1640 █████████████████ ( 18.5%)
       Ireland ▏  980 ██████████ ( 11.0%)
   Netherlands ▏  673 ███████ (  7.6%)
         Japan ▏  495 █████ (  5.6%)
        France ▏  481 █████ (  5.4%)
     Singapore ▏  450 ████ (  5.1%)
     Australia ▏  338 ███ (  3.8%)
       Germany ▏  337 ███ (  3.8%)
      Bulgaria ▏  282 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-28 ▏   33 ████████████████████████ ( 12.5%)
2025-12-29 ▏   48 ███████████████████████████████████ ( 18.2%)
2025-12-30 ▏   31 ██████████████████████ ( 11.7%)
2025-12-31 ▏   30 █████████████████████ ( 11.4%)
2026-01-01 ▏   40 █████████████████████████████ ( 15.2%)
2026-01-02 ▏   44 ████████████████████████████████ ( 16.7%)
2026-01-03 ▏   37 ██████████████████████████ ( 14.0%)
2026-01-04 ▏    1 █ (  0.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!