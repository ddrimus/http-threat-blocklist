# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-293-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--03-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 293                      |
| Total Reports: 630                   |
| Unique Sources: 293                  |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  172 ███████████████████████████████████ ( 27.3%)
                HTTP Probing ▏  157 ███████████████████████████████ ( 24.9%)
HTTP Admin Interface Probing ▏   68 █████████████ ( 10.8%)
        HTTP Sensitive Files ▏   50 ██████████ (  7.9%)
         HTTP Wordpress Scan ▏   40 ████████ (  6.3%)
       CVE-2017-9841 Exploit ▏   36 ███████ (  5.7%)
      HTTP Crawl Non Statics ▏   35 ███████ (  5.6%)
     HTTP Backdoors Attempts ▏   19 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏   18 ███ (  2.9%)
            HTTP CVE Probing ▏   17 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏    9 █ (  1.4%)
                 Netgear RCE ▏    4 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    3 █ (  0.5%)
      CVE-2023-49103 Exploit ▏    1 █ (  0.2%)
      CVE-2019-18935 Exploit ▏    1 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  187 ███████████████████████████████████ ( 32.6%)
       Ireland ▏  137 █████████████████████████ ( 23.9%)
United Kingdom ▏  128 ███████████████████████ ( 22.3%)
     Singapore ▏   29 █████ (  5.1%)
   Netherlands ▏   22 ████ (  3.8%)
       Germany ▏   20 ███ (  3.5%)
         China ▏   16 ██ (  2.8%)
     Hong Kong ▏   12 ██ (  2.1%)
          Iran ▏   11 ██ (  1.9%)
         India ▏   11 ██ (  1.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-26 ▏   53 ███████████████████████ ( 11.8%)
2025-06-27 ▏   64 ████████████████████████████ ( 14.2%)
2025-06-28 ▏   43 ██████████████████ (  9.6%)
2025-06-29 ▏   64 ████████████████████████████ ( 14.2%)
2025-06-30 ▏   80 ███████████████████████████████████ ( 17.8%)
2025-07-01 ▏   64 ████████████████████████████ ( 14.2%)
2025-07-02 ▏   76 █████████████████████████████████ ( 16.9%)
2025-07-03 ▏    6 ██ (  1.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!