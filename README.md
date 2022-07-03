
# Ansible Role: ISC DHCP Relay

## Description

Ansible role which installs and configures [ISC DHCP Relay](https://kb.isc.org/docs/isc-dhcp-44-manual-pages-dhcrelay).


## Example Vars

```yml
---
isc_dhcp_relay_run: true

isc_dhcp_upstream_interfaces:
  - enp1s0

isc_dhcp_relay_interfaces:
  - enp2s0

isc_dhcp_relay_options: ""

isc_dhcp_relay_servers:
  - 192.168.1.1
```

## Example Playbook

```yml
- hosts: all
  roles:
    - isc-dhcp-relay
```


## v1.0

- Initial git commit

## Author
* Lindsay Harvey
 
## License

This project is under the MIT License. See the LICENSE file for the full license text.

## Copyright

- Copyright (c) 2022 Lindsay Harvey