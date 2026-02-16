# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-341-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 341                      |
| Total Reports: 11,765                |
| Unique Sources: 3,188                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3445 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2504 █████████████████████████ ( 21.4%)
HTTP Admin Interface Probing ▏ 1357 █████████████ ( 11.6%)
        HTTP Sensitive Files ▏ 1240 ████████████ ( 10.6%)
         HTTP Wordpress Scan ▏  843 ████████ (  7.2%)
      HTTP Crawl Non Statics ▏  504 █████ (  4.3%)
     HTTP Backdoors Attempts ▏  489 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  427 ████ (  3.6%)
            HTTP CVE Probing ▏  413 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  123 █ (  1.0%)
                 Netgear RCE ▏   95 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   42 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3636 ███████████████████████████████████ ( 36.1%)
United Kingdom ▏ 1752 ████████████████ ( 17.4%)
       Ireland ▏ 1074 ██████████ ( 10.7%)
   Netherlands ▏  748 ███████ (  7.4%)
     Singapore ▏  583 █████ (  5.8%)
        France ▏  578 █████ (  5.7%)
         Japan ▏  576 █████ (  5.7%)
       Germany ▏  395 ███ (  3.9%)
     Australia ▏  379 ███ (  3.8%)
         India ▏  343 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-02-09 ▏   39 ██████████████████████ ( 13.4%)
2026-02-10 ▏   61 ███████████████████████████████████ ( 21.0%)
2026-02-11 ▏   43 ████████████████████████ ( 14.8%)
2026-02-12 ▏   60 ██████████████████████████████████ ( 20.6%)
2026-02-13 ▏   39 ██████████████████████ ( 13.4%)
2026-02-14 ▏   35 ████████████████████ ( 12.0%)
2026-02-15 ▏   12 ██████ (  4.1%)
2026-02-16 ▏    2 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!