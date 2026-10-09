# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-395-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--10--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 395                      |
| Total Reports: 21,269                |
| Unique Sources: 5,563                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6392 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3616 ███████████████████ ( 17.1%)
HTTP Admin Interface Probing ▏ 2632 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2463 █████████████ ( 11.7%)
         HTTP Wordpress Scan ▏ 1534 ████████ (  7.3%)
      HTTP Crawl Non Statics ▏ 1207 ██████ (  5.7%)
            HTTP CVE Probing ▏  878 ████ (  4.2%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.3%)
       CVE-2017-9841 Exploit ▏  671 ███ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  321 █ (  1.5%)
      CVE-2022-41082 Exploit ▏  250 █ (  1.2%)
                 Netgear RCE ▏  173 █ (  0.8%)
 HTTP Path Traversal Probing ▏  109 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏  102 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   65 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6951 ███████████████████████████████████ ( 41.4%)
United Kingdom ▏ 1887 █████████ ( 11.2%)
   Netherlands ▏ 1564 ███████ (  9.3%)
       Ireland ▏ 1282 ██████ (  7.6%)
        France ▏ 1212 ██████ (  7.2%)
     Singapore ▏  981 ████ (  5.8%)
        Canada ▏  789 ███ (  4.7%)
         Japan ▏  769 ███ (  4.6%)
       Germany ▏  745 ███ (  4.4%)
      Bulgaria ▏  598 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-10-02 ▏   43 █████████████████████████████ ( 16.5%)
2026-10-03 ▏   21 ██████████████ (  8.1%)
2026-10-04 ▏   48 ████████████████████████████████ ( 18.5%)
2026-10-05 ▏   26 █████████████████ ( 10.0%)
2026-10-06 ▏   39 ██████████████████████████ ( 15.0%)
2026-10-07 ▏   32 █████████████████████ ( 12.3%)
2026-10-08 ▏   51 ███████████████████████████████████ ( 19.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!