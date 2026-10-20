# NDLab01 – Packet Tracer Introduction

**Student ID:** 21110025  
**Student name:** Đào Lê Anh Thư  
**Pod:** 1 (used as the working pod number)

## Project contents
- `lab1.pkt` — Cisco Packet Tracer lab file.
- `report/21110025_DaoLeAnhThu_ND-Lab01.pdf` — report for submission.
- `report/21110025_DaoLeAnhThu_ND-Lab01.docx` — editable report.
- `evidence/pc1_to_eagle_simulation_success.png` — Simulation Mode evidence showing a successful ICMP event from 1A to Eagle Server.

## Addressing summary
- R1-ISP S0/0/0: `10.10.10.6/30`
- R1-ISP Fa0/0: `192.168.254.253/24`
- R2-Central S0/0/0: `10.10.10.5/30`
- R2-Central Fa0/0: `172.16.255.254/16`
- Eagle Server: `192.168.254.254/24`, gateway `192.168.254.253`
- Host 1A: `172.16.1.1/16`, gateway `172.16.255.254`
- Host 1B: `172.16.1.2/16`, gateway `172.16.255.254`

## Verification
The lab was checked using gateway ping, serial-link ping, Eagle Server ping, traceroute, and host-to-host ping. See the report and `evidence/` for recorded evidence.

## Notes
Keep the `.pkt` file in the repository if the instructor permits it. If the course requires it to be submitted separately, submit the same `lab1.pkt` file separately as well. Do not upload passwords or other private credentials.
