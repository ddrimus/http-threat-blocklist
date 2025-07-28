# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-527-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--28-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 527                      |
| Total Reports: 2,485                 |
| Unique Sources: 839                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  612 ███████████████████████████████████ ( 24.7%)
         HTTP Bad User Agent ▏  587 █████████████████████████████████ ( 23.7%)
HTTP Admin Interface Probing ▏  266 ███████████████ ( 10.7%)
        HTTP Sensitive Files ▏  204 ███████████ (  8.2%)
         HTTP Wordpress Scan ▏  186 ██████████ (  7.5%)
       CVE-2017-9841 Exploit ▏  163 █████████ (  6.6%)
     HTTP Backdoors Attempts ▏  125 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  117 ██████ (  4.7%)
   CVE-2018-20062 (Thinkphp) ▏   77 ████ (  3.1%)
            HTTP CVE Probing ▏   76 ████ (  3.1%)
      CVE-2022-41082 Exploit ▏   25 █ (  1.0%)
                 Netgear RCE ▏   14 █ (  0.6%)
 HTTP Path Traversal Probing ▏   11 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏    7 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    5 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  690 ███████████████████████████████████ ( 31.2%)
United Kingdom ▏  495 █████████████████████████ ( 22.4%)
       Ireland ▏  423 █████████████████████ ( 19.1%)
     Australia ▏  126 ██████ (  5.7%)
         Japan ▏  123 ██████ (  5.6%)
   Netherlands ▏   99 █████ (  4.5%)
     Singapore ▏   89 ████ (  4.0%)
       Germany ▏   64 ███ (  2.9%)
         China ▏   57 ██ (  2.6%)
      Bulgaria ▏   47 ██ (  2.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-21 ▏   87 ████████████████████████████████ ( 16.3%)
2025-07-22 ▏   95 ███████████████████████████████████ ( 17.8%)
2025-07-23 ▏   84 ██████████████████████████████ ( 15.7%)
2025-07-24 ▏   60 ██████████████████████ ( 11.2%)
2025-07-25 ▏   76 ████████████████████████████ ( 14.2%)
2025-07-26 ▏   69 █████████████████████████ ( 12.9%)
2025-07-27 ▏   61 ██████████████████████ ( 11.4%)
2025-07-28 ▏    3 █ (  0.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!