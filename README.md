# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-282-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--08--03-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 282                      |
| Total Reports: 18,791                |
| Unique Sources: 4,949                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5639 ███████████████████████████████████ ( 30.2%)
         HTTP Bad User Agent ▏ 3386 █████████████████████ ( 18.1%)
HTTP Admin Interface Probing ▏ 2370 ██████████████ ( 12.7%)
        HTTP Sensitive Files ▏ 2076 ████████████ ( 11.1%)
         HTTP Wordpress Scan ▏ 1515 █████████ (  8.1%)
      HTTP Crawl Non Statics ▏ 1055 ██████ (  5.7%)
            HTTP CVE Probing ▏  722 ████ (  3.9%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  474 ██ (  2.5%)
      CVE-2022-41082 Exploit ▏  219 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  156 █ (  0.8%)
                 Netgear RCE ▏  152 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   90 █ (  0.5%)
 HTTP Path Traversal Probing ▏   70 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   60 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6219 ███████████████████████████████████ ( 40.6%)
United Kingdom ▏ 1831 ██████████ ( 12.0%)
   Netherlands ▏ 1365 ███████ (  8.9%)
       Ireland ▏ 1281 ███████ (  8.4%)
        France ▏ 1129 ██████ (  7.4%)
     Singapore ▏  809 ████ (  5.3%)
        Canada ▏  773 ████ (  5.0%)
         Japan ▏  731 ████ (  4.8%)
       Germany ▏  656 ███ (  4.3%)
     Australia ▏  516 ██ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-07-27 ▏   15 ██████ (  5.4%)
2026-07-28 ▏   34 █████████████ ( 12.3%)
2026-07-29 ▏   34 █████████████ ( 12.3%)
2026-07-30 ▏   26 ██████████ (  9.4%)
2026-07-31 ▏   41 ████████████████ ( 14.9%)
2026-08-01 ▏   40 ████████████████ ( 14.5%)
2026-08-02 ▏   86 ███████████████████████████████████ ( 31.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!