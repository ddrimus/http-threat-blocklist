# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-529-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--13-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 529                      |
| Total Reports: 3,329                 |
| Unique Sources: 1,051                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  827 ███████████████████████████████████ ( 24.9%)
         HTTP Bad User Agent ▏  744 ███████████████████████████████ ( 22.4%)
HTTP Admin Interface Probing ▏  355 ███████████████ ( 10.7%)
         HTTP Wordpress Scan ▏  279 ███████████ (  8.4%)
        HTTP Sensitive Files ▏  263 ███████████ (  7.9%)
       CVE-2017-9841 Exploit ▏  223 █████████ (  6.7%)
     HTTP Backdoors Attempts ▏  176 ███████ (  5.3%)
      HTTP Crawl Non Statics ▏  154 ██████ (  4.6%)
   CVE-2018-20062 (Thinkphp) ▏  105 ████ (  3.2%)
            HTTP CVE Probing ▏  101 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   29 █ (  0.9%)
                 Netgear RCE ▏   22 █ (  0.7%)
 HTTP Path Traversal Probing ▏   20 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    8 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  890 ███████████████████████████████████ ( 30.5%)
United Kingdom ▏  577 ██████████████████████ ( 19.8%)
       Ireland ▏  517 ████████████████████ ( 17.7%)
         Japan ▏  208 ████████ (  7.1%)
     Australia ▏  187 ███████ (  6.4%)
     Singapore ▏  155 ██████ (  5.3%)
   Netherlands ▏  114 ████ (  3.9%)
        France ▏   98 ███ (  3.4%)
       Germany ▏   87 ███ (  3.0%)
         China ▏   82 ███ (  2.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-06 ▏   78 ██████████████████████████████████ ( 27.1%)
2025-08-07 ▏   65 ████████████████████████████ ( 22.6%)
2025-08-08 ▏   56 ████████████████████████ ( 19.4%)
2025-08-09 ▏    4 █ (  1.4%)
2025-08-12 ▏   79 ███████████████████████████████████ ( 27.4%)
2025-08-13 ▏    6 ██ (  2.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!