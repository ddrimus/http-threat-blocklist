# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-573-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--27-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 573                      |
| Total Reports: 4,233                 |
| Unique Sources: 1,253                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1057 ███████████████████████████████████ ( 25.1%)
         HTTP Bad User Agent ▏  945 ███████████████████████████████ ( 22.4%)
HTTP Admin Interface Probing ▏  463 ███████████████ ( 11.0%)
        HTTP Sensitive Files ▏  368 ████████████ (  8.7%)
         HTTP Wordpress Scan ▏  344 ███████████ (  8.2%)
       CVE-2017-9841 Exploit ▏  266 ████████ (  6.3%)
      HTTP Crawl Non Statics ▏  209 ██████ (  5.0%)
     HTTP Backdoors Attempts ▏  202 ██████ (  4.8%)
            HTTP CVE Probing ▏  136 ████ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  109 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏   35 █ (  0.8%)
 HTTP Path Traversal Probing ▏   29 █ (  0.7%)
                 Netgear RCE ▏   28 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   13 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1121 ███████████████████████████████████ ( 30.5%)
United Kingdom ▏  628 ███████████████████ ( 17.1%)
       Ireland ▏  562 █████████████████ ( 15.3%)
        France ▏  301 █████████ (  8.2%)
     Australia ▏  249 ███████ (  6.8%)
         Japan ▏  236 ███████ (  6.4%)
     Singapore ▏  207 ██████ (  5.6%)
   Netherlands ▏  128 ███ (  3.5%)
      Bulgaria ▏  128 ███ (  3.5%)
       Germany ▏  114 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-20 ▏   64 ████████████████████████ ( 13.4%)
2025-08-21 ▏   65 ████████████████████████ ( 13.6%)
2025-08-22 ▏   65 ████████████████████████ ( 13.6%)
2025-08-23 ▏   64 ████████████████████████ ( 13.4%)
2025-08-24 ▏   50 ███████████████████ ( 10.5%)
2025-08-25 ▏   72 ███████████████████████████ ( 15.1%)
2025-08-26 ▏   92 ███████████████████████████████████ ( 19.2%)
2025-08-27 ▏    6 ██ (  1.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!