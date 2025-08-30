# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-589-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--30-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 589                      |
| Total Reports: 4,385                 |
| Unique Sources: 1,304                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1105 ███████████████████████████████████ ( 25.3%)
         HTTP Bad User Agent ▏  991 ███████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  474 ███████████████ ( 10.8%)
        HTTP Sensitive Files ▏  381 ████████████ (  8.7%)
         HTTP Wordpress Scan ▏  353 ███████████ (  8.1%)
       CVE-2017-9841 Exploit ▏  268 ████████ (  6.1%)
      HTTP Crawl Non Statics ▏  213 ██████ (  4.9%)
     HTTP Backdoors Attempts ▏  209 ██████ (  4.8%)
            HTTP CVE Probing ▏  144 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏  111 ███ (  2.5%)
      CVE-2022-41082 Exploit ▏   37 █ (  0.8%)
 HTTP Path Traversal Probing ▏   29 █ (  0.7%)
                 Netgear RCE ▏   28 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   13 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1175 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  654 ███████████████████ ( 17.2%)
       Ireland ▏  574 █████████████████ ( 15.1%)
        France ▏  301 ████████ (  7.9%)
     Australia ▏  249 ███████ (  6.6%)
         Japan ▏  236 ███████ (  6.2%)
     Singapore ▏  213 ██████ (  5.6%)
      Bulgaria ▏  136 ████ (  3.6%)
       Germany ▏  132 ███ (  3.5%)
   Netherlands ▏  131 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-23 ▏   55 ████████████████████ ( 12.9%)
2025-08-24 ▏   50 ███████████████████ ( 11.7%)
2025-08-25 ▏   72 ███████████████████████████ ( 16.9%)
2025-08-26 ▏   92 ███████████████████████████████████ ( 21.5%)
2025-08-27 ▏   50 ███████████████████ ( 11.7%)
2025-08-28 ▏   45 █████████████████ ( 10.5%)
2025-08-29 ▏   59 ██████████████████████ ( 13.8%)
2025-08-30 ▏    4 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!