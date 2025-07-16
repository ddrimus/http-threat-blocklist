# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-441-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 441                      |
| Total Reports: 1,514                 |
| Unique Sources: 582                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  392 ███████████████████████████████████ ( 26.0%)
                HTTP Probing ▏  365 ████████████████████████████████ ( 24.2%)
HTTP Admin Interface Probing ▏  155 █████████████ ( 10.3%)
        HTTP Sensitive Files ▏  122 ██████████ (  8.1%)
         HTTP Wordpress Scan ▏  104 █████████ (  6.9%)
       CVE-2017-9841 Exploit ▏   98 ████████ (  6.5%)
      HTTP Crawl Non Statics ▏   71 ██████ (  4.7%)
     HTTP Backdoors Attempts ▏   66 █████ (  4.4%)
            HTTP CVE Probing ▏   49 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏   40 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏   17 █ (  1.1%)
                 Netgear RCE ▏   10 █ (  0.7%)
 HTTP Path Traversal Probing ▏    9 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  422 ███████████████████████████████████ ( 31.4%)
United Kingdom ▏  320 ██████████████████████████ ( 23.8%)
       Ireland ▏  297 ████████████████████████ ( 22.1%)
   Netherlands ▏   59 ████ (  4.4%)
         Japan ▏   54 ████ (  4.0%)
     Singapore ▏   52 ████ (  3.9%)
       Germany ▏   38 ███ (  2.8%)
      Bulgaria ▏   35 ██ (  2.6%)
         China ▏   33 ██ (  2.5%)
     Australia ▏   33 ██ (  2.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-09 ▏   55 ██████████████████ ( 11.0%)
2025-07-10 ▏   59 ███████████████████ ( 11.8%)
2025-07-11 ▏   72 ████████████████████████ ( 14.4%)
2025-07-12 ▏   63 █████████████████████ ( 12.6%)
2025-07-13 ▏   93 ███████████████████████████████ ( 18.6%)
2025-07-14 ▏   53 █████████████████ ( 10.6%)
2025-07-15 ▏  104 ███████████████████████████████████ ( 20.8%)
2025-07-16 ▏    2 █ (  0.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!