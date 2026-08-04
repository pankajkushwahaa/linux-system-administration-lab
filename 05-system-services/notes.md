# Notes

## systemd

systemd is the default service manager on most modern Linux distributions.

---

## systemctl

Main command used to manage services.

Common Commands:

systemctl status

systemctl start

systemctl stop

systemctl restart

systemctl reload

systemctl enable

systemctl disable

journalctl

---

## Service States

active (running)

inactive

failed

enabled

disabled

---

## Common Interview Questions

Q. Difference between restart and reload?

restart

Stops and starts the service again.

reload

Reloads configuration without stopping the service.

---

Q. Difference between enable and start?

enable

Starts service automatically at boot.

start

Starts service only for the current session.