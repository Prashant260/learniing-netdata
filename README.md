# Task 7 – Monitor System Resources Using Netdata

## Objective
To monitor system metrics using Netdata installed via Docker.

## Tools Used
- Docker
- Netdata
- Ubuntu WSL

## Steps Followed
1. Pulled and ran Netdata using:
   ```bash
   docker run -d --name=netdata -p 19999:19999 --cap-add SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata
