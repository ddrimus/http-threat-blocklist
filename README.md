# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-391-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--10--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 391                      |
| Total Reports: 21,426                |
| Unique Sources: 5,605                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6435 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3632 ███████████████████ ( 17.1%)
HTTP Admin Interface Probing ▏ 2654 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2481 █████████████ ( 11.7%)
         HTTP Wordpress Scan ▏ 1535 ████████ (  7.2%)
      HTTP Crawl Non Statics ▏ 1220 ██████ (  5.7%)
            HTTP CVE Probing ▏  885 ████ (  4.2%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.2%)
       CVE-2017-9841 Exploit ▏  686 ███ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  335 █ (  1.6%)
      CVE-2022-41082 Exploit ▏  253 █ (  1.2%)
                 Netgear RCE ▏  174 █ (  0.8%)
 HTTP Path Traversal Probing ▏  111 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏  102 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   67 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6990 ███████████████████████████████████ ( 41.4%)
United Kingdom ▏ 1887 █████████ ( 11.2%)
   Netherlands ▏ 1568 ███████ (  9.3%)
       Ireland ▏ 1282 ██████ (  7.6%)
        France ▏ 1222 ██████ (  7.2%)
     Singapore ▏ 1003 █████ (  5.9%)
        Canada ▏  795 ███ (  4.7%)
         Japan ▏  773 ███ (  4.6%)
       Germany ▏  751 ███ (  4.4%)
      Bulgaria ▏  610 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-10-07 ▏   29 ███████████████████ ( 12.2%)
2026-10-08 ▏   51 ███████████████████████████████████ ( 21.5%)
2026-10-09 ▏   21 ██████████████ (  8.9%)
2026-10-10 ▏   40 ███████████████████████████ ( 16.9%)
2026-10-11 ▏   33 ██████████████████████ ( 13.9%)
2026-10-12 ▏   31 █████████████████████ ( 13.1%)
2026-10-13 ▏   31 █████████████████████ ( 13.1%)
2026-10-14 ▏    1 █ (  0.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!