# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-96-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--26-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: LOW                          |
| Active IPs: 96                       |
| Total Reports: 180                   |
| Unique Sources: 96                   |
+--------------------------------------+
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏   52 ███████████████████████████████████ ( 28.9%)
         HTTP Bad User Agent ▏   49 ████████████████████████████████ ( 27.2%)
HTTP Admin Interface Probing ▏   20 █████████████ ( 11.1%)
        HTTP Sensitive Files ▏   13 ████████ (  7.2%)
         HTTP Wordpress Scan ▏   12 ████████ (  6.7%)
      HTTP Crawl Non Statics ▏   12 ████████ (  6.7%)
     HTTP Backdoors Attempts ▏    6 ████ (  3.3%)
            HTTP CVE Probing ▏    4 ██ (  2.2%)
   CVE-2018-20062 (Thinkphp) ▏    3 ██ (  1.7%)
       CVE-2017-9841 Exploit ▏    3 ██ (  1.7%)
                 Netgear RCE ▏    2 █ (  1.1%)
       CVE-2021-26086 (Jira) ▏    2 █ (  1.1%)
      CVE-2022-41082 Exploit ▏    2 █ (  1.1%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

       Ireland ▏   53 ███████████████████████████████████ ( 31.9%)
 United States ▏   43 ████████████████████████████ ( 25.9%)
United Kingdom ▏   34 ██████████████████████ ( 20.5%)
   Netherlands ▏   10 ██████ (  6.0%)
     Singapore ▏    7 ████ (  4.2%)
       Germany ▏    6 ███ (  3.6%)
         India ▏    4 ██ (  2.4%)
   South Korea ▏    3 █ (  1.8%)
          Iran ▏    3 █ (  1.8%)
     Hong Kong ▏    3 █ (  1.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-23 ▏   29 ████████████ ( 16.1%)
2025-06-24 ▏   84 ███████████████████████████████████ ( 46.7%)
2025-06-25 ▏   65 ███████████████████████████ ( 36.1%)
2025-06-26 ▏    2 █ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!