# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-546-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--30-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 546                      |
| Total Reports: 2,603                 |
| Unique Sources: 874                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  646 ███████████████████████████████████ ( 24.9%)
         HTTP Bad User Agent ▏  613 █████████████████████████████████ ( 23.6%)
HTTP Admin Interface Probing ▏  276 ██████████████ ( 10.6%)
        HTTP Sensitive Files ▏  211 ███████████ (  8.1%)
         HTTP Wordpress Scan ▏  196 ██████████ (  7.6%)
       CVE-2017-9841 Exploit ▏  172 █████████ (  6.6%)
     HTTP Backdoors Attempts ▏  132 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  118 ██████ (  4.6%)
   CVE-2018-20062 (Thinkphp) ▏   82 ████ (  3.2%)
            HTTP CVE Probing ▏   79 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   25 █ (  1.0%)
                 Netgear RCE ▏   15 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.4%)
 HTTP Path Traversal Probing ▏   11 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    6 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  721 ███████████████████████████████████ ( 31.2%)
United Kingdom ▏  507 ████████████████████████ ( 21.9%)
       Ireland ▏  428 ████████████████████ ( 18.5%)
         Japan ▏  145 ███████ (  6.3%)
     Australia ▏  133 ██████ (  5.8%)
   Netherlands ▏  102 ████ (  4.4%)
     Singapore ▏   91 ████ (  3.9%)
       Germany ▏   73 ███ (  3.2%)
         China ▏   63 ███ (  2.7%)
      Bulgaria ▏   47 ██ (  2.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-23 ▏   75 ██████████████████████████████████ ( 16.2%)
2025-07-24 ▏   60 ███████████████████████████ ( 13.0%)
2025-07-25 ▏   76 ███████████████████████████████████ ( 16.5%)
2025-07-26 ▏   69 ███████████████████████████████ ( 14.9%)
2025-07-27 ▏   61 ████████████████████████████ ( 13.2%)
2025-07-28 ▏   65 █████████████████████████████ ( 14.1%)
2025-07-29 ▏   52 ███████████████████████ ( 11.3%)
2025-07-30 ▏    4 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!