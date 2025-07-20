# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-483-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 483                      |
| Total Reports: 1,885                 |
| Unique Sources: 681                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  461 ███████████████████████████████████ ( 24.6%)
         HTTP Bad User Agent ▏  460 ██████████████████████████████████ ( 24.5%)
HTTP Admin Interface Probing ▏  199 ███████████████ ( 10.6%)
        HTTP Sensitive Files ▏  154 ███████████ (  8.2%)
         HTTP Wordpress Scan ▏  140 ██████████ (  7.5%)
       CVE-2017-9841 Exploit ▏  114 ████████ (  6.1%)
     HTTP Backdoors Attempts ▏   96 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏   91 ██████ (  4.9%)
            HTTP CVE Probing ▏   56 ████ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏   54 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   20 █ (  1.1%)
                 Netgear RCE ▏   11 █ (  0.6%)
 HTTP Path Traversal Probing ▏    9 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    5 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  512 ███████████████████████████████████ ( 30.4%)
United Kingdom ▏  393 ██████████████████████████ ( 23.4%)
       Ireland ▏  360 ████████████████████████ ( 21.4%)
   Netherlands ▏   84 █████ (  5.0%)
         Japan ▏   80 █████ (  4.8%)
     Singapore ▏   65 ████ (  3.9%)
     Australia ▏   64 ████ (  3.8%)
       Germany ▏   48 ███ (  2.9%)
         China ▏   42 ██ (  2.5%)
      Bulgaria ▏   35 ██ (  2.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-13 ▏   80 ██████████████████████████ ( 13.1%)
2025-07-14 ▏   53 █████████████████ (  8.7%)
2025-07-15 ▏  104 ██████████████████████████████████ ( 17.0%)
2025-07-16 ▏   88 █████████████████████████████ ( 14.4%)
2025-07-17 ▏   88 █████████████████████████████ ( 14.4%)
2025-07-18 ▏  105 ███████████████████████████████████ ( 17.2%)
2025-07-19 ▏   85 ████████████████████████████ ( 13.9%)
2025-07-20 ▏    7 ██ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!