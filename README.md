# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-569-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--11-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 569                      |
| Total Reports: 8,125                 |
| Unique Sources: 2,269                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2300 ███████████████████████████████████ ( 28.5%)
         HTTP Bad User Agent ▏ 1782 ███████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  885 █████████████ ( 11.0%)
        HTTP Sensitive Files ▏  872 █████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  538 ████████ (  6.7%)
       CVE-2017-9841 Exploit ▏  354 █████ (  4.4%)
      HTTP Crawl Non Statics ▏  352 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  337 █████ (  4.2%)
            HTTP CVE Probing ▏  287 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  128 █ (  1.6%)
      CVE-2022-41082 Exploit ▏   82 █ (  1.0%)
                 Netgear RCE ▏   67 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   29 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   28 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2408 ███████████████████████████████████ ( 34.3%)
United Kingdom ▏ 1337 ███████████████████ ( 19.1%)
       Ireland ▏  855 ████████████ ( 12.2%)
   Netherlands ▏  510 ███████ (  7.3%)
        France ▏  440 ██████ (  6.3%)
         Japan ▏  391 █████ (  5.6%)
     Singapore ▏  326 ████ (  4.6%)
     Australia ▏  278 ████ (  4.0%)
       Germany ▏  249 ███ (  3.6%)
         India ▏  218 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-04 ▏   58 ██████████████████████ ( 12.7%)
2025-11-05 ▏   62 ████████████████████████ ( 13.6%)
2025-11-06 ▏   45 █████████████████ (  9.9%)
2025-11-07 ▏   68 ██████████████████████████ ( 14.9%)
2025-11-08 ▏   89 ███████████████████████████████████ ( 19.5%)
2025-11-09 ▏   65 █████████████████████████ ( 14.3%)
2025-11-10 ▏   63 ████████████████████████ ( 13.8%)
2025-11-11 ▏    6 ██ (  1.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!