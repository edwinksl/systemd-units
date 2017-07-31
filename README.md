Repository for systemd unit files.

# Instructions

1. Change `User` to your username
2. Copy unit file to `/etc/systemd/system`: `cp foobar.service /etc/systemd/system`
3. Start service: `systemctl start foobar`
4. Enable service: `systemctl enable foobar`
5. Check status of service: `systemctl status foobar`
