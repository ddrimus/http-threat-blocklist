# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-61-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--25-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: LOW                          |
| Active IPs: 61                       |
| Total Reports: 116                   |
| Unique Sources: 61                   |
+--------------------------------------+
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏   32 ███████████████████████████████████ ( 27.6%)
         HTTP Bad User Agent ▏   32 ███████████████████████████████████ ( 27.6%)
HTTP Admin Interface Probing ▏   14 ███████████████ ( 12.1%)
        HTTP Sensitive Files ▏    9 █████████ (  7.8%)
         HTTP Wordpress Scan ▏    8 ████████ (  6.9%)
      HTTP Crawl Non Statics ▏    8 ████████ (  6.9%)
     HTTP Backdoors Attempts ▏    4 ████ (  3.4%)
            HTTP CVE Probing ▏    3 ███ (  2.6%)
                 Netgear RCE ▏    2 ██ (  1.7%)
   CVE-2018-20062 (Thinkphp) ▏    1 █ (  0.9%)
       CVE-2021-26086 (Jira) ▏    1 █ (  0.9%)
      CVE-2022-41082 Exploit ▏    1 █ (  0.9%)
       CVE-2017-9841 Exploit ▏    1 █ (  0.9%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

       Ireland ▏   36 ███████████████████████████████████ ( 31.6%)
 United States ▏   27 ██████████████████████████ ( 23.7%)
United Kingdom ▏   25 ████████████████████████ ( 21.9%)
   Netherlands ▏    8 ███████ (  7.0%)
     Singapore ▏    5 ████ (  4.4%)
         India ▏    4 ███ (  3.5%)
     Hong Kong ▏    3 ██ (  2.6%)
        France ▏    2 █ (  1.8%)
       Germany ▏    2 █ (  1.8%)
     Argentina ▏    2 █ (  1.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-23 ▏   29 ████████████ ( 25.0%)
2025-06-24 ▏   84 ███████████████████████████████████ ( 72.4%)
2025-06-25 ▏    3 █ (  2.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!