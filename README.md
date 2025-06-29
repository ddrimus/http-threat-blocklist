# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-175-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--29-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: LOW                          |
| Active IPs: 175                      |
| Total Reports: 341                   |
| Unique Sources: 175                  |
+--------------------------------------+
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  100 ███████████████████████████████████ ( 29.3%)
                HTTP Probing ▏   88 ██████████████████████████████ ( 25.8%)
HTTP Admin Interface Probing ▏   37 ████████████ ( 10.9%)
         HTTP Wordpress Scan ▏   22 ███████ (  6.5%)
        HTTP Sensitive Files ▏   21 ███████ (  6.2%)
      HTTP Crawl Non Statics ▏   18 ██████ (  5.3%)
       CVE-2017-9841 Exploit ▏   16 █████ (  4.7%)
            HTTP CVE Probing ▏   10 ███ (  2.9%)
     HTTP Backdoors Attempts ▏   10 ███ (  2.9%)
   CVE-2018-20062 (Thinkphp) ▏    8 ██ (  2.3%)
                 Netgear RCE ▏    4 █ (  1.2%)
      CVE-2022-41082 Exploit ▏    4 █ (  1.2%)
       CVE-2021-26086 (Jira) ▏    2 █ (  0.6%)
      CVE-2019-18935 Exploit ▏    1 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  110 ███████████████████████████████████ ( 35.1%)
       Ireland ▏   83 ██████████████████████████ ( 26.5%)
United Kingdom ▏   52 ████████████████ ( 16.6%)
     Singapore ▏   19 ██████ (  6.1%)
   Netherlands ▏   12 ███ (  3.8%)
       Germany ▏   10 ███ (  3.2%)
         China ▏    9 ██ (  2.9%)
          Iran ▏    6 █ (  1.9%)
         India ▏    6 █ (  1.9%)
      Bulgaria ▏    6 █ (  1.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-23 ▏   29 ████████████ (  8.5%)
2025-06-24 ▏   84 ███████████████████████████████████ ( 24.6%)
2025-06-25 ▏   65 ███████████████████████████ ( 19.1%)
2025-06-26 ▏   55 ██████████████████████ ( 16.1%)
2025-06-27 ▏   64 ██████████████████████████ ( 18.8%)
2025-06-28 ▏   43 █████████████████ ( 12.6%)
2025-06-29 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!