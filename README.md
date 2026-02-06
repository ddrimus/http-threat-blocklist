# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-340-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--06-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 340                      |
| Total Reports: 11,388                |
| Unique Sources: 3,098                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3331 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2466 █████████████████████████ ( 21.7%)
HTTP Admin Interface Probing ▏ 1299 █████████████ ( 11.5%)
        HTTP Sensitive Files ▏ 1222 ████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  782 ████████ (  6.9%)
      HTTP Crawl Non Statics ▏  479 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  459 ████ (  4.0%)
       CVE-2017-9841 Exploit ▏  420 ████ (  3.7%)
            HTTP CVE Probing ▏  398 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  142 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  117 █ (  1.0%)
                 Netgear RCE ▏   93 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   40 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3498 ███████████████████████████████████ ( 35.8%)
United Kingdom ▏ 1741 █████████████████ ( 17.8%)
       Ireland ▏ 1045 ██████████ ( 10.7%)
   Netherlands ▏  730 ███████ (  7.5%)
         Japan ▏  570 █████ (  5.8%)
     Singapore ▏  562 █████ (  5.7%)
        France ▏  535 █████ (  5.5%)
       Germany ▏  388 ███ (  4.0%)
     Australia ▏  374 ███ (  3.8%)
         India ▏  334 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-01-30 ▏   33 ██████████████████████████ ( 14.5%)
2026-01-31 ▏   37 ██████████████████████████████ ( 16.3%)
2026-02-01 ▏   17 █████████████ (  7.5%)
2026-02-02 ▏   23 ██████████████████ ( 10.1%)
2026-02-03 ▏   43 ███████████████████████████████████ ( 18.9%)
2026-02-04 ▏   28 ██████████████████████ ( 12.3%)
2026-02-05 ▏   42 ██████████████████████████████████ ( 18.5%)
2026-02-06 ▏    4 ███ (  1.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!