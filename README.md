# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-537-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--06--03-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 537                      |
| Total Reports: 16,928                |
| Unique Sources: 4,494                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5025 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 3105 █████████████████████ ( 18.4%)
HTTP Admin Interface Probing ▏ 2196 ███████████████ ( 13.0%)
        HTTP Sensitive Files ▏ 1707 ███████████ ( 10.1%)
         HTTP Wordpress Scan ▏ 1463 ██████████ (  8.7%)
      HTTP Crawl Non Statics ▏  938 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  682 ████ (  4.1%)
            HTTP CVE Probing ▏  619 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  455 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏  185 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.9%)
                 Netgear RCE ▏  132 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   68 █ (  0.4%)
 HTTP Path Traversal Probing ▏   61 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   52 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5454 ███████████████████████████████████ ( 39.4%)
United Kingdom ▏ 1794 ███████████ ( 13.0%)
       Ireland ▏ 1277 ████████ (  9.2%)
   Netherlands ▏ 1024 ██████ (  7.4%)
        France ▏  906 █████ (  6.5%)
     Singapore ▏  775 ████ (  5.6%)
        Canada ▏  747 ████ (  5.4%)
         Japan ▏  719 ████ (  5.2%)
       Germany ▏  627 ████ (  4.5%)
     Australia ▏  511 ███ (  3.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-27 ▏   63 █████████████████████████ ( 16.9%)
2026-05-28 ▏   49 ███████████████████ ( 13.1%)
2026-05-29 ▏   87 ███████████████████████████████████ ( 23.3%)
2026-05-30 ▏   55 ██████████████████████ ( 14.7%)
2026-05-31 ▏   42 ████████████████ ( 11.3%)
2026-06-01 ▏   42 ████████████████ ( 11.3%)
2026-06-02 ▏   35 ██████████████ (  9.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!