# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-399-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--10--05-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 399                      |
| Total Reports: 21,127                |
| Unique Sources: 5,526                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6353 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3601 ███████████████████ ( 17.2%)
HTTP Admin Interface Probing ▏ 2617 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2449 █████████████ ( 11.7%)
         HTTP Wordpress Scan ▏ 1530 ████████ (  7.3%)
      HTTP Crawl Non Statics ▏ 1198 ██████ (  5.7%)
            HTTP CVE Probing ▏  867 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.3%)
       CVE-2017-9841 Exploit ▏  655 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  309 █ (  1.5%)
      CVE-2022-41082 Exploit ▏  248 █ (  1.2%)
                 Netgear RCE ▏  171 █ (  0.8%)
 HTTP Path Traversal Probing ▏  106 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏  102 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   65 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6906 ███████████████████████████████████ ( 41.4%)
United Kingdom ▏ 1887 █████████ ( 11.3%)
   Netherlands ▏ 1558 ███████ (  9.3%)
       Ireland ▏ 1282 ██████ (  7.7%)
        France ▏ 1206 ██████ (  7.2%)
     Singapore ▏  962 ████ (  5.8%)
        Canada ▏  789 ███ (  4.7%)
         Japan ▏  766 ███ (  4.6%)
       Germany ▏  734 ███ (  4.4%)
      Bulgaria ▏  595 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-09-28 ▏   44 ████████████████ ( 12.6%)
2026-09-29 ▏   62 ███████████████████████ ( 17.7%)
2026-09-30 ▏   28 ██████████ (  8.0%)
2026-10-01 ▏   91 ███████████████████████████████████ ( 26.0%)
2026-10-02 ▏   50 ███████████████████ ( 14.3%)
2026-10-03 ▏   21 ████████ (  6.0%)
2026-10-04 ▏   48 ██████████████████ ( 13.7%)
2026-10-05 ▏    6 ██ (  1.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!