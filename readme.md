# Introduction
I've been using [PiHole](https://github.com/pi-hole/pi-hole) for many years both on a Raspberry Pi and more recently a virtual machine. I have also recently switched to using pfBlockerNG on pfSense, since it allows me to run everything required for internet (E.g. DHCP, DNS_ access on one device. Over time I've seen DNS blocklists come and go, become outdated, or disappear completely. I have decided to put together a list of my recommended blocklists.

The goal here isn't just to 'block ads', although they can be very annoying (use uBlock Origin for that), it's more about blocking spyware, unwanted telemetry, porn sites, and most important of all, known sites containing malware. This is not going to protect you 100%, but it's another layer of the onion.

# Blocklist Collection
This is a collection of blocklists you can use with PiHole, pfBlockerNG, or even locally as hosts files. They are split into the following categories:

1. Adblockers
2. Porn sites
3. Privacy & Telemetry
4. Malware
5. Windows Telemetry

# Criteria
These blocklists must be up to date, and updated frequently. If you would like to add some blocklists of your own, please submit a PR!