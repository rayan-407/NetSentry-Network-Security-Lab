# NetSentry Network Security Assessment Report

## Executive Summary

A network security assessment was conducted against an authorized Windows virtual machine in a VMware lab environment.

The assessment focused on identifying network exposure and visible TCP services.

## Target

- IP Address: 192.168.16.129
- Environment: VMware Authorized Lab
- Operating System: Windows

## Tools Used

- Nmap
- Kali Linux
- VMware Workstation

## Findings

### Finding 1: Open TCP Service

**Port:** 5357/TCP

**Service:** WSDAPI

**Risk Level:** Informational

The service was identified during TCP port scanning.

The organization should verify whether this service is required.

## Recommendations

1. Disable unnecessary services.
2. Restrict unnecessary inbound connections.
3. Configure Windows Firewall appropriately.
4. Apply security updates regularly.
5. Monitor exposed services.
6. Use network segmentation where appropriate.

## Conclusion

The assessment successfully identified accessible network services on the authorized target.

This project demonstrates:

- Network reconnaissance
- Port scanning
- Evidence collection
- Security analysis
- Professional reporting

