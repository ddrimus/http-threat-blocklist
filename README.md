# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-336-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--09--07-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 336                      |
| Total Reports: 19,826                |
| Unique Sources: 5,234                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5981 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3494 ████████████████████ ( 17.8%)
HTTP Admin Interface Probing ▏ 2455 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2240 █████████████ ( 11.4%)
         HTTP Wordpress Scan ▏ 1526 ████████ (  7.8%)
      HTTP Crawl Non Statics ▏ 1090 ██████ (  5.5%)
            HTTP CVE Probing ▏  791 ████ (  4.0%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  557 ███ (  2.8%)
      CVE-2022-41082 Exploit ▏  233 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  223 █ (  1.1%)
                 Netgear RCE ▏  163 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   95 █ (  0.5%)
 HTTP Path Traversal Probing ▏   84 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   63 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6558 ███████████████████████████████████ ( 41.0%)
United Kingdom ▏ 1849 █████████ ( 11.6%)
   Netherlands ▏ 1474 ███████ (  9.2%)
       Ireland ▏ 1281 ██████ (  8.0%)
        France ▏ 1179 ██████ (  7.4%)
     Singapore ▏  849 ████ (  5.3%)
        Canada ▏  780 ████ (  4.9%)
         Japan ▏  761 ████ (  4.8%)
       Germany ▏  703 ███ (  4.4%)
      Bulgaria ▏  571 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-08-31 ▏   30 ████████████ ( 10.5%)
2026-09-01 ▏   26 ██████████ (  9.1%)
2026-09-02 ▏   28 ███████████ (  9.8%)
2026-09-03 ▏   84 ███████████████████████████████████ ( 29.5%)
2026-09-04 ▏   36 ███████████████ ( 12.6%)
2026-09-05 ▏   34 ██████████████ ( 11.9%)
2026-09-06 ▏   45 ██████████████████ ( 15.8%)
2026-09-07 ▏    2 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!