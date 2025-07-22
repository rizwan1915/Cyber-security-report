# Wireshark Traffic Analysis Summary

**Capture Date:** July 21, 2025  
**Analyst:** Rizwan Khurram

## Observations

- Multiple DNS queries to `siuu.com` from 192.168.1.5
- Suspicious ARP replies indicating possible ARP spoofing
- TCP SYN floods observed on port 80 from 192.168.1.100

## Recommendations

- Investigate the source of TCP floods (DDoS attempt)
- Implement static ARP entries to mitigate spoofing
- Monitor DNS logs for unusual spikes
