# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-519-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--27-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 519                      |
| Total Reports: 2,425                 |
| Unique Sources: 817                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  597 ███████████████████████████████████ ( 24.7%)
         HTTP Bad User Agent ▏  568 █████████████████████████████████ ( 23.5%)
HTTP Admin Interface Probing ▏  262 ███████████████ ( 10.8%)
        HTTP Sensitive Files ▏  203 ███████████ (  8.4%)
         HTTP Wordpress Scan ▏  182 ██████████ (  7.5%)
       CVE-2017-9841 Exploit ▏  160 █████████ (  6.6%)
     HTTP Backdoors Attempts ▏  122 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  116 ██████ (  4.8%)
   CVE-2018-20062 (Thinkphp) ▏   74 ████ (  3.1%)
            HTTP CVE Probing ▏   73 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   24 █ (  1.0%)
                 Netgear RCE ▏   13 █ (  0.5%)
 HTTP Path Traversal Probing ▏   11 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.2%)
      CVE-2019-18935 Exploit ▏    5 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  663 ███████████████████████████████████ ( 30.8%)
United Kingdom ▏  494 ██████████████████████████ ( 22.9%)
       Ireland ▏  415 █████████████████████ ( 19.3%)
     Australia ▏  123 ██████ (  5.7%)
         Japan ▏  112 █████ (  5.2%)
   Netherlands ▏   99 █████ (  4.6%)
     Singapore ▏   85 ████ (  3.9%)
       Germany ▏   60 ███ (  2.8%)
         China ▏   55 ██ (  2.6%)
      Bulgaria ▏   47 ██ (  2.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-20 ▏   59 █████████████████████ ( 10.9%)
2025-07-21 ▏   93 ██████████████████████████████████ ( 17.2%)
2025-07-22 ▏   95 ███████████████████████████████████ ( 17.6%)
2025-07-23 ▏   84 ██████████████████████████████ ( 15.6%)
2025-07-24 ▏   60 ██████████████████████ ( 11.1%)
2025-07-25 ▏   76 ████████████████████████████ ( 14.1%)
2025-07-26 ▏   69 █████████████████████████ ( 12.8%)
2025-07-27 ▏    4 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!