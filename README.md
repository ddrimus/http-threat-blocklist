# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-239-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--01-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: LOW                          |
| Active IPs: 239                      |
| Total Reports: 492                   |
| Unique Sources: 239                  |
+--------------------------------------+
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  140 ███████████████████████████████████ ( 28.5%)
                HTTP Probing ▏  125 ███████████████████████████████ ( 25.4%)
HTTP Admin Interface Probing ▏   55 █████████████ ( 11.2%)
        HTTP Sensitive Files ▏   40 ██████████ (  8.1%)
         HTTP Wordpress Scan ▏   29 ███████ (  5.9%)
      HTTP Crawl Non Statics ▏   26 ██████ (  5.3%)
       CVE-2017-9841 Exploit ▏   25 ██████ (  5.1%)
   CVE-2018-20062 (Thinkphp) ▏   15 ███ (  3.0%)
            HTTP CVE Probing ▏   13 ███ (  2.6%)
     HTTP Backdoors Attempts ▏   11 ██ (  2.2%)
      CVE-2022-41082 Exploit ▏    6 █ (  1.2%)
                 Netgear RCE ▏    4 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏    2 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    1 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  150 ███████████████████████████████████ ( 33.0%)
United Kingdom ▏  109 █████████████████████████ ( 24.0%)
       Ireland ▏   92 █████████████████████ ( 20.3%)
     Singapore ▏   27 ██████ (  5.9%)
   Netherlands ▏   18 ████ (  4.0%)
       Germany ▏   16 ███ (  3.5%)
         China ▏   15 ███ (  3.3%)
          Iran ▏   11 ██ (  2.4%)
         Japan ▏    8 █ (  1.8%)
         India ▏    8 █ (  1.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-24 ▏   77 █████████████████████████████████ ( 16.9%)
2025-06-25 ▏   65 ████████████████████████████ ( 14.3%)
2025-06-26 ▏   55 ████████████████████████ ( 12.1%)
2025-06-27 ▏   64 ████████████████████████████ ( 14.0%)
2025-06-28 ▏   43 ██████████████████ (  9.4%)
2025-06-29 ▏   64 ████████████████████████████ ( 14.0%)
2025-06-30 ▏   80 ███████████████████████████████████ ( 17.5%)
2025-07-01 ▏    8 ███ (  1.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!