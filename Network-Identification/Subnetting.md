# Subnetting

## Objective

Identify the subnet mask of the current network and understand the importance of subnetting.

---

## Command Used

```bash
ifconfig
```

---

## Sample Output

```text
inet 10.0.2.15
netmask 255.255.255.0
broadcast 10.0.2.255
```

---

## Explanation

The `ifconfig` command displays detailed network configuration information, including the assigned IP address, subnet mask, broadcast address, and interface status.

In this lab, the subnet mask is:

```text
255.255.255.0
```

This subnet divides the network into smaller logical segments, allowing efficient communication between devices.

---

## What is Subnetting?

Subnetting is the process of dividing a large network into smaller, manageable subnetworks (subnets).

Instead of allowing every device to communicate across one large network, subnetting creates separate network segments that improve efficiency and security.

---

## Why Subnetting is Important

- Reduces broadcast traffic.
- Improves network performance.
- Isolates sensitive departments or devices.
- Simplifies network management.
- Enhances overall network security.

---

## Cybersecurity Relevance

Subnetting is widely used to:

- Separate internal and external networks.
- Isolate servers from user workstations.
- Create secure VLANs.
- Limit lateral movement during cyber attacks.
- Reduce the attack surface.

Understanding subnetting is essential for SOC Analysts, Network Security Engineers, and Penetration Testers.

## Conclusion

Subnetting improves network efficiency, organization, and security by dividing large networks into smaller logical segments that are easier to manage and protect.
