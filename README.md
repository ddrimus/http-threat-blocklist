# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-461-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 461                      |
| Total Reports: 9,800                 |
| Unique Sources: 2,702                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2854 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏ 2154 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1094 █████████████ ( 11.2%)
HTTP Admin Interface Probing ▏ 1056 ████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  619 ███████ (  6.3%)
      HTTP Crawl Non Statics ▏  409 █████ (  4.2%)
       CVE-2017-9841 Exploit ▏  399 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  388 ████ (  4.0%)
            HTTP CVE Probing ▏  346 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  138 █ (  1.4%)
      CVE-2022-41082 Exploit ▏   99 █ (  1.0%)
                 Netgear RCE ▏   80 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   35 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2971 ███████████████████████████████████ ( 35.3%)
United Kingdom ▏ 1594 ██████████████████ ( 18.9%)
       Ireland ▏  950 ███████████ ( 11.3%)
   Netherlands ▏  647 ███████ (  7.7%)
         Japan ▏  470 █████ (  5.6%)
        France ▏  467 █████ (  5.5%)
     Singapore ▏  418 ████ (  5.0%)
     Australia ▏  327 ███ (  3.9%)
       Germany ▏  302 ███ (  3.6%)
      Bulgaria ▏  272 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-13 ▏   31 ██████████████████████ ( 11.8%)
2025-12-14 ▏   27 ███████████████████ ( 10.3%)
2025-12-15 ▏   45 ████████████████████████████████ ( 17.2%)
2025-12-16 ▏   41 █████████████████████████████ ( 15.6%)
2025-12-17 ▏   34 ████████████████████████ ( 13.0%)
2025-12-18 ▏   49 ███████████████████████████████████ ( 18.7%)
2025-12-19 ▏   30 █████████████████████ ( 11.5%)
2025-12-20 ▏    5 ███ (  1.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!