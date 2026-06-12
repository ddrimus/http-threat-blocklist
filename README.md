# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-549-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--06--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 549                      |
| Total Reports: 17,365                |
| Unique Sources: 4,620                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5168 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 3165 █████████████████████ ( 18.3%)
HTTP Admin Interface Probing ▏ 2244 ███████████████ ( 13.0%)
        HTTP Sensitive Files ▏ 1801 ████████████ ( 10.4%)
         HTTP Wordpress Scan ▏ 1472 █████████ (  8.5%)
      HTTP Crawl Non Statics ▏  972 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  682 ████ (  4.0%)
            HTTP CVE Probing ▏  640 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  456 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏  193 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  136 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   73 █ (  0.4%)
 HTTP Path Traversal Probing ▏   62 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   54 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5653 ███████████████████████████████████ ( 39.9%)
United Kingdom ▏ 1800 ███████████ ( 12.7%)
       Ireland ▏ 1280 ███████ (  9.0%)
   Netherlands ▏ 1079 ██████ (  7.6%)
        France ▏  948 █████ (  6.7%)
     Singapore ▏  786 ████ (  5.5%)
        Canada ▏  747 ████ (  5.3%)
         Japan ▏  722 ████ (  5.1%)
       Germany ▏  632 ███ (  4.5%)
     Australia ▏  516 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-06-05 ▏   36 ██████████████ ( 11.2%)
2026-06-06 ▏   45 ██████████████████ ( 14.0%)
2026-06-07 ▏   41 ████████████████ ( 12.8%)
2026-06-08 ▏   40 ████████████████ ( 12.5%)
2026-06-09 ▏   33 █████████████ ( 10.3%)
2026-06-10 ▏   38 ███████████████ ( 11.8%)
2026-06-11 ▏   87 ███████████████████████████████████ ( 27.1%)
2026-06-12 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!