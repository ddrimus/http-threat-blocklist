# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-357-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--24-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 357                      |
| Total Reports: 22,977                |
| Unique Sources: 5,983                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6917 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3779 ███████████████████ ( 16.6%)
HTTP Admin Interface Probing ▏ 2861 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 2764 █████████████ ( 12.1%)
         HTTP Wordpress Scan ▏ 1555 ███████ (  6.8%)
      HTTP Crawl Non Statics ▏ 1316 ██████ (  5.8%)
            HTTP CVE Probing ▏  973 ████ (  4.3%)
       CVE-2017-9841 Exploit ▏  748 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  690 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏  382 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  274 █ (  1.2%)
                 Netgear RCE ▏  186 █ (  0.8%)
 HTTP Path Traversal Probing ▏  162 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  107 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   70 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7508 ███████████████████████████████████ ( 42.0%)
United Kingdom ▏ 1934 █████████ ( 10.8%)
   Netherlands ▏ 1628 ███████ (  9.1%)
        France ▏ 1288 ██████ (  7.2%)
       Ireland ▏ 1284 █████ (  7.2%)
     Singapore ▏ 1067 ████ (  6.0%)
        Canada ▏  820 ███ (  4.6%)
       Germany ▏  801 ███ (  4.5%)
         Japan ▏  790 ███ (  4.4%)
      Bulgaria ▏  760 ███ (  4.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-11-17 ▏   20 ██████████████ ( 10.3%)
2026-11-18 ▏   47 ███████████████████████████████████ ( 24.1%)
2026-11-19 ▏   37 ███████████████████████████ ( 19.0%)
2026-11-20 ▏   25 ██████████████████ ( 12.8%)
2026-11-21 ▏   21 ███████████████ ( 10.8%)
2026-11-22 ▏   25 ██████████████████ ( 12.8%)
2026-11-23 ▏   20 ██████████████ ( 10.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!