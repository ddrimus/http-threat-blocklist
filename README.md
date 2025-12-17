# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-469-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--17-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 469                      |
| Total Reports: 9,683                 |
| Unique Sources: 2,670                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2824 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏ 2132 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1082 █████████████ ( 11.2%)
HTTP Admin Interface Probing ▏ 1042 ████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  612 ███████ (  6.4%)
      HTTP Crawl Non Statics ▏  402 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  392 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  384 ████ (  4.0%)
            HTTP CVE Probing ▏  338 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  138 █ (  1.4%)
      CVE-2022-41082 Exploit ▏   97 █ (  1.0%)
                 Netgear RCE ▏   77 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   40 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   35 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2938 ███████████████████████████████████ ( 35.3%)
United Kingdom ▏ 1573 ██████████████████ ( 18.9%)
       Ireland ▏  943 ███████████ ( 11.3%)
   Netherlands ▏  634 ███████ (  7.6%)
         Japan ▏  468 █████ (  5.6%)
        France ▏  466 █████ (  5.6%)
     Singapore ▏  416 ████ (  5.0%)
     Australia ▏  312 ███ (  3.7%)
       Germany ▏  302 ███ (  3.6%)
      Bulgaria ▏  269 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-10 ▏   35 ███████████████████████████ ( 14.1%)
2025-12-11 ▏   39 ██████████████████████████████ ( 15.7%)
2025-12-12 ▏   27 █████████████████████ ( 10.8%)
2025-12-13 ▏   34 ██████████████████████████ ( 13.7%)
2025-12-14 ▏   27 █████████████████████ ( 10.8%)
2025-12-15 ▏   45 ███████████████████████████████████ ( 18.1%)
2025-12-16 ▏   41 ███████████████████████████████ ( 16.5%)
2025-12-17 ▏    1 █ (  0.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!