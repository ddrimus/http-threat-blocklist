# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-506-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--30-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 506                      |
| Total Reports: 5,832                 |
| Unique Sources: 1,696                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1541 ███████████████████████████████████ ( 26.6%)
         HTTP Bad User Agent ▏ 1309 █████████████████████████████ ( 22.6%)
HTTP Admin Interface Probing ▏  627 ██████████████ ( 10.8%)
        HTTP Sensitive Files ▏  531 ████████████ (  9.2%)
         HTTP Wordpress Scan ▏  439 █████████ (  7.6%)
       CVE-2017-9841 Exploit ▏  300 ██████ (  5.2%)
      HTTP Crawl Non Statics ▏  288 ██████ (  5.0%)
     HTTP Backdoors Attempts ▏  259 █████ (  4.5%)
            HTTP CVE Probing ▏  201 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  121 ██ (  2.1%)
      CVE-2022-41082 Exploit ▏   56 █ (  1.0%)
                 Netgear RCE ▏   40 █ (  0.7%)
 HTTP Path Traversal Probing ▏   39 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   21 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1652 ███████████████████████████████████ ( 33.2%)
United Kingdom ▏  875 ██████████████████ ( 17.6%)
       Ireland ▏  735 ███████████████ ( 14.8%)
        France ▏  374 ███████ (  7.5%)
     Singapore ▏  278 █████ (  5.6%)
     Australia ▏  258 █████ (  5.2%)
         Japan ▏  240 █████ (  4.8%)
   Netherlands ▏  216 ████ (  4.3%)
       Germany ▏  192 ████ (  3.9%)
      Bulgaria ▏  161 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-23 ▏   59 ███████████████████████████████████ ( 19.0%)
2025-09-24 ▏   41 ████████████████████████ ( 13.2%)
2025-09-25 ▏   46 ███████████████████████████ ( 14.8%)
2025-09-26 ▏   48 ████████████████████████████ ( 15.4%)
2025-09-27 ▏   40 ███████████████████████ ( 12.9%)
2025-09-28 ▏   43 █████████████████████████ ( 13.8%)
2025-09-29 ▏   25 ██████████████ (  8.0%)
2025-09-30 ▏    9 █████ (  2.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!