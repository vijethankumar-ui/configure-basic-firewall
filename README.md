# Windows Firewall Demo

This repository demonstrates basic firewall operations on Windows using PowerShell and GUI:

- Listing inbound rules
- Blocking a specific port (Telnet, port 23)
- Allowing SSH (port 22)
- Testing rules
- Cleaning up rules

## Usage

1. Open PowerShell **as Administrator**.
2. Run `firewall-commands.ps1` to apply test rules.
3. Follow instructions in `firewall-steps.md` for GUI steps.

## Notes

- Blocking a port prevents incoming connections on that port.
- Allowing a port permits incoming traffic.
- Always remove test rules after verification.
