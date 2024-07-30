ansible-role-matrix
===================

Deploy matrix services. (WIP)

Todo:

- Install a new server from scratch
- Restart services (+daemon_reload)
- Add asreg
- See `TODO` in various files
- Remove code for deprecated unused federation_sender and pusher apps (see `TODO`)
- Generate MMR signing key and merge with homeserver key: https://docs.t2bot.io/matrix-media-repo/v1.3.5/installation/signing-key/

Notes:

- ma1sd: installed from internal repo version 2.5.0 with patch from: https://github.com/ma1uta/ma1sd/issues/52
- ma1sd: package broken for bookworm (use manual install)
