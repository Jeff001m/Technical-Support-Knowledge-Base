# Network Troubleshooting Guide

## No Internet Connection

### Symptoms
- Unable to browse websites
- Network icon shows "No Internet"

### Troubleshooting Steps
1. Verify physical cable or Wi-Fi connection.
2. Restart the router and computer.
3. Run:
```
ipconfig /release
ipconfig /renew
ipconfig /flushdns
```
4. Test connectivity using:
```
ping 8.8.8.8
ping google.com
```
5. Check DNS configuration.
6. Confirm DHCP is assigning an IP address.

---

## DNS Issues

### Symptoms
- Websites fail to load by name.
- Ping works using IP addresses only.

### Resolution
- Flush DNS cache.
- Change DNS to Google DNS (8.8.8.8 / 8.8.4.4).
- Restart the DNS Client service.

---

## Common Tools

- ipconfig
- ping
- tracert
- nslookup
- netstat
