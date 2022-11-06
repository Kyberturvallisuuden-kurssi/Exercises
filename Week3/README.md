Introduction to Practical Cyber Security Testing - Week 3: Networking environment
====


## About the lab

Topic: Wireshark, IPS, Firewalls, nmap, honey pots, shodan, Wi-Fi, virtualisation, cloud

TODO: add descriptory text about the lab and this week's topic


## Prerequisites

<details><summary>Details</summary>

* TODO: describe required knowledge to complete this week's tasks

</details>


## System Requirements

<details><summary>Details</summary>

* TODO: what tools or features are required to complete this week's tasks

</details>


## Grading

<details><summary>Details</summary>

This course uses GitHub Classroom with Autograding, meaning that your assignments are automatically graded! To find out your score, check the results of github actions after pushing your answers. No cheating!

Task #|Grade/Level|Description|
-----|:---:|-----------|
Task 1 | 1 | TODO: brief task descriptions and what each grade requires

</details>

---


## Task 1

### Analyze traffic with Wireshark and tell about destination of one packet

What was the destination of the packet?

```

```

---

## Task 2

### Install a Wifi Scanner to your computer

What was the MAC address of the Wifi?

```

```

---

## Task 3

### Create a honeypot with OWASP Honeypot

```

```

---

## Task 4

### Try pfSense firewall in a virtual machine

1.Install Linux virtual machine, e.g. Debian 11

The tutorial is based on the use of Oracle VirtualBox

Download ISO image from https://www.debian.org/download

Create a new virtual machine (Debian (64-bit), base memory: 4G, storage: 20G) and attach the Debian ISO image as an installation media.

During the installation, choose the SSH and web servers to be installed.

Check the functioning of the installation by rebooting and logging to Debian, and that the Debian web browser has access to Internet.

Check that the Debian web server and the SSH server are working.

Power off the virtual machine.

Configure from the virtual machine network settings the internal network for Adapter1.

2.Install pfSense in another virtual machine
https://www.pfsense.org/download/

Choose AMD64, DVD Image
Extract from gz-packet ISO image (e.g. gzip -d )

Create a new virtual machine for pfSense (FreeBSD 64-bit, base memory: 4G, storage: 10G)

Attach pfSense ISO image to virtual machine.

Virtual machine network settings:
Adapter1: Bridged network
Adapter2: Internal network (intnet)

Install pfSense
Configure WAN: em0 and LAN: em1

LAN address e.g. 192.168.2.1 (24 bit)

Start Debian 11 virtual machine and check the access to the pfSense control interface. The username is admin and password pfsense.

3. Configure the following firewall rules

Allow the access to Internet addressess from Debian

Interfaces -> WAN interface: delete tge Block private networks setting

Allow the access to Debian's SSH and web servers via VAN.

Return a configuration file as an answer.
```

```


## Task 5

Search servers located in Oulu with shodan and return one IP address and hostname.

It requires a login to use filters.
```

```

---

## Task 6

### A) TODO
```

```

### B) TODO
```

```

---

## Task 7

### A) TODO
```

```

### B) TODO
```

```

---

## Task 8

### A) TODO
```

```

### B) TODO
```

```
