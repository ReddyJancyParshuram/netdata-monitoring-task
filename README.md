# Monitor System Resources Using Netdata

## Objective:
Install Netdata and visualize system and app performance metrics.

## Tools:
- Netdata (Docker)
- Localhost (port 19999)

## Docker Command Used:
```bash
docker run -d --name=netdata -p 19999:19999 --cap-add SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata
