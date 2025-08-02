# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-554-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--02-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 554                      |
| Total Reports: 2,793                 |
| Unique Sources: 927                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  697 ███████████████████████████████████ ( 25.1%)
         HTTP Bad User Agent ▏  640 ████████████████████████████████ ( 23.0%)
HTTP Admin Interface Probing ▏  302 ███████████████ ( 10.9%)
        HTTP Sensitive Files ▏  225 ███████████ (  8.1%)
         HTTP Wordpress Scan ▏  224 ███████████ (  8.1%)
       CVE-2017-9841 Exploit ▏  181 █████████ (  6.5%)
     HTTP Backdoors Attempts ▏  141 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  130 ██████ (  4.7%)
   CVE-2018-20062 (Thinkphp) ▏   86 ████ (  3.1%)
            HTTP CVE Probing ▏   82 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   26 █ (  0.9%)
                 Netgear RCE ▏   15 █ (  0.5%)
 HTTP Path Traversal Probing ▏   15 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    7 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  761 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  519 ███████████████████████ ( 21.1%)
       Ireland ▏  446 ████████████████████ ( 18.1%)
         Japan ▏  169 ███████ (  6.9%)
     Australia ▏  140 ██████ (  5.7%)
     Singapore ▏  129 █████ (  5.2%)
   Netherlands ▏  108 ████ (  4.4%)
       Germany ▏   75 ███ (  3.0%)
         China ▏   66 ███ (  2.7%)
        France ▏   48 ██ (  2.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-26 ▏   61 ██████████████████████ ( 14.1%)
2025-07-27 ▏   61 ██████████████████████ ( 14.1%)
2025-07-28 ▏   65 ████████████████████████ ( 15.0%)
2025-07-29 ▏   48 █████████████████ ( 11.1%)
2025-07-30 ▏   12 ████ (  2.8%)
2025-07-31 ▏   80 █████████████████████████████ ( 18.5%)
2025-08-01 ▏   94 ███████████████████████████████████ ( 21.7%)
2025-08-02 ▏   12 ████ (  2.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!