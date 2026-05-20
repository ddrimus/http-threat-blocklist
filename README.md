# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-487-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--05--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 487                      |
| Total Reports: 16,147                |
| Unique Sources: 4,272                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4799 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 2991 █████████████████████ ( 18.6%)
HTTP Admin Interface Probing ▏ 2099 ███████████████ ( 13.1%)
        HTTP Sensitive Files ▏ 1586 ███████████ (  9.9%)
         HTTP Wordpress Scan ▏ 1410 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  867 ██████ (  5.4%)
     HTTP Backdoors Attempts ▏  668 ████ (  4.2%)
            HTTP CVE Probing ▏  583 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  450 ███ (  2.8%)
      CVE-2022-41082 Exploit ▏  173 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.9%)
                 Netgear RCE ▏  128 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   65 █ (  0.4%)
 HTTP Path Traversal Probing ▏   59 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   50 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5093 ███████████████████████████████████ ( 38.4%)
United Kingdom ▏ 1779 ████████████ ( 13.4%)
       Ireland ▏ 1277 ████████ (  9.6%)
   Netherlands ▏  963 ██████ (  7.3%)
        France ▏  870 █████ (  6.6%)
     Singapore ▏  761 █████ (  5.7%)
         Japan ▏  714 ████ (  5.4%)
        Canada ▏  683 ████ (  5.2%)
       Germany ▏  608 ████ (  4.6%)
     Australia ▏  507 ███ (  3.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-13 ▏   41 ████████████████████ ( 10.6%)
2026-05-14 ▏   59 █████████████████████████████ ( 15.3%)
2026-05-15 ▏   29 ██████████████ (  7.5%)
2026-05-16 ▏   54 ███████████████████████████ ( 14.0%)
2026-05-17 ▏   55 ███████████████████████████ ( 14.2%)
2026-05-18 ▏   70 ███████████████████████████████████ ( 18.1%)
2026-05-19 ▏   69 ██████████████████████████████████ ( 17.9%)
2026-05-20 ▏    9 ████ (  2.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!