# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-515-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--04-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 515                      |
| Total Reports: 7,669                 |
| Unique Sources: 2,150                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2137 ███████████████████████████████████ ( 28.0%)
         HTTP Bad User Agent ▏ 1690 ███████████████████████████ ( 22.2%)
HTTP Admin Interface Probing ▏  840 █████████████ ( 11.0%)
        HTTP Sensitive Files ▏  808 █████████████ ( 10.6%)
         HTTP Wordpress Scan ▏  513 ████████ (  6.7%)
       CVE-2017-9841 Exploit ▏  349 █████ (  4.6%)
      HTTP Crawl Non Statics ▏  338 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  317 █████ (  4.2%)
            HTTP CVE Probing ▏  274 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  127 ██ (  1.7%)
      CVE-2022-41082 Exploit ▏   78 █ (  1.0%)
                 Netgear RCE ▏   63 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   25 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2273 ███████████████████████████████████ ( 34.4%)
United Kingdom ▏ 1256 ███████████████████ ( 19.0%)
       Ireland ▏  826 ████████████ ( 12.5%)
   Netherlands ▏  457 ███████ (  6.9%)
        France ▏  436 ██████ (  6.6%)
         Japan ▏  331 █████ (  5.0%)
     Singapore ▏  320 ████ (  4.8%)
     Australia ▏  278 ████ (  4.2%)
       Germany ▏  234 ███ (  3.5%)
         India ▏  201 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-28 ▏   52 ████████████████████████████ ( 13.2%)
2025-10-29 ▏   52 ████████████████████████████ ( 13.2%)
2025-10-30 ▏   54 █████████████████████████████ ( 13.7%)
2025-10-31 ▏   60 ████████████████████████████████ ( 15.2%)
2025-11-01 ▏   49 ██████████████████████████ ( 12.4%)
2025-11-02 ▏   60 ████████████████████████████████ ( 15.2%)
2025-11-03 ▏   65 ███████████████████████████████████ ( 16.5%)
2025-11-04 ▏    3 █ (  0.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!