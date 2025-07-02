# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-270-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--02-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 270                      |
| Total Reports: 558                   |
| Unique Sources: 270                  |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  159 ███████████████████████████████████ ( 28.5%)
                HTTP Probing ▏  140 ██████████████████████████████ ( 25.1%)
HTTP Admin Interface Probing ▏   59 ████████████ ( 10.6%)
        HTTP Sensitive Files ▏   46 ██████████ (  8.2%)
         HTTP Wordpress Scan ▏   34 ███████ (  6.1%)
      HTTP Crawl Non Statics ▏   30 ██████ (  5.4%)
       CVE-2017-9841 Exploit ▏   27 █████ (  4.8%)
   CVE-2018-20062 (Thinkphp) ▏   16 ███ (  2.9%)
            HTTP CVE Probing ▏   16 ███ (  2.9%)
     HTTP Backdoors Attempts ▏   15 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏    9 █ (  1.6%)
                 Netgear RCE ▏    4 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏    2 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    1 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  170 ███████████████████████████████████ ( 33.0%)
United Kingdom ▏  121 ████████████████████████ ( 23.5%)
       Ireland ▏  115 ███████████████████████ ( 22.3%)
     Singapore ▏   29 █████ (  5.6%)
   Netherlands ▏   20 ████ (  3.9%)
       Germany ▏   17 ███ (  3.3%)
         China ▏   16 ███ (  3.1%)
          Iran ▏   11 ██ (  2.1%)
         Japan ▏    8 █ (  1.6%)
         India ▏    8 █ (  1.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-25 ▏   62 ███████████████████████████ ( 14.0%)
2025-06-26 ▏   55 ████████████████████████ ( 12.4%)
2025-06-27 ▏   64 ████████████████████████████ ( 14.5%)
2025-06-28 ▏   43 ██████████████████ (  9.7%)
2025-06-29 ▏   64 ████████████████████████████ ( 14.5%)
2025-06-30 ▏   80 ███████████████████████████████████ ( 18.1%)
2025-07-01 ▏   64 ████████████████████████████ ( 14.5%)
2025-07-02 ▏   10 ████ (  2.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!