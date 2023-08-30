ansible-role-matrix
===================

Deploy matrix services. (WIP)

Todo:

- Install a new server from scratch
- Restart services (+daemon_reload)
- Add asreg
- See `TODO` in various files
- Remove code for deprecated unused federation_sender and pusher apps (see `TODO`)

Notes:

- ma1sd: installed from internal repo version 2.5.0 with patch from: https://github.com/ma1uta/ma1sd/issues/52
- ma1sd: package broken for bookworm (use manual install)
