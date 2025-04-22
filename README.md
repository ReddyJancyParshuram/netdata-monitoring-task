# Monitor System Resources Using Netdata

## Objective:
Install Netdata and visualize system and app performance metrics.

## Tools:
- Netdata (Docker)
- Localhost (port 19999)

## Docker Command Used:
``bash(terminal)
docker run -d --name=netdata -p 19999:19999 --cap-add SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata
Dashboard:
Netdata dashboard accessed at: http://localhost:19999
Screenshots:
Outcome:
Successfully monitored live system metrics like CPU, RAM, disk, and network using Netdata.
