# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-319-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--04-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 319                      |
| Total Reports: 705                   |
| Unique Sources: 319                  |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  188 ███████████████████████████████████ ( 26.7%)
                HTTP Probing ▏  175 ████████████████████████████████ ( 24.9%)
HTTP Admin Interface Probing ▏   76 ██████████████ ( 10.8%)
        HTTP Sensitive Files ▏   55 ██████████ (  7.8%)
         HTTP Wordpress Scan ▏   44 ████████ (  6.2%)
       CVE-2017-9841 Exploit ▏   44 ████████ (  6.2%)
      HTTP Crawl Non Statics ▏   38 ███████ (  5.4%)
            HTTP CVE Probing ▏   21 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏   20 ███ (  2.8%)
     HTTP Backdoors Attempts ▏   20 ███ (  2.8%)
      CVE-2022-41082 Exploit ▏   11 ██ (  1.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.7%)
                 Netgear RCE ▏    4 █ (  0.6%)
 HTTP Path Traversal Probing ▏    2 █ (  0.3%)
      CVE-2023-49103 Exploit ▏    1 █ (  0.1%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  210 ███████████████████████████████████ ( 32.9%)
       Ireland ▏  148 ████████████████████████ ( 23.2%)
United Kingdom ▏  145 ████████████████████████ ( 22.7%)
     Singapore ▏   32 █████ (  5.0%)
   Netherlands ▏   25 ████ (  3.9%)
       Germany ▏   20 ███ (  3.1%)
         China ▏   19 ███ (  3.0%)
      Bulgaria ▏   16 ██ (  2.5%)
     Hong Kong ▏   12 ██ (  1.9%)
         Japan ▏   11 █ (  1.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-27 ▏   58 █████████████████████████ ( 12.4%)
2025-06-28 ▏   43 ██████████████████ (  9.2%)
2025-06-29 ▏   64 ████████████████████████████ ( 13.7%)
2025-06-30 ▏   80 ███████████████████████████████████ ( 17.2%)
2025-07-01 ▏   64 ████████████████████████████ ( 13.7%)
2025-07-02 ▏   76 █████████████████████████████████ ( 16.3%)
2025-07-03 ▏   78 ██████████████████████████████████ ( 16.7%)
2025-07-04 ▏    3 █ (  0.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!