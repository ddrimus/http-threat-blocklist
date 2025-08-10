# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-579-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--10-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 579                      |
| Total Reports: 3,311                 |
| Unique Sources: 1,049                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  817 ███████████████████████████████████ ( 24.8%)
         HTTP Bad User Agent ▏  752 ████████████████████████████████ ( 22.8%)
HTTP Admin Interface Probing ▏  349 ██████████████ ( 10.6%)
         HTTP Wordpress Scan ▏  278 ███████████ (  8.4%)
        HTTP Sensitive Files ▏  256 ██████████ (  7.8%)
       CVE-2017-9841 Exploit ▏  223 █████████ (  6.8%)
     HTTP Backdoors Attempts ▏  177 ███████ (  5.4%)
      HTTP Crawl Non Statics ▏  151 ██████ (  4.6%)
   CVE-2018-20062 (Thinkphp) ▏  104 ████ (  3.2%)
            HTTP CVE Probing ▏  102 ████ (  3.1%)
      CVE-2022-41082 Exploit ▏   28 █ (  0.8%)
                 Netgear RCE ▏   22 █ (  0.7%)
 HTTP Path Traversal Probing ▏   21 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    8 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  891 ███████████████████████████████████ ( 30.8%)
United Kingdom ▏  565 ██████████████████████ ( 19.5%)
       Ireland ▏  503 ███████████████████ ( 17.4%)
         Japan ▏  207 ████████ (  7.1%)
     Australia ▏  198 ███████ (  6.8%)
     Singapore ▏  156 ██████ (  5.4%)
   Netherlands ▏  114 ████ (  3.9%)
        France ▏   91 ███ (  3.1%)
       Germany ▏   87 ███ (  3.0%)
         China ▏   84 ███ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-03 ▏   81 ████████████████████████████████ ( 15.7%)
2025-08-04 ▏   79 ███████████████████████████████ ( 15.3%)
2025-08-05 ▏   77 ██████████████████████████████ ( 14.9%)
2025-08-06 ▏   88 ███████████████████████████████████ ( 17.0%)
2025-08-07 ▏   65 █████████████████████████ ( 12.6%)
2025-08-08 ▏   56 ██████████████████████ ( 10.8%)
2025-08-09 ▏   60 ███████████████████████ ( 11.6%)
2025-08-10 ▏   11 ████ (  2.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!