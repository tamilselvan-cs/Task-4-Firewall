# Internship Task 4 — Windows Firewall Configuration

## Objective
Configure and demonstrate a firewall rule on Windows (block inbound Telnet port 23) and provide evidence.

## Steps carried out
1. Listed existing firewall inbound rules and saved to `outputs/windows_inbound_list_before.txt`.
2. Created a blocking rule: `Internship_Block_Telnet_23` (blocks TCP port 23).
3. Captured screenshot of rule in Windows Defender Firewall GUI (`screenshots/windows_rule_properties.png`).
4. Exported firewall configuration (`outputs/windows_firewall_backup.wfw`).
5. Removed the test rule and saved post-removal evidence (`outputs/check_deleted_rule.txt`).

## Files
- `commands.txt` — list of commands executed.
- `outputs/` — command outputs and exported firewall backup.
- `screenshots/` — before/after and rule properties screenshots.

## Notes
- Always ensure you are not remotely connected via RDP before making blocking rules that might lock you out.
- Local connectivity tests for Telnet may be inconclusive if no Telnet service is installed; provided GUI + export files as supporting evidence.
